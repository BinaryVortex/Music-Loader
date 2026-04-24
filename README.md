# Music-Loader

Music-Loader is a lightweight, self-contained music player built with plain HTML, CSS and a bit of JavaScript. It demonstrates a simple audio player with an animated visualizer built from CSS — great as an example, mini demo, or starting point for a small web audio UI.

![Music Loader Screenshot](./Screenshot%202024-07-09%20170712.png)

## Features

- Simple, accessible audio player using the HTML5 <audio> element
- Loop and autoplay support (configured in index.html)
- CSS-driven animated visualizer bars
- Responsive layout that runs entirely in the browser — no build tools or server required

## Preview / Demo

To try the demo locally:

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Music-Loader.git
2. Open `index.html` in your browser (double-click or use `file://` path).

The player uses an online audio source by default. Replace the <source> element in `index.html` with your audio file URL or a local file path to test your own audio.

## Usage

Open `index.html` and look for the audio element around the top of the file:

```html
<audio controls loop autoplay>
  <source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/9473/new_year_dubstep_minimix.ogg" type="audio/ogg">
  Your browser does not support the audio tag
</audio>
```

Replace the `src` attribute with your audio file to change the track. Remove `autoplay` if you prefer the player not to start automatically.

## Customization ideas

- Swap the audio source(s) with your own tracks or add multiple source formats (ogg/mp3).
- Tweak visualizer colors, animation timing, and number of bars in the CSS.
- Add JavaScript to sync visualizer animation to actual audio frequency data using the Web Audio API.
- Make the layout mobile-first and add play/pause/next controls.

## File structure

- `index.html` – the full demo (styles + markup in one file)
- `Screenshot 2024-07-09 170712.png` – screenshot used above
- `README.md` – this file

## Contributing

This project is small and intended as a demo. Contributions, suggestions and bug reports are welcome — open an issue or submit a pull request with improvements.

## License

No license specified. If you'd like this project to be used or contributed to under a particular license, add a LICENSE file (for example, MIT) to the repository.

---

If you want, I can:

- Add a short live GitHub Pages deployment guide and update the README with a hosted demo link if you enable Pages for this repo.
- Extract the CSS into a separate file and make the markup cleaner.
- Add a sample local audio file and fallback formats for improved compatibility.
