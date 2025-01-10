# Create-Auto-Password-With-Email-Spring-Boot

# Auto-Password Generator with Email Notification - Spring Boot

This is a Spring Boot application that generates a random password for a user and sends it to their email address. The password is generated using a secure random string generator, and it is sent via email using JavaMailSender.

## Features

- Generate a secure, random password.
- Send the generated password to a user's email address.
- Customizable password length and character set.
- REST API for generating passwords and sending email.

## Requirements

- Java 17 (or higher)
- Spring Boot 2.x
- A mail server (SMTP) to send emails (e.g., Gmail, SendGrid, etc.)
- Maven for dependency management

## Technologies Used

- Spring Boot
- JavaMailSender (for sending emails)
- SecureRandom (for password generation)

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Auto-Password-Generator.git
cd Auto-Password-Generator
