# Selective Disclosure & ZKP Triggers

This repository contains the foundational components for Selective Disclosure Routing and ZKP (Zero-Knowledge Proof) Triggers used within Verit's decentralised identity system. These features optimise privacy by enabling users to disclose only the necessary pieces of their identity while still proving the authenticity of their credentials.

## Overview

Selective disclosure ensures that users can control exactly what information is shared, preventing overexposure of sensitive data. The ZKP triggers work in tandem with selective disclosure, generating cryptographic proofs only when specific conditions are met, ensuring minimal data is revealed while maintaining security and trust.

### Key Concepts:

- **Selective Disclosure**: Enables fine-grained control over what parts of a user's credential are shared, allowing for greater privacy in digital interactions.

- **ZKP Triggers**: Automatically generate cryptographic proofs based on specific conditions, ensuring that only the necessary proof is provided, without compromising privacy.

- **Modular Design**: Easily integrates with both decentralised and traditional identity systems, offering flexibility and scalability.

## Features:

- **Data Minimisation**: Only the relevant data is disclosed during interactions, reducing the risk of overexposing sensitive information.

- **Context-Aware Proof Generation**: ZKPs are triggered based on predefined conditions, ensuring that users only disclose what is necessary for a specific transaction or request.

- **Privacy-Preserving**: Achieves privacy goals by relying on cryptographic proofs rather than exposing actual data.

## Use Cases:

- **Credential Verification**: Users can prove certain aspects of their identity (e.g., age, qualifications) without revealing all of their data.

- **Selective Sharing**: Useful in scenarios like online transactions, job applications, or government services where only certain pieces of information need to be shared.

- **Cross-Platform Integration**: The middleware layer can be adapted for a range of systems, from Web2 applications to decentralised platforms.

## Installation & Setup:

To integrate this system into your own applications, simply follow the setup steps outlined in the documentation. The system is modular and can be easily configured for your specific use case, whether you're building a new identity verification system or enhancing an existing one.

## Licence:

This project is licensed under the MIT License.