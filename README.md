# Volley for macOS

Select their message. Press **⌥ Option + R**. Get your reply, in your voice, pasted right where your cursor was. Works in WhatsApp, Slack, LinkedIn, Gmail and any other app.

**[getvolley.vercel.app](https://getvolley.vercel.app)** · **[Download the latest Volley.dmg](https://github.com/harsimran-preet/volley-releases/releases/latest/download/Volley.dmg)** · macOS 13 or later · Apple Silicon and Intel

## Install

1. Open `Volley.dmg` and drag Volley into Applications.
2. Open Volley. This early build isn't notarized by Apple yet, so the first time macOS blocks it: go to **System Settings → Privacy & Security** and click **Open Anyway**.
3. Allow **Accessibility** when the setup window asks. Volley needs it to read your selection and paste the reply.
4. Add an API key from [Anthropic](https://console.anthropic.com/), [Google AI Studio](https://aistudio.google.com/apikey) or [OpenAI](https://platform.openai.com/api-keys).

### Optional permissions

Volley works with Accessibility alone. Two features ask for more, and only when you turn them on:

- **Calendars**, for *Calendar availability* (Settings → Voice, off by default). Volley reads only the start and end times of your busy events for the next few days, so a reply can suggest a time that works. Event titles, attendees and notes are never read.
- **Full Disk Access**, for importing your iMessage history (Settings → Memory → Import history), so replies sound like you from day one. The Messages database is opened read-only, and the imported text stays on your Mac. Importing a WhatsApp *Export chat* file needs no extra permission.

Volley updates itself: it checks this repository's latest release in the background and offers new versions from its menu-bar icon.

## What's here

This repository only hosts builds. Each [release](https://github.com/harsimran-preet/volley-releases/releases) has:

- `Volley.dmg`: the installer.
- `Volley_<version>_universal.dmg`: the same installer, versioned.
- `Volley.app.tar.gz`, `.sig` and `latest.json`: used by the in-app updater. You don't need these.

Release notes are on each release.
