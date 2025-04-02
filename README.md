# chat_application
Easy Chat

Easy Chat is a real-time chatting application built using Android Studio and Java. This project is designed to provide seamless and secure communication between users, enabling them to chat with their friends and family. The application integrates Firebase for authentication, user management, and data storage.

Features

User Authentication: Login using a phone number and OTP verification.

OTP Verification: Secure authentication via Firebase OTP service.

User Profile Management: Users can set and update their profile pictures and usernames.

Real-Time Messaging: Chat with friends and family instantly.

Firebase Integration: Stores user data and chat messages securely.

Logout Functionality: Users can log out and re-authenticate if needed.

Project Overview

This is a Mega Project for Android development, aimed at providing a simple yet effective chat application.

Authentication Process

Login with Phone Number: Users enter their phone number to receive an OTP.

OTP Verification:

If OTP is correct → Displays "OTP Verification Successful" and logs in the user.

If OTP is incorrect → Displays "Verification Failed" message.

Firebase Integration:

Stores verified phone numbers in Firebase.

Adds users to Firebase after successful login.

Profile Management

Users can upload a profile picture.

Users can update their username.

Users can logout anytime and re-login when needed.

Technologies Used

Java (Primary language for development)

Android Studio (IDE for development)

Firebase Authentication (For user login & OTP verification)

Firebase Firestore (For storing user data)

Firebase Storage (For profile pictures and media files)
