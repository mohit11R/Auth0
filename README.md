# Auth0

What is Authentication? Authentication is the process of verifying the identity of a user, device, or system to make sure they are who (or what) they claim to be.

Password less Authentication It is a security method that allows users to log in without using a traditional password. Instead, it verifies identity using more secure and user-friendly alternatives.

Two Password Less Approaches

One-time passcode, biometrics or magic links via Email/SMS
Passkeys: Based on WebAuthn standard and FIDO Alliance
How Passkeys Work -- Private Key stays on your device -- Public Key stored on thr server -- Device signs a server challenge with the private key -- Server verifies with the public key

Benefits of Passkeys

Multi-Factor Authentication: Biometrics or hardware-based
Device-Independent: syncs across devices
Phishing-Resistant: No password to steal
Security: Strong encryption
Convenience: No need to remember passwords
No password resets: Eliminates the need for recovery steps
Passkey Flow: Registration

User visits website/app for the first time
Server generates a challenge
Device signs challenge with private key(after biometric/PIN verification)
Public key is sent to the server for future logins
Passkey Flow: Authentication

Server sends a new challenge
Device signs it with the private key(after biometric/PIN verification)
Server verifies signature with the stored public key
User is authenticated
Types of Authorization Models

Role-Based Access Control(RBAC)
Attribute-Based Access Control(ABAC)
Policy-BAsed Access Control
What is Identity and Access Management (IAM)? It is a framework of policies, processes, and technologies used to ensure that the right people (or systems) have the right access to the right resources at the right time

Three Fundamental Pillars of IAM

User Authentication
User Authorization
User Management
-- Key IAM Features

Automation and centralization
Enforced Security Controls
Enhanced User Experience
-- Importance of IAM for Compliance and Security

Protect digital
Ensure regulatory Compliance
