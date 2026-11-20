# Love and Rescue

A browser based third person 3D rescue game built with Three.js. The current build opens with an illustrated, comic style story prologue before entering the playable world.

## Run locally

Open `index.html` through a local web server so the browser can load the story artwork and other assets. From the project folder, for example:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Story prologue

The five supplied illustrations in `assets/story/` introduce the rescue story: the peaceful valley, the kidnapping, the captive in the fortress, the hero's discovery, and the journey toward the castle. The final title artwork leads into the game.

- Select **Continue** to read the next page; the final button starts the rescue level.
- Select **Back** or use the left arrow to revisit a page.
- Select **Skip intro** or press **Escape** to enter gameplay immediately.
- Right arrow or Enter advances the story.
- A quiet, generated musical motif fades in after the first story interaction and fades out as gameplay begins. Browsers require a user gesture before they allow audio playback.

Story art files:

- `assets/story/prologue-page-1.png`
- `assets/story/prologue-page-2.png`
- `assets/story/prologue-page-3.png`
- `assets/story/prologue-page-4.png`
- `assets/story/title-screen.png`

## Game controls

- **WASD:** Move
- **Shift:** Sprint
- **Space:** Jump
- **C:** Crouch / hide
- **Left mouse / F:** Fire
- **Hold right mouse and drag:** Aim / turn view
- **R:** Reload

The in-game information button shows the current control list.
