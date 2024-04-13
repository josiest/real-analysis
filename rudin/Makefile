CC=pdflatex
OUTPUT_DIR=build

CHPT_NAME_03 := numerical-sequences-and-series
CHPT_NAME_04 := continuity
CHPT_NUM ?= 04

OUTPUT_NAME=$(CHPT_NUM)-$(CHPT_NAME_$(CHPT_NUM))

target:
	mkdir -p $(OUTPUT_DIR)
	$(CC) -output-directory $(OUTPUT_DIR) $(OUTPUT_NAME).tex

main:
	make target CHPT_NUM=04
