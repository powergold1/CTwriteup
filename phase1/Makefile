TARGET=WriteupPhase1

all: $(TARGET).pdf

.PHONY: clean $(TARGET).pdf

$(TARGET).pdf:
	latexmk -quiet  -pdf $(TARGET).tex
	rubber-info $(TARGET)

clean:
	latexmk -C $(TARGET).tex
