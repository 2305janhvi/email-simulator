# Email-simulator
Email Simulator (Python)
A lightweight, terminal-based Email System Simulator built using Python. This project demonstrates core Object-Oriented Programming (OOP) concepts, including class composition, encapsulation, and inter-object communication.

🌟 Key Features
Three-Tier Architecture: Uses Email, Inbox, and User classes to manage data flow.

Real-time Timestamps: Automatically logs the date and time for every email sent using the datetime module.

Inbox Management:

List: View a numbered summary of emails.

Read: View full body content (automatically marks the email as "Read").

Delete: Remove specific emails from the inbox by their index.

Formatted Output: Clean console headers and separation lines for better readability.

Example Output:

The main() function demonstrates a typical flow between two users, Tory and Ramy:
Email sent from Tory to Ramy!
Email sent from Ramy to Tory!

Ramy's Inbox:
Your Emails:
1. [Unread] From: Tory | Subject: Hello | Time: 2026-03-01 17:15

--- Email ---
From: Tory
To: Ramy
Subject: Hello
Received: 2026-03-01 17:15
Body: Hi Ramy, just saying hello!
------------

Email deleted.
