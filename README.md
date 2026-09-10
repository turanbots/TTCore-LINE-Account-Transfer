# TTCore LINE Account Transfer

A desktop solution that generates a short-lived QR code from a primary token, allowing users to sign in to or transfer a LINE account on a new phone.

> This repository is for product presentation purposes only. The source code is not publicly available.

## What Does It Do?

TTCore LINE Account Transfer validates a valid LINE primary token and creates a single-use QR session. The generated QR code can be scanned with the official LINE app on the new phone to complete the sign-in or account transfer process.

## Features

- Primary token validation
- Short-lived, single-use QR code generation
- LINE account sign-in or transfer from a mobile phone using a QR code
- Account name display for verification
- Real-time transfer status tracking
- Clear status messages for successful, expired, and failed operations
- Local web interface
- Windows 10 and Windows 11 support
- Simple startup and straightforward workflow
- Security-focused design that does not write tokens, QR session data, or private keys to application logs
- Automatic removal of temporary session data from memory after completion or expiration

## How Does It Work?

1. Enter a valid primary token for an account you own or are explicitly authorized to manage.
2. The application validates the token and generates a short-lived QR code for the account.
3. Open the official LINE app on the new phone.
4. Select **Log in > Log in with QR code > Scan QR code**.
5. Scan the QR code displayed by the application.
6. Complete the phone verification to finish signing in or transferring the account.

QR sessions are short-lived. If a session expires, generate a new QR code. A successful transfer may sign out the previous primary device.

## Security and Responsible Use

- Never share your primary token with anyone.
- Use the software only with accounts you own or are explicitly authorized to manage.
- The application is designed to run locally on the user's computer.
- The primary token is not written to disk or application logs; it is held in memory only while needed.
- QR session data is removed after the operation is completed or expires.
- This project is not an official LINE Corporation product and is not affiliated with, endorsed by, or supported by LINE.

## Sales and Licensing

The source code and software license are available for purchase. Contact us on WhatsApp for pricing, licensing terms, installation, and technical support.

**WhatsApp:** [0546 805 65 12](https://wa.me/905468056512)

## Source Code

The source code is not published in this repository. This repository provides a high-level overview of the product, its capabilities, and its workflow.

## Legal Notice

The buyer and user are responsible for complying with the applicable service terms, laws, regulations, and the account owner's explicit authorization.

