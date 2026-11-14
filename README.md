# Fitlife

A responsive, phone-friendly fitness app prototype based on the supplied Figma screens.

## Run it

Open `index.html` in a browser for a quick preview. For the best installable mobile experience, serve this folder over HTTPS or localhost with a static web server. For example, with Node.js installed:

```sh
npx serve .
```

Open the shown local URL on your phone, or open that same URL from a phone on the same Wi-Fi using your computer's local network address. To install, use **Add to Home Screen** in the mobile browser.

## Included

- Mobile-first onboarding, profile setup, and selectable fitness goals
- Daily dashboard, guided workout routines with timed exercise instructions, and activity history
- Local device storage so profile and workout progress survive refreshes
- Web app manifest and app icon for an installable PWA shell

## Current scope

This is a working front-end prototype. Sign-up does not create a server account, and steps, calories, water, and workouts are local sample/manual data; live wearable tracking and account sync need a backend and mobile health integrations. HTTPS is needed for PWA installation and other device APIs.
