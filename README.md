# Shared Recipe Box

A lightweight iPhone-friendly PWA for saving recipes from TikTok, Instagram and websites. The front end is hosted on GitHub Pages. Recipe data is stored in Firebase Cloud Firestore and synchronises live between phones.

## Features
- Real-time shared library across phones
- Quick-save incoming links to an Inbox
- TikTok / Instagram / website source detection
- Search, categories and tags
- Favourites and Tried status
- Ingredients, method and notes
- Duplicate-link warning
- JSON backup
- Installable on iPhone Home Screen
- No in-app account/login

## Setup
Open the app after GitHub Pages is enabled, create a free Firebase project/Firestore database, paste the supplied Firestore rules, then paste Firebase's web app configuration into Recipe Box.

The second phone joins from Recipe Box > More > Share with another phone.

Access is based on the shared household library link, so don't use this app for sensitive information.