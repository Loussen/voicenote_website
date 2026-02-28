# VoiceNote website

Simple static site for the VoiceNote app: landing page, Privacy Policy, Terms & Conditions, and Disclaimer (suitable for App Store / Play Store requirements).

## Contents

- **index.html** – Home / app overview
- **privacy.html** – Privacy Policy
- **terms.html** – Terms & Conditions
- **disclaimer.html** – Disclaimer
- **css/style.css** – Shared styles (app-aligned red theme)

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
cd website
python3 -m http.server 8080
# Then open http://localhost:8080
```

## Deploy

Upload the `website` folder to any static host (e.g. GitHub Pages, Netlify, Vercel, or your domain). Then set the app URLs:

- In **home_screen.dart**: update `_privacyPolicyUrl`, `_termsUrl`, `_disclaimerUrl` with your live URLs (e.g. `https://yoursite.com/privacy.html`).

## Customize

- Replace `support@voicenote.app` with your support email in privacy.html and terms.html.
- Adjust "Last updated" dates when you change the documents.
- Edit text as needed for your app name and policies.
