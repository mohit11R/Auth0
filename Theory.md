<!-- Customer Identity and Access Management Theory -->

***What is Authentication?***
Authentication is the process of verifying the identity of a user, device, or system to make sure they are who (or what) they claim to be.


***Password less Authentication***
It is a security method that allows users to log in without using a traditional password.
Instead, it verifies identity using more secure and user-friendly alternatives.

*****Two Password Less Approaches*****
1. One-time passcode, biometrics or magic links via Email/SMS
2. Passkeys: Based on WebAuthn standard and FIDO Alliance

How Passkeys Work
-- Private Key stays on your device
-- Public Key stored on thr server
-- Device signs a server challenge with the private key
-- Server verifies with the public key

Benefits of Passkeys
1. Multi-Factor Authentication: Biometrics or hardware-based
2. Device-Independent: syncs across devices
3. Phishing-Resistant: No password to steal
4. Security: Strong encryption
5. Convenience: No need to remember passwords
6. No password resets: Eliminates the need for recovery steps

***Passkey Flow: Registration***
1. User visits website/app for the first time
2. Server generates a challenge
3. Device signs challenge with private key(after biometric/PIN verification)
4. Public key is sent to the server for future logins

***Passkey Flow: Authentication***
1. Server sends a new challenge
2. Device signs it with the private key(after biometric/PIN verification)
3. Server verifies signature with the stored public key
4. User is authenticated


**Types of Authorization Models**
1. Role-Based Access Control(RBAC)
2. Attribute-Based Access Control(ABAC)
3. Policy-BAsed Access Control


**What is Identity and Access Management (IAM)**?
It is a framework of policies, processes, and technologies used to ensure that the right people (or systems) have the right access to the right resources at the right time

***Three Fundamental Pillars of IAM***
1. User Authentication
2. User Authorization
3. User Management

-- Key IAM Features
1. Automation and centralization
2. Enforced Security Controls
3. Enhanced User Experience

-- Importance of IAM for Compliance and Security
1. Protect digital
2. Ensure regulatory Compliance
