# Lisa_running

Simple web page to organize a jogging/running group with:
- Runner voting poll for preferred track and time
- Admin controls for managing available tracks and time slots
- Persistent poll data in browser localStorage

## Usage
Open `index.html` in a browser.

When the page is used for the first time in a browser, the first non-empty admin code entered will become that browser's admin code (saved in localStorage).
You can reset the stored admin code from the **Reset admin code** button in the profile section (enter the current admin code first).

> This is a client-side demo page, not production-grade authentication.
