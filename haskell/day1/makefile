# Makefile

# Compiler
HC = ghc

# Source files
SRC = Main.hs

# Output executable
OUT = myprogram

# Compile and run
all: $(OUT)
	./$(OUT)

# Compile the Haskell source
$(OUT): $(SRC)
	$(HC) -o $(OUT) $(SRC)

# Clean generated files
clean:
	rm -f $(OUT) *.hi *.o