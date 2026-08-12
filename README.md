# Notcheur — Support

Bug reports, questions and feature requests for **Notcheur**, a notch utility for macOS.

This repository holds no source code — it exists so you can reach us.

## Get help

**[→ Open an issue](../../issues/new/choose)**

Before filing a bug, it helps to include:

- Your macOS version (Apple menu ▸ About This Mac)
- Your Notcheur version (menu bar icon ▸ Settings)
- What you expected, and what happened instead

## Common questions

**Notcheur doesn't seem to open.**
It has no Dock icon and no window by design. Rest the pointer on the notch for about a
quarter second — a quick pass won't trigger it. There's also a Notcheur icon in the menu
bar with an "Open Notcheur" item. You can change the hover delay in Settings ▸ Notch.

**Zen doesn't turn on a Focus.**
macOS has no API for setting a Focus, so Notcheur runs a Shortcut you create yourself.
Make two shortcuts in the Shortcuts app named exactly **Notcheur Zen On** and
**Notcheur Zen Off**, each with a *Set Focus* action. Zen's setup hint links straight to
Shortcuts.

**Now Playing shows nothing while music is playing.**
Notcheur supports **Apple Music** and **Spotify**. It can't read audio from browsers —
Apple restricts system-wide now-playing to its own apps. You'll also be asked for
Automation permission the first time; if you declined it, re-enable Notcheur under
System Settings ▸ Privacy & Security ▸ Automation.

**My notes aren't syncing between Macs.**
Notes sync through your own iCloud. Check you're signed in to the same Apple Account on
both Macs and that iCloud Drive is on. Notcheur has no servers of its own.

**How do I cancel a subscription?**
System Settings ▸ your name ▸ Media & Purchases ▸ Subscriptions, or
[apps.apple.com/account/subscriptions](https://apps.apple.com/account/subscriptions).

## Privacy

Notcheur collects nothing. No accounts, no analytics, no servers.
See the [privacy policy](https://bigcheese1989.github.io/Notcher/site/privacy.html).
