# UPI QR Code Generator (Web) 💳

A single-page web app that generates a UPI payment QR code from any UPI ID,
right in the browser. No installation or backend needed.

## How it works
1. Enter a UPI ID (for example `name@okhdfcbank`)
2. Click **Generate QR**
3. The app builds a `upi://pay` link and renders it as a QR code you can scan
   with any UPI app (PhonePe, Google Pay, Paytm, etc.)

## Tech
- HTML, CSS, vanilla JavaScript
- [qrcode.js](https://cdnjs.com/libraries/qrcodejs) loaded from a CDN

## How to run
Open `index.html` in any browser. That's it.
