# Changelog

## 1.1.8

- Pick, Copy, Undo, and Redo sit in one row inside a single card, with equal widths and the same height. Go to prompt is full width on the row below. The picked prompt's title stays above that card.
- Hover help is off until you turn it on in Settings, Others. Pointing at a field, button, or section shows a short guide after a brief pause. The guide does not cover the field you are typing in. Save keeps the choice.
- The finished-row numbers on a character stay within three lines. Older numbers collapse into a leading …, and the newest numbers stay at the end. Pointing at or clicking that list does not open another list.
- Primary and Secondary use the same picker in Filter labels and in Theme colors: a horizontal hue bar with one round handle, plus a swatch and a hex field. The color stays as you pick it until you press Save.
- No color is a checkbox. A tick makes that label chip's background transparent everywhere it appears. Untick brings its Primary and Secondary colors back. The Filter column is gone. Labels in Filter labels stay available for filtering.
- A label with no custom colors uses the current Theme colors, and it follows theme changes until you set a color for that label. Reset to theme drops the custom colors. No color still makes the chip transparent.
- Clear rows with this label chooses characters from a searchable list. The choices are All characters and each character. Tick several, or click a name to select only that one. Select all and Clear selection are included, with a count such as 3 selected. The confirm names the characters and how many rows will be deleted.

## 1.1.7

- Theme colors stay as you pick them until you press Save. Choosing Primary and then Secondary no longer puts Primary back. Closing Settings without Save restores the saved colors.
- If any Settings tab has unsaved changes, closing Settings or the app window lists what changed, such as Theme colors: Primary, Secondary or Shortcuts: Pick. Apply saves everything and closes. Cancel forgets the changes and closes. Back returns to editing.
- Language, font size, shortcuts, filter labels, theme colors, and Others each save only when you press Save.
- Recent colors shows up to 10 colors you saved, newest first. Click one to set the selected Primary or Secondary color.
- Suggested colors has pairs you can apply together: Neon Pink / Violet, Sunset Orange / Crimson, Ocean Teal / Deep Blue, Forest Green / Lime, Gold / Bronze, Lavender / Lilac, Mint / Cyan, Ruby / Black, Halloween Orange / Purple, and Christmas Red / Green.
- The logo uses Primary and Secondary. After Save, the window icon is redrawn in those colors. The installed program icon and the desktop shortcut stay the icon from setup.
- Gradient buttons and selected segments, including Prompt Pick, Explicit, and Pick existing, fill edge to edge. Rounded corners match, and theme colors no longer leave a light ring or a dark sliver on the edge.

## 1.1.6

- Prompt cards no longer show a green edge or a Done badge. Finished rows stay in the log and still stay out of the next pick.
- Settings renames Labels to Filter labels. The label manager names each column, and resting the pointer on a column name explains what it does.
- Each label has No color, Primary, and Secondary. No color makes that chip transparent. Primary and Secondary are hue, saturation, and lightness sliders, and those colors show on that label's chips everywhere.
- Filter stays a checkbox under its own column name. A saved filter choice is kept when you set a color, rename the label, or import.
- Drag a column edge to resize it. The label manager and the Settings window grow with the column.

## 1.1.5

- Updates and download links use the GitHub account linekoaiart129. An installed 1.1.4 still finds this release through GitHub's redirect from the previous account.
- The notes in the app are the change bullets only.

## 1.1.4

- Pick reads the selected character's done rows at the moment of the click and never returns one of those rows, including rows saved as text and numbers mixed together or imported from spreadsheet JSON. Fast clicks and Enter are locked until that row is saved. Undo and Redo update the same list immediately.
- The done-row numbers on a character card stay within three lines. Older numbers collapse into a leading …, and the newest numbers stay visible. Hover or click the list to see every number. The full list is still what Pick checks.
- Prompt Log starts with Date added, newest and Pick order, newest to oldest. A later choice is remembered. A fresh install, a missing saved choice, or Delete all uses these defaults again.
- Prompt Log’s clear control is labelled Clear rows with this label. Clear labelled rows deletes logged rows that have that label, after a confirm that lists how many. The prompts stay.

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
