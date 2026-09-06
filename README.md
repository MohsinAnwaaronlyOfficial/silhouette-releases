# Silhouette — Channel operations for faceless creators

Silhouette is a Windows desktop app for people who run faceless YouTube channels. It keeps every channel's browser profile looking like a real viewer (human-pattern warm-up), replies to the comments on your own videos (AI-drafted, quality-checked, posted from YouTube Studio), and watches profile, proxy and login health so you only look when something needs you. Everything runs on your own PC on top of IXBrowser.

## Download

Get the latest `Silhouette-<version>-win64.zip` from the **Releases** page of this repository (right-hand side).

## Install — 2 minutes

1. Unzip the file anywhere you have write access, for example `C:\Silhouette` (not Program Files).
2. Run `Silhouette.exe`. Windows SmartScreen may warn on first launch (unsigned beta build): **More info → Run anyway**.
3. **License** page → paste the key you received → **Activate**. The key locks itself to this PC; there is nothing else to send us.
4. **Settings** → add your own LLM API keys (Gemini free tier is enough; OpenAI / Groq are optional fallbacks).
5. **Settings → Slack Integration** → **Connect Slack** → pick your workspace → **Allow**. Alert channels are created for you.
6. **Channels** → **Sync with IXBrowser** → link each profile to a channel and a niche → **Scheduler → Start**.

Node.js is bundled — nothing else to install. IXBrowser must be installed and signed in on the same PC.

## Requirements

Windows 10/11 (64-bit) · IXBrowser · internet access for license checks and updates.

## License keys

One key activates one PC. Moving to a new PC: **License → Move to another PC**, then activate the same key there. If you kept "Keep Slack linked to my license" on, Slack reconnects by itself on the new PC.

Free trial keys (7–30 days) are available on request. Payment: Easypaisa, JazzCash or UBL bank transfer — send the transaction ID and your key is issued within a few hours.

**Support:** WhatsApp +1 (571) 615-2713 · mohsinanwaarllc@gmail.com

## Privacy

Accounts, cookies, keys and browser sessions never leave your PC. The app sends anonymous usage counts and crash reports so we can improve it — never channel names, keys, emails or your PC identity. Switch it off any time in Settings.

## Updates

The app checks for updates daily and from **Check for updates** on the front page. Updates are signed; the app only installs a release published here.

## Changelog

**3.1.6** — health report explains short warm-ups (planned vs actual, videos, sign-in state) and empty Studio inboxes.

**3.1.5** — remote health report (what works / what's missing) so support can help before you notice · never includes keys or personal data.

**3.1.4** — your keys/settings/niches can never be overwritten by an older backup · Slack connect certificate fix for Windows Server · edits are backed up immediately.

**3.1.3** — fresh-install fixes: 'Sync with IXBrowser now' on the Scheduler page · Connect Slack no longer fails when the browser is slow to open ('Copy link' fallback).

**3.1.2** — your Slack channels are named after you (License page → 'Your name or agency name', e.g. Killer YT → #killer-yt-warmup) · rename them any time from Settings · reconnecting on a new PC keeps your existing channels.

**3.1.1** — in-app updates fixed (Restart now installs and relaunches) · your whole setup is backed up to your license and restored on a new PC · Back up now / Restore buttons in Settings.

**3.1.0** — one-click Slack connect with automatic restore on a new PC · smooth scrolling everywhere · Channels page shows your saved channels even when IXBrowser is closed · Demo Mode now covers every page · faster Diagnostics · cleaner License page and About.

**3.0.0** — first public build: licensing, signed updates, anonymous usage statistics, bundled Node.js.

Made by Unity Media Flow (UMF).
