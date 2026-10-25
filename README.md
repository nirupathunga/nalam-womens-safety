# NALAM — Privacy-First Women's Safety Platform

**Beyond Emergency Alerts. Towards Privacy, Preparedness, and Empowerment.**

NALAM is a women’s safety mobile application prototype developed for **recHERsion’26**. It focuses on an often-overlooked aspect of personal safety: protecting sensitive information and helping users document incidents in an organised, accessible manner.

Rather than relying solely on conventional SOS and location-tracking approaches, NALAM brings together privacy exposure awareness, incident documentation, integrity fingerprints, and shareable reports in one application.

## The Problem

Women's safety solutions often focus on emergency response, while privacy risks and the difficulty of maintaining organised incident records may receive less attention.

Users may need a simple way to recognise potentially exposed personal information, document incidents, and prepare structured reports without navigating multiple tools.

## Our Solution

NALAM provides a privacy-focused, bilingual mobile experience designed around three principles:

- **Privacy Awareness:** Identify potentially sensitive information patterns before sharing text.
- **Incident Documentation:** Organise incident details in a timeline and generate a report.
- **Accessible Support:** Provide safety resources through an interface designed for English and Tamil users.

## Key Features

### 1. Privacy Exposure Checker
Scans user-entered text for patterns that may indicate exposed personal information, helping users review content before sharing it.

### 2. Incident Timeline
Allows users to record incident details in an organised format for easier review.

### 3. SHA-256 Integrity Fingerprint
Generates a cryptographic hash of incident content. This can help identify changes to the content but does not independently establish the truth, origin, or legal authenticity of an incident.

### 4. PDF Incident Reports
Enables users to export incident information into a shareable PDF format.

### 5. English and Tamil Support
Makes the prototype accessible to users who prefer either language.

### 6. Safety Resource Access
Provides information about emergency and cybercrime reporting resources relevant to India.

## What Makes NALAM Different?

NALAM combines privacy awareness and structured incident documentation in a single mobile experience. Its focus extends beyond emergency alerts to the preparation and organisation of information that users may need when seeking support.

The prototype prioritises a practical, understandable workflow instead of making unverified claims about automatic emergency response or predictive safety.

## Technology Stack

- **Mobile Framework:** React Native
- **Development Platform:** Expo
- **Programming Language:** TypeScript
- **Local Data Storage:** AsyncStorage
- **PDF Generation:** Expo Print
- **Report Sharing:** Expo Sharing
- **Integrity Checking:** SHA-256 hashing

## Getting Started

### Prerequisites

- Node.js and npm
- A compatible Expo Go installation or Android emulator
- Git (optional)

### Installation

Clone or download this repository and open a terminal in the project directory.

```bash
npm install
npx expo start
```

Scan the displayed QR code using a compatible Expo Go application, or launch the project in a configured Android emulator.

**Compatibility:** This project was prepared for Expo SDK 54. Ensure your Expo Go version and project dependencies are compatible before running it.

## Demonstration Workflow

1. Launch NALAM.
2. Explore the privacy exposure checker using fictional sample text.
3. Create a sample incident record.
4. Review its integrity fingerprint.
5. Export the incident report as a PDF.
6. Explore the English and Tamil interface and available safety resources.

Use fictional data during demonstrations. Verify each feature on the target device before presenting it as functional.

## Privacy, Safety and Limitations

NALAM is a hackathon prototype and is not a replacement for emergency services or professional assistance.

- AsyncStorage does not provide the same protection as dedicated encrypted secure storage.
- The privacy checker identifies patterns and may produce false positives or miss sensitive information.
- A SHA-256 hash does not prove that an incident occurred or guarantee legal admissibility.
- The prototype does not claim automatic police dispatch, continuous background tracking, or live emergency monitoring.
- Users should avoid storing unnecessary sensitive information in the prototype.

In India, call **112** for emergency assistance when appropriate. For cybercrime reporting, visit the official portal: https://cybercrime.gov.in/

## Social Impact

NALAM aims to make privacy awareness and incident documentation more accessible through a simple, bilingual mobile experience. By bringing these capabilities together, the project explores how technology can support preparedness, informed decisions, and access to help.

## Future Scope

Potential future improvements include encrypted local storage, stronger authentication, consent-based trusted-contact sharing, secure backups, accessibility enhancements, and evaluation with women's safety organisations.

These are proposed improvements, not claims about the current prototype.

## Team

**recHERsion’26 Hackathon**

- **Nirupathunga M**
- **Pavithra M**

## Project Status

Hackathon prototype developed to explore privacy-first approaches to women's safety.

