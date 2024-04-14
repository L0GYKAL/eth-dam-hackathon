# CoconyM

Welcome to CoconyM, a sophisticated mixer built in Rust with advanced privacy features and a convenient swap functionality. CoconyM leverages the power of the Oasis network, a blockchain network that relies on Intel SGX for trusted and confidential computing. With CoconyM, users can ensure their transactions remain private and secure while enjoying the benefits of seamless mixing and swapping of assets.

## Features

### Advanced Privacy

CoconyM ensures your transactions remain confidential with its advanced privacy features. Every transaction is securely processed using Intel SGX technology, guaranteeing the privacy and integrity of your data.

### Secret Sharing

Users generate a secret shared with the Trusted Execution Environment (TEE), which can be changed at any time. This secret ensures secure communication and allows users to merge balances deposited from multiple addresses.

### Seamless Mixing

Easily merge balances from multiple addresses using the same secret. CoconyM simplifies the process of consolidating your funds while maintaining the highest level of privacy and security.

### Swap Functionality

CoconyM features a convenient swap functionality based on an Intent mechanism. Users can get the best price for their assets while avoiding front-running and minimizing the risk of Miner Extractable Value (MEV).

### Withdrawal Flexibility

Request withdrawals to multiple addresses with different tokens and amounts, along with added delays to break correlation between transactions. CoconyM ensures your withdrawals remain private and secure, protecting your assets from prying eyes.

## How It Works

1. **Deposit**  
  ![Deposit Image Placeholder](https://github.com/L0GYKAL/eth-dam-hackathon/assets/32228897/e967cc45-10cc-4265-a506-b41cd227db8d)
  Users deposit funds into CoconyM using their secret shared with the TEE. Funds are securely processed and added to the user's balance.

2. **Swap**  
  ![Swap Image Placeholder](https://github.com/L0GYKAL/eth-dam-hackathon/assets/32228897/901b6a1c-fe71-4fb1-bcfa-6c8d9b33ee9a)
  Utilize the swap functionality to exchange assets at the best possible price while ensuring privacy and security.

3. **Withdraw**  
   ![withdraw](https://github.com/L0GYKAL/eth-dam-hackathon/assets/32228897/74c64951-71cb-4044-b823-3f793a214081)
  Request withdrawals to multiple addresses with different tokens and amounts, along with added delays, to maintain privacy and security.

## Getting Started

To get started with CoconyM, follow these steps:

1. Clone the CoconyM repository.
2. Install Rust and dependencies.
3. Build the project using `cargo build`.
4. Run CoconyM using `cargo run`.
5. Start mixing and swapping your assets with confidence!

## Contribution

Contributions to CoconyM are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request or open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for choosing CoconyM for your privacy and security needs. Happy mixing! 🌴✨
