# AI-Lead-Machine-Agent

Who this is for
This workflow is for digital marketing agencies or sales teams who want to automatically find business leads based on industry & location, gather their contact details, and send personalized cold emails — all from one form submission.

What this workflow does
This workflow starts every time someone submits the Lead Machine Form. It then:

Scrapes business data (company name, website, phone, address, category) using Apify based on business type & location.
Extracts the best email address from each business website using Google Gemini AI.
Stores valid leads in Google Sheets.
Generates cold email content (subject + body) with AI based on your preferred tone (Friendly, Professional, Simple).
Sends the cold email via Gmail.
Updates the sheet with send status & timestamp.
Setup
To set this workflow up:

Form Trigger – Customize the “Lead Machine” form fields if needed (Business Type, Location, Lead Number, Email Style).
Apify API – Add your Apify Actor Endpoint URL in the HTTP Request node.
Google Gemini – Add credentials for extracting email addresses.
Google Sheets – Connect your sheet for storing leads & email status.
OpenAI – Add your credentials for cold email generation.
Gmail – Connect your Gmail account for sending cold emails.
How to customize this workflow to your needs
Change the AI email prompt to reflect your brand’s voice and offer.
Add filters to only target leads that meet specific criteria (e.g., website must exist, email must be verified).
Modify the Google Sheets structure to track extra info like “Follow-up Date” or “Lead Source”.
Switch Gmail to another email provider if preferred.
