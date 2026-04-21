# Moodboard Mixer

A vibe-based music discovery app. Pick a mood, see the aesthetic, hear the playlist.

Built with HTML, CSS, and JavaScript. Uses Spotify embeds for in-app music playback and Unsplash for curated moodboard images.

## How to Run Locally

1. Clone this repo:
   ```
   git clone https://github.com/vanshikagaur12/moodboard-mixer.git
   cd moodboard-mixer
   ```

2. Open `index.html` in your browser. That's it -- no install or build step needed.

   On Mac you can run:
   ```
   open index.html
   ```

## Live Site

The app is deployed on GitHub Pages: https://vanshikagaur12.github.io/moodboard-mixer/

## Features

- **13 curated vibes** with matching moodboard images and playlists
- **Spotify embedded player** -- music plays right in the app
- **Pinterest-style masonry grid** for visual moodboards
- **Search with autocomplete** -- find vibes by name
- **Shuffle Vibe** -- jump to a random new vibe
- **Skip / Shuffle tracks** -- control your queue
- **"Vibe not found" page** -- friendly redirect when searching for vibes we don't have yet
- **Responsive design** -- works on desktop and mobile

## Tech Stack

- HTML / CSS / JavaScript (no frameworks, no build step)
- Spotify Embed API (in-app playback)
- Unsplash (curated images)
- Google Fonts (DM Sans + Playfair Display)

## Complexity Markers

This project hits 5 of the assignment's complexity markers:

1. Multiple components with shared state (home, vibe page, player, search, queue)
2. External API integration (Spotify embeds)
3. Non-trivial logic (vibe matching, search autocomplete, queue management)
4. Responsive, thoughtful UX (masonry grid, mobile layout, transitions)
5. Persistent data flow (curated vibe database driving all views)

## AI Tools Used

Built with Claude (Anthropic) as a coding partner for code generation, debugging, and architecture decisions.
