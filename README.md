# Secure Communication System (Go)

## Overview  
The **Secure Communication System** is a project designed to ensure private and reliable data exchange over a network. It integrates modern encryption techniques, robust key management, and authentication mechanisms to protect against common security threats such as tampering and replay attacks.

---

## Key Features  
- **Data Encryption and Authentication**:  
  Implemented an "Encrypt-Then-MAC" approach, combining symmetric encryption for data privacy and HMAC for integrity verification. This ensures that data is secure and unaltered during transmission.

- **Secure Key Exchange**:  
  Developed a key management system using Argon2 key derivation and HashKDF to securely generate and exchange encryption keys.

- **User Authentication**:  
  Built functionality for verifying users and ensuring the integrity of data files, allowing only authorized users to access the system.

- **Robustness Against Attacks**:  
  Tested the system for resilience against replay attacks, man-in-the-middle attacks, and data corruption scenarios.

---

## System Architecture  
- **Hybrid Encryption**:  
  Combines public key cryptography for secure key exchange and symmetric encryption for efficient data transmission.

- **File Sharing and Revocation**:  
  Includes features for securely sharing files between users and the ability to revoke access when necessary.

- **Data Structures**:  
  Utilizes linked data structures to track file versions, enabling efficient storage and retrieval.

---

## Challenges and Solutions  
1. **Designing a Secure Key Exchange Mechanism**  
   - **Solution**: Used Argon2 and HashKDF for strong, secure, and efficient key generation to resist brute force attacks.

2. **Protecting Data Integrity**  
   - **Solution**: Added HMAC-based integrity checks to detect unauthorized modifications during transmission.

3. **Simulating Network Attack Scenarios**  
   - **Solution**: Conducted testing for replay and man-in-the-middle attacks, iteratively improving the system's defenses.

---

## Diagrams

<img width="745" alt="Screenshot 2024-12-02 at 11 45 18 AM" src="https://github.com/user-attachments/assets/8e00578b-5aa1-4332-a1e4-9319e967bb77">

---

## Key Takeaways  
- Developed expertise in modern encryption techniques and secure communication protocols.  
- Designed and tested a system capable of balancing security with performance.  
- Gained hands-on experience in debugging and improving systems under adversarial conditions.

---

## Contact  
For more information about this project, feel free to reach out.  
