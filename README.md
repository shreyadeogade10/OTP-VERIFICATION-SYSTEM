# OTP-VERIFICATION-SYSTEM

This repository contains a Python-based OTP (One-Time Password) Verification System designed to enhance security for user authentication. The project generates a 6-digit OTP, sends it via email to the user, and then verifies the entered OTP within a specified time frame.

**Key Features**:
**OTP Generation**: A secure 6-digit OTP is generated using Python's built-in libraries.
**Email Integration**: The OTP is sent directly to the user's email using SMTP for secure communication.
**GUI Interface**: A user-friendly graphical interface that allows users to input their email and verify the OTP (developed using a Python framework other than Tkinter).
**Validation**: The system checks the entered OTP against the generated one and provides feedback on successful or failed verification.
**Timeout Feature**: Includes an optional timeout feature that invalidates the OTP after a certain period, adding an extra layer of security.
**Technologies Used**:
Python (Core logic and OTP generation)
SMTP Library (Email delivery)
GUI Framework (for user interface)
Random and Time libraries (for OTP generation and timeout)
Project Structure:
otp_verification.py: The main script that handles OTP generation, email sending, and verification.
gui.py: The script that manages the graphical user interface for OTP input and feedback.
README.md: Detailed documentation on how to set up and run the project.
How to Use:
Clone the repository and install required dependencies.
Run the application, input your email, and wait for the OTP to be sent.
Enter the received OTP within the GUI to complete the verification process.
