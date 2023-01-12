# Tensornetics, Quantum Cryptography Key Distribution Network (QCKDN)

The Quantum Cryptography Distribution is a collection of hardware and software components for implementing quantum key distribution and post-quantum cryptographic schemes.

## Contents

- Hardware: 
  - Quantum key generation
  - Quantum channel implementation
  - Quantum receiver implementation
- Software: 
  - Error correction
  - Privacy amplification
  - Key distribution
  - Key management
  - Network integration
  - Post-quantum cryptographic schemes
- Data:
  - Data encryption
  - Data decryption

## Requirements

- Rust programming language
- Kubernetes
- Istio service mesh
- ReactJS

## Installation

- See the `doc/installation_guide.md` for installation instructions.

## Usage

- See the `doc/user_guide.md` for usage instructions.

## Deployment

- See the `deployment/` for k8s manifests and istio config.

## Security

- See the `security/` for security assessments and hardening guides.

## Development

- See the `CONTRIBUTING.md` for development guidelines and instructions for submitting pull requests.

## Contact

- Email: [info@tensornetics.com](mailto:info@tensornetics.com)
- Website: [https://www.tensornetics.com](https://www.tensornetics.com)


```
quantum-cryptography-distribution/
├── Cargo.toml
├── hardware/
    ├── quantum_key_gen.rs
    ├── quantum_channel.rs
    ├── quantum_receiver.rs
├── software/
    ├── error_correction.rs
    ├── privacy_amplification.rs
    ├── key_distribution.rs
    ├── key_management.rs
    ├── network_integration.rs
    ├── post_quantum_crypto.rs
├── data/
    ├── data_encryption.rs
    ├── data_decryption.rs
├── test/
├── gui/
    ├── frontend/
        ├── react_code/
    ├── backend/
├── deployment/
    ├── k8s/
        ├── manifests/
    ├── istio/
        ├── config/
├── security/
├── doc/
    ├── installation_guide.md
    ├── user_guide.md
    ├── design_doc.md
    ├── security_guide.md
    ├── testing_report.md
```
