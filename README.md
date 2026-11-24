# SPYWORK

**For parents:** SPYWORK is a spy thriller shooter for the Mac, rated about PG-13 (gunfire and combat violence, with blood decals). It has no text chat and no voice chat. Friends play together only by sharing a code. It was made by Chris.

- **Platform:** Mac only, macOS 11 or later, Apple Silicon or Intel (one universal app).
- **Price:** free. This repository holds only the download.
- **What's in it:** six maps, a six-episode story, arena modes against bots, split screen, and online play with friends.

## Download

**[Download SPYWORK for Mac](https://github.com/ResultantAI/spywork-releases/releases/latest/download/SPYWORK-mac.zip)** (SPYWORK-mac.zip, about 1.1 GB, always the latest release)

## Grown-up needed once

The app is not notarized by Apple, so the first time takes a grown-up and the Mac's password:

1. **Unzip** SPYWORK-mac.zip (double-click it). You can drag **SPYWORK.app** to Applications.
2. **Open SPYWORK.** macOS says it "could not verify" the app. Click **Done** (not Move to Trash).
3. Open **System Settings**, then **Privacy & Security**. Scroll down to *"SPYWORK" was blocked to protect your Mac* and click **Open Anyway**. The Mac asks for its password (or Touch ID); then click **Open Anyway** once more.
4. If the Mac asks whether SPYWORK can **find devices on your local network**, click **Allow**. If it asks to **accept incoming network connections**, click **Allow** too.

From then on SPYWORK opens like any other app.

**The very first launch is slow.** The game prepares its graphics for this Mac: the main menu takes about half a minute, and the first map you load can sit still for several minutes. Leave it running; it only happens once.

## How to play with a friend

Both of you need the same version of SPYWORK. If the versions differ, the game says so.

**Host**
1. Choose **ONLINE**, then **HOST**.
2. Pick a mode (and a map if you like), then **OPEN LOBBY**.
3. Tell your friend the code on the screen, or press **COPY CODE** and text it. When they're in, press **START**.

**Join**
1. Choose **ONLINE**, then **JOIN**.
2. Type the code (or **PASTE** it, Cmd+V). A typo is caught before the game tries to connect.

The code goes through a free public relay, so it never contains your home's internet address. If the host leaves, the match ends; if a friend drops out, a bot takes their place.

Online names are the callsign from **OPERATIVE**: letters and digits, up to 12. A rude name is swapped for AGENT and two digits.

**For grown-ups:** the lobby's **ADVANCED** item (closed by default) has other ways to connect: a code made by your router (UPnP), a same-network (LAN) code and port-forwarding steps. Those codes contain your public or home address, so share them only with people you know.

## Controls

An Xbox controller, or keyboard and mouse. **SETTINGS** lists every binding and lets you change them.

## Privacy

- **No accounts, no tracking, no chat.** The game does no analytics.
- **Relay:** online games go through the noray relay at `foxssake.studio`, run by the author of the open-source netfox project.
- **Hosting** also asks your router to open a port (UPnP) and asks a public STUN server (Google's or Cloudflare's) for your public address; those are used only for the ADVANCED codes.

## Credits

The game's own content is original. Textures, sky and furniture are CC0. Characters and animations are from Mixamo. Some models are from Sketchfab under CC0 or CC BY 4.0, and every author is listed in the game's **CREDITS** screen. Made with Godot Engine (MIT).
