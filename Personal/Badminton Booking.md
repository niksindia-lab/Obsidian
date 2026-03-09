# Badminton Booking System

## Location
Queen Elizabeth Park Community and Cultural Centre

## Session Times
- Monday: 7:30 PM - 9:30 PM
- Thursday: 7:30 PM - 9:30 PM

## Booking Details
- **Website**: https://townofoakville.perfectmind.com/24974/Clients/BookMe4?widgetId=acf798a6-9321-41b7-aa41-92cbb8c1b485
- **Login**: contact.poojamehta@gmail.com
- **Password**: Satnam12!
- **Payment**: Saved credit card ending in 8215

## Booking Rules
- Sessions open for booking **8 days before** the event date
- Booking opens exactly at the **session start time** (7:30 PM)
- Example: Monday session (Mar 16) opens for booking on Sunday (Mar 8) at 7:30 PM
- Slots fill up FAST (32 slots available)
- **No waiting list** for these sessions

## Process
1. Navigate to booking URL
2. Login with credentials
3. Go to Sports Drop-in
4. Search "badminton"
5. Filter location: Queen Elizabeth Park Community and Cultural Centre
6. Find Badminton - Adult session at 7:30 PM
7. Click Register
8. Pay with saved card (ending 8215)

## Cron Jobs
- `badminton-book-monday` - Triggers 7:30 PM Sunday (8 days before)
- `badminton-check-monday` - Monday morning check
- `badminton-nudge-monday` - Monday 7:15 PM reminder

## Day-of Confirmation
- Check with Nikhil on the day of the event
- If not attending: **CANCEL** the session to avoid losing money

## Optimization Notes
- Direct registration URL (skips browsing):
  ```
  /24974/Clients/BookMe4EventParticipants?eventId=e6831d08-1b92-2e9c-0513-4192874a420f&occurrenceDate=20260316&widgetId=...&locationId=...&waitListMode=False
  ```
- Need to be fast - slots fill within seconds

## Status
- ⚠️ Initial booking attempt failed (API rate limit / timeout issues)
- First test booking: Cancelled successfully

---