# Voice Based Email Writing
A Python-based voice assistant that allows users to send  emails through voice commands. This project integrates speech recognition, email handling, and text-to-speech functionalities to create a seamless experience for emails using natural language.

# Features:
- Send Emails via Voice Command: Users can dictate the recipient, subject, and message body.
- Voice Confirmation: Confirms email details before sending.
- Error Handling: Handles invalid email addresses or no internet connection.
# Tech Stack:
- Python: Core language for backend logic.
- SpeechRecognition: To convert voice commands into text.
- pyttsx3: For text-to-speech functionality, allowing the assistant to speak back to the user.
- smtplib: To handle sending emails via SMTP.
- imaplib: For retrieving and reading emails from the inbox.
- Email and MIME libraries: To format and send HTML/text emails.
- Google API (Optional): Can be integrated for Gmail accounts using OAuth 2.0 for better security.
