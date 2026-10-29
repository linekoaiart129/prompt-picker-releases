# Changelog

## 0.1.19

- Pick prompt > Character > New is two fields, Name and Source. The first pick creates that character in Prompt Log with a stable numeric id and logs the pick. Undo removes the character when it has no logged prompts left. Redo creates it again.
- The onboarding tour, hints, and tooltips match the current app: Filters, Label Option (Alt+F and Alt+N), Ctrl+N on Prompts Data, the New-label remove button with Ctrl+Z, Settings > Others (Contact and the two uninstall choices), the install folder, and the update popup.
- Settings > Shortcuts lists every shortcut, grouped by tab, including Alt+F, Alt+N, and Ctrl+N. They can be rebound. Reset to default restores them. A key already used by another action is rejected.
- Settings > Updates shows the current version, Check for updates, and the short list of what changed.
- Prompt Log date added follows file order: the last character is newest and the first is oldest. Existing added dates are rewritten from that order. Each character has a stable numeric id. Importing the same id replaces that character's log instead of duplicating it.
- Settings > Reset has Delete Prompt Data, Delete Prompt Log, and Delete all (both), each with its own confirmation.
- Import file opens the system file picker and imports immediately.
- Refresh is at the top-right inside Prompts Data. It highlights when the list stalls or a load fails, and it does not drop an unsaved edit.
- Avast or AVG Auto-Sandbox can stop the unsigned setup before it starts. Do not turn the antivirus off. SmartScreen still uses More info, then Run anyway.

## 0.1.16

- If setup can start but cannot write the folder, it explains Controlled Folder Access, antivirus, or a permissions policy, and points to `%TEMP%\PromptPicker-install.log`. That log records the account name, the profile folder, and the temp folder from the first step. Do not turn antivirus off. If the log file was never created, setup was stopped before it started.
- Label Option: Alt+F sets a filterable label and Alt+N adds a note. On the Prompts Data tab, Ctrl+N opens a new prompt with the next row number and the usual default level.
- An update installs into the existing folder, including a 0.1.12 install in `%LOCALAPPDATA%\Programs\Prompt Picker`. It does not add a second copy. A silent upgrade overwrites that folder and does not run the previous uninstaller. Setup does not relaunch, delete, or move its own exe. The first launch removes a leftover copy in another folder and points the Desktop shortcut at the running program.
- The uninstaller shows one window, closes Prompt Picker first, and does not start the app.
- The installer asks for a folder. The suggested folder is `C:\Prompt Picker` when it can be created, otherwise a Prompt Picker folder in your user profile. A path with a space is kept in full.
- Only a Desktop shortcut is created. It does not carry an AppUserModelID. An old Start Menu shortcut named Prompt Picker is removed. That shortcut was the "Unspecified error": it stored AppUserModelID `com.lineko.promptpicker`.
- Each launch writes `%APPDATA%\Prompt Picker\startup.log`.
- A picked prompt whose label matches New shows a remove button on that result chip. Removing the label updates the modified time and can be undone or redone.
- Uninstall can keep data or wipe everything. Keep data also keeps settings and install choices. The next install prefills that folder and those options, and restores the settings. Wipe everything removes them.
- Settings includes Contact: Discord, Patreon, X, then Telegram.

## 0.1.12

- Shortcuts repair themselves on launch. A missing install folder is not reused. A startup error offers a repair dialog. A clean-machine check runs before a release is published.
