# Attendance-management-system-using-blockchain

INTRODUCTION
Blockchain is the technology behind cryptocurrencies such as Bitcoin, Ethereum, Litecoin etc.

A blockchain, is a list of records, called blocks, which are linked and secured using cryptography. Each block contains a cryptographic hash of the previous block, a timestamp and transaction data. The data, once entered in a block is immutable due to the way blockchains are designed.

This concept of immutable digital data storage can be used for storing data securely, such as student attendance, medical records, and financial transactions, to prevent tampering with this data.

Disclaimer and assumptions
This project is to be considered as a proof of concept only. As such the basic algorithm behind a blockchain is used which constructs blocks and associates them using their cryptographic hashes. A proof of work or proof of stake algorithm has not been implemented to prevent the need for higher computing resources. Unlike traditional decentralized blockchains, this blockchain works using a centralized flask server to avoid dealing with multiple nodes unnecessarily for now.

Some assumptions have been made in this project:

A teacher will enter the attendance of a class, only once for a date. Multiple lectures in a day are not supported.
Roll numbers are assumed to start from 1 for each class.
Roll numbers of students who are repeating a year, will not be available.
