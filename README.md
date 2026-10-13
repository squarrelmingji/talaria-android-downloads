# Talaria (Alpha) for Android — INTERNAL USE ONLY

Talaria combines T3 Code’s coding-agent workspace with Hermes bot integration for authorized Squarrel staff and internal testing. Independently maintained by Squarrel; these are not official T3 Tools or Hermes releases.

Hermes integration includes bot chats and side chats, profile creation/cloning, and panels for skills, identity, jobs and settings. Bot setup must be completed before first chat.

Hermes features require connected Talaria environment with separately installed and configured Hermes gateway. App includes integration UI, not Hermes runtime, preconfigured internal bots, provider credentials or chat history. Environment administrator configures Hermes; authorized staff connect through Settings → Connections using sign-in or pairing. Hermes owns bot configuration and history. Provider usage and tests can incur charges under connected account’s plan.

Current Hermes limits: bot Files/Terminal and bot rename/delete unavailable; memory and user entries view-only. Persistent model changes and adding provider keys supported only for default bot. Cloning copies supported settings, not credentials.

Android 8 or newer. Not distributed through Google Play. Experimental builds provided “as is”, without warranty. Bugs and incomplete features expected. No public support commitment.

Download latest APK from Releases. Install first GitHub build once; Android asks to allow installs from your browser. Then use Settings → About → Check for updates. No GitHub download token required. Updates use newest successfully published Talaria commit build. Android asks you to confirm every update.

Every APK is signed with Talaria’s release key. Updates install only over a Talaria app signed with that same key; never uninstall to update, or local app data is lost. Verify SHA-256 shown in release notes before installing manually.

Downloads are public. Internal-use designation names intended audience; it does not limit who can download files or replace license terms. Internal connections require authorized sign-in or pairing. Downloading APK grants no access to Squarrel accounts or data.

APK includes bundled app code and public connection settings, including public Firebase client configuration. That code can be inspected. Personal chat history, account credentials, signing keys and publishing tokens are not intended APK contents. Releases checked for known credential patterns; this check is not complete security audit.

Support: internal team channels only. Do not post secrets or private logs publicly.

Based on [T3 Code](https://github.com/pingdotgg/t3code), with Hermes integration. Original MIT license and copyright notice retained in [LICENSE](LICENSE). Included third-party licenses and notices apply. Internal-use notice does not replace those terms.
