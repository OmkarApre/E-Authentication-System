# E-Authentication-System using QR code, OTP and Aadhar
## Introduction

This repository contains the implementation of an E-Authentication system that aims to provide secure and user-friendly login mechanisms for various online platforms, particularly in the context of financial services and online exam portals. The system utilizes QR Code, One Time Password (OTP), and Aadhar authentication methods to enhance security and usability.

## Features

- Efficient and secure user login process.
- Protection against password collection through shoulder surfing.
- Implementation of complex password techniques with a user-friendly interface.
- Multiple authentication options: QR Code, OTP, and Aadhar.
- Integration with email for identity verification.

## How It Works

The E-Authentication System offers a three-tier authentication process to ensure comprehensive security:

1. **QR Code Authentication:**
   - When a user selects QR Code authentication, the system generates a unique QR Code.
   - This QR Code is sent to the user's registered email address.
   - The user scans the QR Code using a compatible device, which redirects them to the authentication portal.

2. **OTP Authentication:**
   - Upon choosing OTP authentication, the system sends a One Time Password (OTP) to the user's registered mobile number.
   - The user enters the received OTP into the authentication portal.

3. **Aadhar Authentication:**
   - In the final stage, the user is prompted to provide their Aadhar number.
   - The Aadhar number serves as a unique identifier for the user.
   - The system verifies the Aadhar number with the Aadhar database for authentication.

If the user successfully passes any of the three authentication stages, they are granted access to the main platform. The multi-layered approach ensures that even if one method is compromised, the user's account remains secure due to the other layers of protection.
