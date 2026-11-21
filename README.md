# PostDeck releases

PostDeck is made by Cribian.

This repo holds the PostDeck installers for Windows. The source code is not in this repo.

## Install

1. Open the [latest release](https://github.com/Cribian122/postdeck-releases/releases/latest).
2. Download `PostDeck-Setup-<version>.exe`.
3. Run the file.

The installer has no code signature yet, so Windows and your browser do not know the publisher. Expect the warnings in the table.

| Warning | What to do |
|---|---|
| The browser says the file "isn't commonly downloaded" | Click **Keep** (Edge: open the **...** menu next to the file). |
| "Windows protected your PC" | Click **More info**, then **Run anyway**. |

## System requirements

| Part | Minimum | Tested on |
|---|---|---|
| Windows | Windows 10 or 11, 64-bit | Windows 11 Home |
| CPU | 64-bit Intel or AMD | Intel Core i9-14900K |
| Memory | 8 GB (the OpenShorts figure) | 32 GB |
| Graphics card | Optional. See the next table. | NVIDIA GeForce RTX 5070 Ti, 16 GB, driver 617.42 |
| Disk space | About 390 MB for PostDeck. Studio setup needs 5 GB free without an NVIDIA card, 12 GB free with one. | |
| OBS | OBS Studio 28 or newer, for live clips and auto-clips | |
| Internet | For the Studio setup download and for a cloud AI model | |

| Graphics card | What Studio uses |
|---|---|
| NVIDIA GeForce GTX 16 series, RTX 20, 30, 40 or 50 series | The GPU. Clips are faster. |
| Older NVIDIA cards (GTX 10 series and earlier), AMD or Intel graphics | The CPU. Studio works, but slower. |

Keep the NVIDIA driver up to date. A second clip job at the same time waits until the card has 4.5 GB of video memory free. Leave room for the game and OBS when you clip while you stream.

## Set up Studio

Studio is the clip maker in PostDeck. It is built on [OpenShorts](https://github.com/mutonby/openshorts) by mutonby (MIT license).

1. In PostDeck, open **Studio > Server**.
2. Click **Set up Studio**. PostDeck downloads Python, the Python packages and ffmpeg one time. Studio then uses about 2.5 GB without an NVIDIA card and about 8 GB with one.
3. Under **AI model**, paste a Gemini API key. You can get one free at https://aistudio.google.com/apikey. If you pay for Claude or OpenAI, or run a local model, select it there and paste its key.

## Updates

PostDeck checks this repo when it starts and every 10 minutes after that. It downloads a new version in the background. When the download is complete, a banner shows **Restart to update**.

| Problem | What to do |
|---|---|
| No banner after a new release | Keep PostDeck open for 10 minutes, or close it from the tray and start it again. |
| The update does not install | Download the newest installer from the release page and run it. Your posts and settings stay. |

## Privacy and terms

- Privacy Policy: https://cribian122.github.io/postdeck-releases/privacy.html
- Terms of Use: https://cribian122.github.io/postdeck-releases/terms.html

To report a problem or ask for a change, open **Report a problem** in PostDeck.
