# Peer-to-Peer Instagram-like Application

This repository contains the implementation of a Peer-to-Peer Instagram-like application based on a distributed cloud system for encryption, developed in Rust. The system implements sophisticated features like load balancing, fault tolerance, and secure image encryption and decryption among peers.

## Project Overview

The application is designed to provide a platform similar to Instagram but with enhanced privacy through encrypted peer-to-peer (P2P) communication. Key features include:

- **Load Balancing:** Distributes requests evenly across cloud servers.
- **Fault Tolerance:** Handles server failures seamlessly without interrupting user experience.
- **Image Encryption and Decryption:** Ensures that images are securely encrypted and decrypted between clients using advanced steganography techniques.

## System Architecture

The system utilizes a combination of cloud servers and client applications to manage communication and data encryption. The architecture supports both UDP and TCP communications, prioritizing speed and efficiency in data handling.

## Getting Started

### Prerequisites

- Rust programming environment
- Cargo package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShahdElmahallawy/Distributed-Photo-Sharing-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Distributed-Photo-Sharing-App
   ```
3. Compile and run the application:
   ```bash
   cargo run
   ```

## Usage

After starting the server and client applications, users can perform the following actions:

- **Log in** to the system to start sending and receiving encrypted images.
- **Send images** to other clients, which will be automatically encrypted and decrypted.

## Libraries Used

- `queues` for managing server queues.
- `steganography` for image encoding and decoding.
- `photon-rs` for image processing.
- `tokio` for asynchronous programming.
- `serde` and `serde_json` for serialization and deserialization of data.

## Authors
- Mariam Dahab - Image encryption and fault tolerance
- Mira Shanouda - Load balancing and offline handling
- Nada Ayman - P2P communication and service directory management
- Shahd Elmahallawy - Image decryption and client-server communication

