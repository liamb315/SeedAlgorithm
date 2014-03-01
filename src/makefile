# makefile for SeedAlgorithm Code

# Compiler
CC=icc

# Compilation Flags
CFLAGS=-openmp -vec-report=3 -O3 -I

all:
	$(CC) $(CFLAGS) ../tools ArraySeedAlgorithm.C ../tools/ReadSeedFile.C -o ../output/arrayTest

