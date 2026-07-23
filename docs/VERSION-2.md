# Version 2 - Membership Renewal Reminder

## Problem

The gym owner manually remembers membership expiry dates.

## Solution

Automatically check all memberships every morning.

If a membership expires within 3 days:

- Notify the gym owner
- (Future) Send WhatsApp reminder to the member

## Workflow

Schedule Trigger (9:00 AM)
↓
Read Google Sheet
↓
Check Expiry Dates
↓
Filter Members Expiring in 3 Days
↓
Send Notification

## Status

🚧 In Development
