# Vim Commands Cheat Sheet

## **Navigation Commands**
- `h` — Move left
- `j` — Move down
- `k` — Move up
- `l` — Move right
- `5j` — Move 5 lines down
- `w` — Move forward by word
- `b` — Move backward by word
- `e` — Move to the end of the word
- `$` — Jump to the end of the line
- `0` — Jump to the beginning of the line
- `^` — Jump to the first non-empty character on the line
- `f<char>` — Jump to the next occurrence of a character
- `F<char>` — Jump to the previous occurrence of a character
- `(` — Move one sentence up
- `)` — Move one sentence down
- `{` — Move one paragraph up
- `}` — Move one paragraph down
- `Ctrl+d` — Move down half a page
- `Ctrl+u` — Move up half a page
- `Ctrl+f` — Move down a full page
- `Ctrl+b` — Move up a full page
- `gg` — Jump to the beginning of the file
- `G` — Jump to the end of the file

---

## **Insert Mode Commands**
- `i` — Insert before the cursor
- `a` — Insert after the cursor
- `I` — Insert at the beginning of the line
- `A` — Insert at the end of the line
- `o` — Insert a new line below the current one
- `O` — Insert a new line above the current one
- `c` — Change the current word
- `s` — Replace the current character

---

## **Copy and Paste Commands**
- `yy` — Copy (yank) a line
- `p` — Paste after the cursor
- `P` — Paste before the cursor
- `yi(` — Yank text between parentheses
- `yi{` — Yank text between curly braces
- `ya{` — Yank text including curly braces

---

## **Undo and Redo**
- `u` — Undo the last change
- `Ctrl+r` — Redo the undone changes

---

## **Delete Commands**
- `dw` — Delete a word
- `ds` — Delete a sentence
- `dp` — Delete a paragraph
- `dd` — Delete the current line
- `d<char>` — Delete up to a specific character

---

## **Repeat Command**
- `.` — Repeat the last command

---

## **Search Commands**
- `/` — Search forward for a term
- `n` — Jump to the next search result
- `N` — Jump to the previous search result
- `*` — Search forward for the word under the cursor
- `#` — Search backward for the word under the cursor

---

## **Marks and Bookmarks**
- `m<char>` — Set a bookmark with a character
- `` `<char> `` — Jump to the bookmark with the given character
- `` `` `` — Toggle between the last two visited places
- `` `. `` — Jump to the last edited location
