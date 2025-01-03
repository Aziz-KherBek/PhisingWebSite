# Documentation

This is a simple HTML and CSS website designed for testing phishing scenarios. 

## Overview

The website includes a form where users can input their email address and password. Upon submission, the form sends the entered information to a webhook URL. This webhook captures and stores the data for retrieval. 

## Key Features

1. **User Form**: 
   - The form includes fields for an email address and a password.
   - The form's `action` attribute is configured to send the submitted data to a webhook URL.

2. **Webhook Integration**: 
   - The webhook URL receives the submitted data.
   - The URL must be updated periodically due to its limited validity.

3. **Hosting**: 
   - The website is hosted on GitHub Pages for accessibility and testing.

## Notes

- **Webhook URL**: Since the webhook URL is temporary and expires after a set duration, it needs to be updated regularly for continued functionality.
- **Security Warning**: This setup is for educational purposes only. Capturing user credentials without their explicit consent is unethical and potentially illegal.

## WebSite 
![My Example Image] (/Screenshot 2025-01-03 095219.png)
