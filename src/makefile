# makefile for SeedAlgorithm Code

# Compiler
CC=icc

# Compilation Flags
CFLAGS=-openmp -vec-report=3 -O3 -I ../tools

all:
	$(CC) $(CFLAGS) ArraySeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/arrayTest
	$(CC) $(CFLAGS) StructSeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/structTest

array:
	$(CC) $(CFLAGS) ArraySeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/arrayTest

struct:
	$(CC) $(CFLAGS) StructSeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/structTest	

clean:
	rm -f ../output/arrayTest
	rm -f ../output/structTest