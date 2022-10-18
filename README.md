# ECC-Data-Transmission Lab 2

Group Members: Cody Chinothai and Van Luu

Cody Chinothai - ECC Generator

Van Luu - ECC Detector

Lab 2 ECC Gen.clf 
- The ECC generator is a hamming code based error detection circuit within the I/O controller that uses even parity to turn an 8-bit data vector into a 13-bit data vector that includes 5 parity bits. 
- The first 4 parity bits (P0 - P3) exist to detect single bit errors while the last parity bit (P5) allows single bit errors to be corrected and double errors to be detected. 
- Once the 13 bits are generated, they are sent to the memory via the 13-bit data transmission bus. 
