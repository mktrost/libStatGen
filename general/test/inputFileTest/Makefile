EXE = inputFileTest
TOOLBASE = InputFileTest

TEST_COMMAND=	mkdir -p results && \
	./inputFileTest && \
	diff data/InputFileTest.bam results/bgzfFile.glf && \
	diff data/InputFileTest.txt results/defaultFile.glf && \
	diff data/InputFileTest.gz results/defaultFile.gz && \
	diff data/InputFileTest.gz results/gzipFile.glf && \
	diff data/InputFileTest.txt results/InputFileTest.glf && \
	diff data/InputFileTest.txt results/uncompressedFile.glf

include ../../../Makefiles/Makefile.test