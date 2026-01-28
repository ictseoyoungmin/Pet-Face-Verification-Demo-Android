# Pet Face Verification Demo

A prototype Android application for pet face verification using face embedding vectors and comparison with a face bank.

## Demo


https://github.com/user-attachments/assets/268a4133-ed7d-41d9-a979-70d52693d771

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
- **Device**: Galaxy 25 Ultra 

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


