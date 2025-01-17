# Information Theory and Coding Project

This repository contains the implementation of **CIE 425 Information Theory and Coding** course project, divided into two parts. The project aims to explore and implement key concepts of source and channel coding, as well as to develop an end-to-end communication system. 

## Table of Contents
- [Project Overview](#project-overview)
- [Part 1: Source Coding](#part-1-source-coding)
- [Part 2: Channel Coding](#part-2-channel-coding)
- [Software Requirements](#software-requirements)
- [Features](#features)
- [Contributors](#contributors)

---

## Project Overview

This project demonstrates the principles of information theory and coding by:
1. Estimating symbol probabilities and calculating entropy.
2. Implementing Huffman and Shannon-Fano encoding/decoding.
3. Implementing the (7,4) Hamming code for channel encoding/decoding with AWGN noise.
4. Integrating source coding and channel coding into a full communication system.

---

## Part 1: Source Coding

**Objective**: Encode text data efficiently using Huffman and Shannon-Fano coding.

### Features:
- Estimate symbol probabilities from a given text file.
- Calculate entropy and efficiency of fixed-length codes.
- Implement Huffman and Shannon-Fano encoding/decoding without using built-in functions.
- Compare the performance of Huffman and Shannon-Fano codes.

### Steps:
1. Compute symbol probabilities for 33 characters (a-z, space, punctuation).
2. Calculate entropy and fixed-length code efficiency.
3. Develop custom Huffman encoder/decoder functions.
4. Implement Shannon-Fano encoder/decoder and compare with Huffman.

---

## Part 2: Channel Coding

**Objective**: Implement (7,4) Hamming code for error correction.

### Features:
- Encode data using (7,4) Hamming code without built-in functions.
- Add AWGN noise to simulate a communication channel.
- Decode noisy data and correct errors using syndrome decoding.
- Compare BER vs. SNR performance with and without coding.

### Steps:
1. Encode data with (7,4) Hamming code.
2. Add AWGN noise with varying SNR levels.
3. Decode noisy data and correct errors.
4. Integrate with source coding to create a complete communication system.
5. Analyze received text files for errors at different SNR levels.

---

## Software Requirements

- **Python 3.8+**
- **NumPy** (for numerical operations)
- **Matplotlib** (for plotting BER vs. SNR)

---

## Features

1. **Source Coding**:
   - Huffman and Shannon-Fano Encoding/Decoding.
   - Entropy and efficiency calculation.

2. **Channel Coding**:
   - (7,4) Hamming Code Encoding/Decoding.
   - Noise addition with AWGN.
   - BER vs. SNR analysis.

3. **Integrated Communication System**:
   - Combines source coding and channel coding.
   - Validates text file integrity after transmission with error correction.

---
## Contributors

The following individuals have contributed to this project:

- **Adham Ahmed**  
  Email: [s-adham.saad@zewailcity.edu.eg](mailto:s-adham.saad@zewailcity.edu.eg)

- **Amar Sherif**   
  Email: [s-amar.shabaan@zewailcity.edu.eg](mailto:s-amar.shabaan@zewailcity.edu.eg)

- **Ahmed Mohamed**  
  Email: [s-ahmed.mohamed@zewailcity.edu.eg](mailto:s-ahmed.mohamed@zewailcity.edu.eg)

- **Omar Awad**  
  Email: [s-omar.awad@zewailcity.edu.eg](mailto:s-omar.awad@zewailcity.edu.eg)

