# makefile for SeedAlgorithm Code

# Compiler
CC=icc

# Compilation Flags
CFLAGS=-openmp -vec-report=3 -O3 -I

all:
	$(CC) $(CFLAGS) ../tools ArraySeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/arrayTest
	$(CC) $(CFLAGS) ../tools StructSeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/structTest

array:
	$(CC) $(CFLAGS) ../tools ArraySeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/arrayTest

struct:
	$(CC) $(CFLAGS) ../tools StructSeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/structTest	