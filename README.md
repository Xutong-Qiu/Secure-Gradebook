# Secure-Gradebook

## Overview

This repository contains the design and implementation of a robust gradebook system, designed to meet to the needs of secure gradebook data management.

## Security Measures

The gradebook system is fortified with multiple security measures to safeguard against a variety of attacks:
- **Buffer Overflow Protection**: Mitigation techniques to prevent buffer overflow vulnerabilities.
- **Man-in-the-Middle Attack Defense**: Utilization of authentication encryption mode (GCM) to detect unauthorized alterations.
- **IV-Key Pair Reuse Prevention**: Generation of new, randomized IVs for each encryption operation to enhance security.
- **Integer Overflow Handling**: Checks and balances to handle integer overflows.
- **Protection Against Fake Gradebook Attacks**: Encryption of the gradebook name to verify consistency and prevent unauthorized overwriting.

To learn more about the detailed architecture, security features, and functionality of this system, please refer to the accompanying report PDF.
