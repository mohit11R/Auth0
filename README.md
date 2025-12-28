# Auth0

# Customer Identity and Access Management (CIAM) — Theory

This repository provides a high-level overview of **Customer Identity and Access Management (CIAM)** concepts, focusing on authentication, passwordless authentication, passkeys, authorization models, and IAM fundamentals.

---

## 📌 What is Authentication?

**Authentication** is the process of verifying the identity of a user, device, or system to ensure they are who (or what) they claim to be.

---

## 🔐 Passwordless Authentication

**Passwordless Authentication** is a security approach that allows users to sign in without traditional passwords.  
Instead, it uses more secure and user-friendly alternatives to verify identity.

### Passwordless Authentication Approaches

1. **One-Time Passcodes (OTP), Biometrics, or Magic Links**
   - Delivered via **Email** or **SMS**
2. **Passkeys**
   - Based on the **WebAuthn** standard and supported by the **FIDO Alliance**

---

## 🔑 Passkeys

Passkeys replace passwords with cryptographic key pairs for stronger and phishing-resistant authentication.

### How Passkeys Work

- 🔒 **Private Key** stays securely on the user’s device
- 🌐 **Public Key** is stored on the server
- ✍️ Device signs a server-generated challenge using the private key
- ✅ Server verifies the signature using the public key

---

### ✅ Benefits of Passkeys

1. **Multi-Factor Authentication**
   - Uses biometrics or hardware-based verification
2. **Device-Independent**
   - Can sync securely across devices
3. **Phishing-Resistant**
   - No passwords to steal or reuse
4. **High Security**
   - Strong public-key cryptography
5. **User Convenience**
   - No passwords to remember
6. **No Password Resets**
   - Eliminates recovery and reset flows

---

## 🔁 Passkey Authentication Flows

### Registration Flow

1. User visits the website or application for the first time
2. Server generates a cryptographic challenge
3. Device signs the challenge after biometric or PIN verification
4. Public key is sent and stored on the server for future logins

---

### Authentication Flow

1. Server sends a new challenge
2. Device signs the challenge using the private key (after biometric/PIN verification)
3. Server verifies the signature using the stored public key
4. User is successfully authenticated

---

## 🛂 Authorization Models

Authorization determines **what an authenticated user is allowed to do**.

### Common Authorization Models

1. **Role-Based Access Control (RBAC)**
   - Access based on assigned roles
2. **Attribute-Based Access Control (ABAC)**
   - Access based on user, resource, and environment attributes
3. **Policy-Based Access Control (PBAC)**
   - Access driven by defined policies and rules

---

## 🧩 What is Identity and Access Management (IAM)?

**Identity and Access Management (IAM)** is a framework of policies, processes, and technologies that ensures:

> The right people (or systems) have the right access to the right resources at the right time.

---

### 🏛 Three Fundamental Pillars of IAM

1. **User Authentication**
2. **User Authorization**
3. **User Management**

---

## ⚙️ Key IAM Features

1. **Automation and Centralization**
2. **Enforced Security Controls**
3. **Enhanced User Experience**

---

## 🔐 Importance of IAM for Security & Compliance

1. **Protect Digital Resources**
2. **Ensure Regulatory Compliance**
