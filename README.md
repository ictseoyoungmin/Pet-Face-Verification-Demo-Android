# Pet Face Verification Demo

A prototype Android application for pet face verification using face embedding vectors and comparison with a face bank.

## Demo

<div align="center">
  <video width="460" controls>
    <source src="PetFaceUI_demo_460.mp4" type="video/mp4">
  </video>
</div>

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


