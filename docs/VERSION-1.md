# Version 1 - Automatic Membership Expiry Calculation

## Objective

Automatically calculate the expiry date whenever a new member registers.

## Workflow

1. Gym owner submits the Google Form.
2. Response is saved to Google Sheets.
3. Google Sheets Trigger starts the workflow.
4. JavaScript calculates the expiry date based on the membership plan.
5. The workflow updates the Google Sheet with the calculated expiry date.

## Tech Stack

- Google Forms
- Google Sheets
- n8n
- JavaScript

## Status

✅ Completed

## Future Improvements

- WhatsApp renewal reminders
- Automatic Member ID generation
- Membership dashboard
- Payment tracking
