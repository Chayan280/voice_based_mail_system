# Voice Based Mail System
## Project Overview

A voice-controlled email automation system built in Python that allows users to compose, send, and check emails using voice commands only.
This project integrates speech recognition, text-to-speech, and email APIs to offer a fully interactive, hands-free mailing experience.
## Key Features
✔ Voice-Based Controls
Speak your choice (Compose / Check Inbox)
Speak your message to automatically send it as an email

✔ Text-to-Speech (TTS) Feedback
System reads out:
Options
Choices
Total emails
Unseen (unread) emails
Sender name
Email subject
Email body

✔ Email Sending Support
Sends email via Gmail SMTP
Uses your voice message as the email body

✔ Inbox Reader (IMAP)
Fetch total emails
Fetch unread emails
Read latest email details:
Sender
Subject
Body (extracted using BeautifulSoup)

## Technologies Used
Technology	Purpose
Python	Main programming language
SpeechRecognition	Convert user’s speech to text
gTTS (Google Text-to-Speech)	Convert text to voice
Pyglet	Play TTS audio
Smtplib	Send mail
Imaplib	Read inbox
BeautifulSoup	Extract readable text from email body

## How It Works
1. System greets user with voice prompts
It plays pre-recorded TTS prompts:
"Option 1: Compose a Mail"
"Option 2: Check your inbox"
"Your choice"

## Setup & Installation

Install packages:
pip install -r requirements.txt

Modify sender and receiver email in code
mail.login("youremail@gmail.com","your-app-password")
mail.sendmail("youremail@gmail.com","receiver@gmail.com",msg)

## Conclusion

This Voice-Based Email System demonstrates how powerful Python can be when combining:
Speech recognition
Email automation

It provides a hands-free communication tool, ideal for:
Visually impaired users
Smart assistants
Automation projects
IoT voice interfaces


