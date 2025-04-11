# Solana Hello World Program

A minimal Solana program written in Rust that prints "Hello, world!" to the program log. AITU SE-2320 BT2

## Program Details
- **Language**: Rust
- **Framework**: Solana Program (v1.18.26)
- **Network**: Devnet

## Setup
### 1. Clone the repository
git clone https://github.com/Marticat/BT2_2
cd hello-world-solana

### 2. Install Solana CLI:
   sh -c "$(curl -sSfL https://release.solana.com/v1.18.26/install)"
   
###   3.Configure for devnet:
solana config set --url https://api.devnet.solana.com

## Build & Deploy
cargo build-sbf
solana program deploy ./target/deploy/hello_world.so

## Screenshots
![Снимок экрана 2025-04-11 132938](https://github.com/user-attachments/assets/30881127-9a47-41b1-8673-b24f1050b206)
