# Changelog

## 1.1.3

- Pick existing selects the same character after a reload or an update, using its log id. New mode still restores Name and Source. A deleted character is left unselected.
- Add prompt and Paste prompts toggle from their own buttons. The X at the top-right of each panel closes that panel.

## 1.1.2

- The working session is restored after an update or restart: character, Name and Source, the last pick, Level / Exclude / Priority, the open tab, scroll position, and unsaved text.
- Add prompt and Paste prompts can be typed in. One closes the other. Esc or the close button dismisses the panel.
- Each Priority chip keeps its own percent. The slider sets the next chip, or only the chip you click.
- Narrow windows keep Refresh compact, keep form controls at a normal height, and wrap prompt cards inside their rounded frame.

## 1.1.1

First public release of the Windows app.

- Pick a prompt by level, with Exclude and Priority. Character > New uses Name and Source. The first pick is saved in Prompt Log, and undo can remove that new character.
- A New label on the result can be removed, and undo puts it back. Ctrl+Z and Ctrl+Y undo and redo a pick.
- Prompts Data stores the library. Paste, import, and a sample template are available when the library is empty. Label Option uses Alt+F and Alt+N. Ctrl+N adds a prompt.
- Import file opens a JSON or text file directly. Refresh sits at the top-right of Prompts Data, highlights if the list gets stuck, and keeps an unsaved edit.
- Prompt Log keeps characters and copied rows. Date added follows the file, and the last character is the newest. Each character has a stable id, and importing that id again replaces the log.
- Settings includes shortcuts grouped by tab, theme colors, backup, and a reset that can delete Prompt Data, the Prompt Log, or both.
- Updates shows this release. A newer version installs into the folder chosen at setup and does not delete prompts.
- A Desktop shortcut is created. An old Start Menu shortcut named Prompt Picker is removed. Uninstall can keep data or wipe everything.
