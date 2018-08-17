# Define some implicit rules for "compiling" abc files to PDF and MIDI
OBJDIR	:= objects
SRCDIR	:= src
SHELL	:= bash

OBJECTS	:= $(shell echo $(OBJDIR)/{stones,stones-karaoke}.{mid,wav,ogg,pdf})


$(OBJDIR)/%.mid : $(SRCDIR)/%.abc
	abc2midi $< -o $@ -quiet

$(OBJDIR)/%.wav : $(OBJDIR)/%.mid
	timidity -Ow -idq $<

$(OBJDIR)/%.ogg : $(OBJDIR)/%.wav
	sox --norm=-3 $<  --comment TITLE=Stones --add-comment ARTIST=Iolo $@

$(OBJDIR)/%.ps : $(SRCDIR)/%.abc
	abcm2ps $< -O $@

$(OBJDIR)/%.pdf : $(OBJDIR)/%.ps
	ps2pdf $< $@



default: $(OBJECTS)

play: $(OBJDIR)/stones-karaoke.mid
	timidity -Et $<

playogg: $(OBJDIR)/stones-karaoke.ogg
	play $<

clean:
	rm $(OBJECTS) 2>/dev/null || true

