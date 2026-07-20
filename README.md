# Krello

Your own tiny Trello. A board of all your projects at a glance, each with its own TODO list, so nothing gets forgotten.

**[Open the board →](https://jkbustillo.github.io/Krello/)**

One `index.html`. No backend, no build step, no dependencies — open the file and it works, online or off.

## Using it

- **New project** — type in the dashed card, press Enter.
- **New task** — type in the project's field, press Enter. Focus stays put, so you can add several in a row.
- **Rename a project** — click its title.
- **Reorder or move tasks** — drag them within a project or across to another one.
- **Reorder projects** — drag a card by the grip next to its title. With the grip focused, the arrow keys move it too.
- **Move your board** — the panel at the bottom holds the whole board as one line of text. Copy it to back it up, paste one in to restore it.

## Where your tasks live

In `localStorage`, which is scoped per origin. The hosted board and a local copy of `index.html` are two separate origins, so they keep two separate boards — use the copy/paste panel to move between them. Clearing site data wipes the board.

## Notes

- On touch, press and hold a task to pick it up; a project's grip drags straight away. The board scrolls when you drag a task near the top or bottom edge.
- Importing replaces the current board rather than merging, and asks first.
- Task order, project order and completion state are all saved as you go.

## Running it locally

```
git clone https://github.com/JKBustillo/Krello.git
```

Then open `index.html`. That's the whole setup.
