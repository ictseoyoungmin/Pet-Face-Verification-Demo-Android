# Pet Face Verification Demo

A prototype Android application for pet face verification using face embedding vectors and comparison with a face bank.

## Demo

https://github.com/user-attachments/assets/2e5b232f-c1f0-4c22-85e5-50c569b9dfbd


https://github.com/user-attachments/assets/d8f22c99-d5d7-4609-b64f-50a53aba8e28




## Overview

This is a minimal prototype implementation of a pet face verification system. The application extracts face embedding vectors from five different angles and compares them against a stored face bank for verification purposes.

## Features

### Face Embedding Extraction
- Captures face images from **5 different angles**:
  - Front
  - Up
  - Down
  - Left
  - Right
- Extracts embedding vectors from each angle
- Stores embeddings in the face bank for future reference

### Face Verification
- Compares query face embedding vectors against stored face bank vectors
- Identifies matching pets based on embedding similarity

## Technology Stack

- **Platform**: Android
- **Language**: Kotlin
- **IDE**: Android Studio
- **Device**: Galaxy S25 Ultra / S20 Ultra   

## Architecture

### Components

1. **Face Embedding Extraction**
   - Multi-angle face image capture
   - Embedding vector generation
   - Face bank storage

2. **Verification Engine**
   - Query vector extraction
   - Vector comparison and matching
   - Similarity-based verification

## Device Specifications

- **Device**: Samsung Galaxy 25 Ultra
- **OS**: Android (16)
- **Architecture**: Full edge-based processing (TFLite)


