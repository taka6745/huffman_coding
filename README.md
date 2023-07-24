# Huffman Coding Project

## Overview

This project implements the Huffman coding algorithm for lossless data compression in Python.

## Features

- Frequency analysis of characters in the input data.
- Building the Huffman tree based on character frequencies.
- Generating variable-length codes for each character.
- Compressing data using Huffman coding.
- Decompressing data using the Huffman tree.

## Usage

1. Clone the repository:

```
git clone https://github.com/your_username/huffman_coding_project.git
```

2. Navigate to the project directory:

```
cd huffman_coding_project
```

3. Run the Python script to compress a file:

```
python huffman_compress.py input_file.txt output_file.huf
```

4. To decompress a file:

```
python huffman_decompress.py output_file.huf decompressed_output.txt
```