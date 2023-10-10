# Generate and Validate OTP

## Introduction

This web application is designed to help you generate and validate OTP (One-Time Password) for authentication. It consists of two main components:

1. **Client** - Frontend using React:

   - This is the user interface where you can interact with the application.
   - You will use this part to register, receive OTP on your email, and validate it before logging in.

2. **Server** - Backend using Spring Boot:
   - This is the server-side component responsible for handling registration, generating OTP, sending it to your email, and validating it.
   - It manages the authentication process and ensures secure access to the application.

## How It Works

### Registration

1. When you sign up for the application, you will provide your details.
2. The server will generate a unique OTP (One-Time Password) for you.
3. This OTP will be sent to your registered email address for verification.

### OTP Verification

1. Check your email for the OTP sent by the application.
2. Enter this OTP in the provided space on the client (frontend) to validate your email.
3. Once validated, you can proceed to log in to the application.

### Login

1. After successful OTP verification, you can log in using your credentials.
2. This ensures that only authorized users gain access to the application.

This web application is primarily designed to enhance security by adding an extra layer of authentication through OTP. It provides a secure way to verify your identity before granting access.

Please refer to the respective client and server directories for more details on how to run and use this application.
