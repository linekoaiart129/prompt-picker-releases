# Prompt Picker

[![Latest release](https://img.shields.io/github/v/release/broplaygame75-ai/prompt-picker-releases)](https://github.com/broplaygame75-ai/prompt-picker-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/broplaygame75-ai/prompt-picker-releases/total)](https://github.com/broplaygame75-ai/prompt-picker-releases/releases)

**18+.** Prompt Picker is for adults. The first launch asks "Are you 18 or older?"

Versions use `1.FEATURE.FIX`. The middle number goes up for new features. The last number goes up for a small fix. 1.1.1 is the first public Windows release. The web app launches separately as 1.2.0. Later Windows notes describe the current release, not a list of older builds.

Prompt Picker draws one prompt from your own library. It keeps the prompt text, names, levels, labels, notes, and a log of which character used which row. You can search, sort, and import or export that library as JSON. Each GitHub release lists only what changed and the download files. This page is the install guide. This repository publishes installers and documentation only. Source code is not included.

## Download

Installers are on the [releases](https://github.com/broplaygame75-ai/prompt-picker-releases/releases) page.

- `PromptPicker-Setup-1.1.3.exe` is the installer. Auto-update uses this file and `latest.yml`. Leave those names as they are.
- `PromptPicker-1.1.3-Windows.zip` contains the installer, the install guide, and the pictures.

SHA-256 checksums for 1.1.3:

| File | SHA-256 |
| --- | --- |
| `PromptPicker-Setup-1.1.3.exe` | `be7f372902e75dfd811581c5c902392188ce6ff179084357419e6b0a589ae459` |
| `PromptPicker-1.1.3-Windows.zip` | `5eb12359149d9b89b743e30110bbcc602fca08b86d2e49e19f298706242c57c0` |

The same checksums are listed with the download files on that version's release. The release notes do not repeat this install guide.

## Install

1. Download the Setup exe, or open the zip and run the Setup exe inside it.
2. If Windows says "Windows protected your PC", click **More info**, then **Run anyway**. The app is not code-signed. Do not turn off SmartScreen or Defender.
3. Avast or AVG Auto-Sandbox can stop the unsigned installer before it starts. Do not turn the antivirus off. Add an exception for the setup file, or report a false positive at [Avast's false-positive form](https://www.avast.com/false-positive-file-form) and include the download URL. If `%TEMP%\PromptPicker-install.log` was never created, setup did not start.
4. Choose a folder. The suggested folder is `C:\Prompt Picker` when that location can be created. Otherwise it is a Prompt Picker folder in your user profile. Program files go in the folder you choose.
5. A Desktop shortcut is created. A Start Menu shortcut is not created, and an old Start Menu shortcut named Prompt Picker is removed.
6. Confirm you are 18 or older, then pick a prompt.

Pictures and the same steps in English, Tiếng Việt, 中文, and 한국어 are in the [install guide](guide/HOW-TO-INSTALL.md).

## Update

An update installs into the folder you already chose. It does not ask for a folder again and it does not delete prompts or settings. Prompts stay in `%APPDATA%\Prompt Picker\data`.

## Uninstall

Settings > Others and Windows Settings > Apps offer the same two choices.

**Uninstall, keep data** removes the app, shortcuts, uninstall entries, temporary files, and the updater cache. It keeps prompts, language, theme, sorts, hints, and every other preference, plus the chosen folder and the desktop shortcut choice. The next install opens with that folder filled in and those options selected, and the app restores the settings. Export a JSON backup first (Settings > Backup & Import) if you want a copy.

**Uninstall and wipe everything** removes the app, the prompts, the settings, the install folder, and the saved install choices. This cannot be undone.

## Contact

1. [Discord](https://discord.gg/yH5AAdj5qY) is the preferred contact. Fastest reply.
2. [Patreon](https://www.patreon.com/c/linekoaiart447658)
3. [X](https://x.com/lyht111222333)
4. [Telegram](https://t.me/linekoaiart) is checked less often.

## FAQ

**Where do my prompts go?** `%APPDATA%\Prompt Picker\data` (`prompts.json` and an images folder). Settings such as language, theme, sorts, and hints live in that data and in `%APPDATA%\Prompt Picker`.

**Will an update erase my prompts?** No. An update replaces the program files in the folder you chose.

**Why does SmartScreen warn me?** The installer is not code-signed. Click **More info**, then **Run anyway**. Leave SmartScreen and Defender on. Do not turn them off.

**Avast or AVG blocked the installer and nothing was installed.** Auto-Sandbox can stop the unsigned setup before its first instruction, so there is no install folder, no shortcut, and no `%TEMP%\PromptPicker-install.log`. CyberCapture or Behavior Shield can do the same. Defender's protection history stays empty while Defender is passive. Do not turn Avast or AVG off. Add an exception for the setup file, or submit it as a false positive at [Avast's false-positive form](https://www.avast.com/false-positive-file-form) and include the download URL from the releases page. After it is cleared, run the same installer again.

**Why was an old Start Menu shortcut an "Unspecified error"?** That shortcut stored an AppUserModelID the Start Menu could not activate. Prompt Picker does not create a Start Menu shortcut and removes the old one.

**What does "keep data" remember?** Prompts and every preference, the chosen folder, the installer language, and the desktop shortcut choice. The next install prefills those. "Wipe everything" removes them.

## Troubleshooting

- The app writes `%APPDATA%\Prompt Picker\startup.log` on each launch and `%APPDATA%\Prompt Picker\crash.log` when something fails. Include both when you report a bug, along with the app version, the Windows version, and the steps you took.
- If the Desktop shortcut is missing, open the app from the install folder once. It recreates the Desktop shortcut and removes a stale Start Menu shortcut.
- If an older install does not finish updating, download this installer and run it once. Later updates install into the same folder.

## Community

Bug reports and feature requests use the issue templates. See [SUPPORT.md](SUPPORT.md), [CONTRIBUTING.md](CONTRIBUTING.md), [SECURITY.md](SECURITY.md), and [CHANGELOG.md](CHANGELOG.md).
