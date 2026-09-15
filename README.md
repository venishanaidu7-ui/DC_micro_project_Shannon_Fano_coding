# Shannon-Fano Compressed Text Transmission

## Project Overview

This project is a MATLAB-based simulation of text compression and transmission using the Shannon-Fano coding technique.

The system consists of two main parts:

* **Transmitter**
* **Receiver**

The transmitter accepts text from the user, calculates character frequencies, generates Shannon-Fano codes, and converts the text into compressed binary data.

The receiver receives the compressed binary data and uses the Shannon-Fano code table to decode it back into the original text.

## Features

* Text input through a MATLAB GUI
* Character frequency calculation
* Shannon-Fano code generation
* Text compression into binary data
* Compression statistics
* Transmitter GUI
* Receiver GUI
* Decompression of received data
* Transmission success/error checking

## Working

### Transmitter

1. User enters text.
2. The program finds the frequency of each character.
3. Characters are sorted according to their frequency.
4. Shannon-Fano codes are generated.
5. The original text is converted into compressed binary data.
6. Compression statistics are displayed.
7. The compressed data is sent to the receiver.

### Receiver

1. The receiver gets the compressed binary data.
2. The Shannon-Fano code table is used for decoding.
3. The binary data is converted back into text.
4. The decoded text is compared with the original text.
5. The system displays whether the transmission was successful or had an error.

## Technologies Used

* MATLAB
* Shannon-Fano Coding
* Data Compression
* Digital Communication Simulation
* GUI

## How to Run

1. Open MATLAB.
2. Open `DC_micro_project_Shannon_Fano_coding.m`.
3. Run the program.
4. Enter the text in the transmitter window.
5. Click **COMPRESS AND TRANSMIT**.
6. The receiver window will appear.
7. Click **DECOMPRESS / RECEIVE**.
8. The original text will be displayed after decoding.

## Project Type

Simulation-based Digital Communication Project.

<img width="672" height="719" alt="image" src="https://github.com/user-attachments/assets/1aa3acb1-3558-4088-8e94-73c64d33eb86" />
<img width="689" height="717" alt="image" src="https://github.com/user-attachments/assets/30550d90-ea47-40a0-b52d-0836963c9bf1" />

