# WALLS HAVE EARS — Sound Instrument

A keyboard sound instrument that runs entirely in the browser. Assign sounds to keys,
play them with your keyboard (or tap pads on a phone), and perform with the visualizer.

## Run it

The built-in sound archive loads its `.wav` files over HTTP, so open the app through a
web server rather than double-clicking `index.html`.

**Locally**

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

**On GitHub Pages**

Repo → Settings → Pages → deploy from the `main` branch, root folder.

(You can still use your own audio files with ADD A SOUND even when opened from a file.)

## Look

Black and bone-white, nothing else. Huge Impact type cropped by the screen edge, thick rules,
and almost no decoration. On a computer, the concrete wall only appears where your cursor
lights it. On a phone the light drifts slowly by itself.

## How to use

The main page shows only the title and **your sounds**, each one a numbered "specimen".
Everything else is behind the **MENU** button:

- **Your sounds**: press the keys on your keyboard to play. **MIX** on a sound reveals its
  volume and a **LOOP** toggle (a looping sound starts on one press and stops on the next).
- **Add a sound**: put one of your own audio files on a key.
- **Sound room**: a numbered catalogue. **PREVIEW** to listen, add favourites to the basket,
  choose keys, then **Take basket to keyboard**.
- **Project gallery**: keep several named versions of your instrument in this browser, and **Load project file** to open a backup (.json) from your computer.
- **Performance**: full screen. Type a word on your keyboard and it appears as large as the
  screen allows; press **Enter** and every letter dissolves. Backspace deletes, Esc closes.
  On a phone the keyboard pops up by itself; tap **Keyboard** or the screen to bring it back.
- **Save / Load project**: download or open a backup JSON file (older files still load).

- **View: mobile / desktop**: the layout switches by itself on small screens. This menu item forces
  one or the other and remembers your choice. On a phone, tap a key letter (or PLAY) to play a sound.

Esc closes whatever is open.

## Files

```
index.html     the whole app (HTML, CSS, JS)
sounds/        105 built-in sounds in 7 categories
```
