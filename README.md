# NALAM — Women's Safety & Digital Support

An Android-first Expo MVP for the recHERsion'26 Women’s Safety hackathon.

## Features
- Privacy exposure checker for user-entered text (email, phone-like numbers, PIN/ID clues).
- Incident creation and local timeline.
- SHA-256 fingerprint of each incident record (integrity indicator only).
- PDF incident report export and native share sheet.
- English/Tamil interface toggle and support guidance.
- Delete individual records or clear all local records.

## Run on Windows
1. Install Node.js LTS and Expo Go on your Android phone.
2. Extract the ZIP and open PowerShell in this folder.
3. Run `npm install`
4. Run `npx expo start`
5. Scan the QR code in Expo Go. Keep phone and laptop on the same Wi-Fi.
6. If network discovery fails, try `npx expo start --tunnel`.

## Prototype limits
No GPS tracking, background monitoring, SMS alerts, cloud sync, police integration, or automatic violence prediction. Privacy checks are simple patterns and may miss information. AsyncStorage is not encrypted secure storage; use fictional demo data only. A hash does not prove authorship, truth, authenticity, or legal admissibility. The Tamil copy should be reviewed by a fluent speaker.
