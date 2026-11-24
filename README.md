# SPYWORK

SPYWORK is a first-person spy shooter for macOS. It has six maps (an embassy at night, a rain-soaked freight yard, a container port, a casino, an alpine old town and a bank) and a six-episode story. It also has arena modes against bots, split screen, and **online play with friends**.

- **Rating:** about PG-13. It has gunfire and combat violence, with blood decals.
- **Platform:** Mac only, macOS 11 or later, Apple Silicon or Intel (one universal app).
- **Price:** free. This repository holds only the download.

## Download

**[SPYWORK-mac.zip](https://github.com/ResultantAI/spywork-releases/releases/latest/download/SPYWORK-mac.zip)** (always the latest release)

Unzip it (double-click), then drag **SPYWORK.app** to Applications or anywhere you like.

## Opening it the first time

The app is not notarized by Apple, so macOS stops it the first time:

1. Double-click **SPYWORK**. macOS says it "could not verify" the app. Click **Done**, not Move to Trash.
2. Open **System Settings**, then **Privacy & Security**.
3. Scroll down to the Security section. You will see *"SPYWORK" was blocked to protect your Mac.* Click **Open Anyway**.
4. Confirm with your password or Touch ID, then click **Open Anyway** again in the dialog that follows.

From then on it opens normally.

You may also see:
- **"SPYWORK would like to find and connect to devices on your local network"** when you host or join. Click **Allow**: hosting uses it to ask your router to open a port, and same-network (LAN) codes need it.
- **"Do you want the application SPYWORK.app to accept incoming network connections?"** when you host, if the macOS firewall is on. Click **Allow**.

The game starts full screen. F11 switches to a window and back.

**The first launch is slow.** On a Mac's first launch the game prepares its graphics (it compiles its shaders), and the title says so. The screen can sit still for a minute or two before the main menu appears, and again when you load your first map. Leave it running. Later launches are quick.

## Playing online

Everyone needs the **same version**. If the versions differ, the game says so and names both.

### Host

1. From the main menu, choose **ONLINE**, then **HOST**.
2. Pick the mode (Free For All, Teams, Co-op vs bots, Standoff or Last Light), the map, the bots and their difficulty, and how many players (2 to 8). Choose **OPEN LOBBY**.
3. The lobby shows a **join code**. Use **COPY CODE** and send it to your friends.
   - **INTERNET**: your router opened the game's port by itself (UPnP). The code is 12 characters, like `ABCD-EFGH-JKLM`.
   - **RELAY**: your router would not open a port, or your internet provider shares your address with others (carrier-grade NAT). The match goes through a free public relay instead. The code is 28 characters long, so send it as text and your friends can paste it.
   - **SAME NETWORK (LAN)**: a second code for players on your own Wi-Fi.
4. When everyone is listed, press **START**.

If you leave, the match ends for everyone. If a friend drops out, a bot takes their place.

### Join

1. From the main menu, choose **ONLINE**, then **JOIN**.
2. Type the host's code with the keyboard or the controller, or press **PASTE** (or Cmd+V). The code has a built-in check, so a typo is caught before the game tries to connect.
3. You wait in the lobby until the host presses START.

Your name online is your callsign from **OPERATIVE**: letters and digits, up to 12 characters.

## Controls

Keyboard and mouse or a game controller. **SETTINGS** lists every binding and lets you change them.

## Privacy

- **Host:** asks your router to open a port (UPnP), and asks a public STUN server (Google's or Cloudflare's) for your public address.
- **Relay:** when it is used, game traffic goes through the noray relay at `foxssake.studio`, run by the author of the open-source netfox project.
- **No accounts and no tracking.** The game does no analytics and has no chat.

## Credits

The game's own content is original. Textures, sky and furniture are CC0. Characters and animations are from Mixamo. Some models are from Sketchfab under CC0 or CC BY 4.0, and every author is listed in the game's **CREDITS** screen. Made with Godot Engine (MIT).
