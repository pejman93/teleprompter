# Teleprompter

A teleprompter that runs in the browser. I use it on my phone when recording videos: paste the script, turn the phone sideways, press play, and read along as the text scrolls.

It's a single HTML file with no build step and no dependencies.

**Live:** https://pejman93.github.io/teleprompter/

## Usage

1. Open the page on your phone and paste your script into the text box.
2. Rotate the phone to landscape and tap **Start prompter**.
3. Tap **Play**. Read each line as it passes the yellow markers.

| Control | What it does |
| --- | --- |
| Tap the text | Play / pause |
| Drag the text | Scroll back or skip ahead by hand |
| Speed − / + | Scroll speed, 1 (slow) to 10 (fast) |
| A− / A+ | Text size |
| ⟲ | Back to the top |
| Mirror | Flip the text horizontally, for use behind teleprompter glass |
| Fullscreen | Hide the browser bars (not supported on every phone) |

On a keyboard, Space plays/pauses and the up/down arrows change speed.

The script, speed and text size are saved in the browser's local storage, so they're still there next time. Nothing is sent anywhere.

The page asks the browser to keep the screen awake while it plays. If your screen still dims, raise the auto-lock time in your phone's settings.

## Running locally

Open `index.html` in a browser. That's it.

## License

[MIT](LICENSE)
