# NTU_IT_jpeg_decoder

## Files
1. src/decoder.c: jpeg decoder source code
2. /Image: Some sample images for testing the decoder
3. /Makefile: use "make" can easily compile decoder.c and test the output

## Environment
OS: Ubuntu 18.04.5
gcc: version 7.5.0

## Setup and run
- make: will compile src/decoder and output a executable file /jpeg_decoder
- make test: compile src/decoder and test four images in the /Image, finally output the .bmp files in the /output
