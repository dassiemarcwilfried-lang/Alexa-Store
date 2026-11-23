ALEXA STORE V9 - COOKIE CONSENT NOTES

The visitor-facing pages now include:
- Accept All
- Reject Optional
- Manage Preferences
- Essential storage (always active)
- Optional Analytics and Advertising choices
- A Cookie Settings footer link on each visitor-facing page
- Saved choices in localStorage

No advertising or analytics provider scripts have been added. The consent manager exposes:
  window.AlexaConsent.hasConsent("analytics")
  window.AlexaConsent.hasConsent("advertising")
  window.AlexaConsent.getChoice()
  window.AlexaConsent.openSettings()

Future optional scripts must check the relevant consent before loading or running.

IMPORTANT:
This is a basic on-site consent interface, not a certified Google CMP. Before enabling Google AdSense personalized ads for visitors in the EEA, UK, or Switzerland, configure a Google-certified CMP / Google Privacy & Messaging solution as required by Google. Have the responsible adult/publisher account manager review the privacy policy and advertising setup before launch.
