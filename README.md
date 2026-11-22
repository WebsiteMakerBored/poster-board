# Poster Board

A movie logging and review website with a clean, Apple-inspired design. Built as a single `index.html` file and hosted free on GitHub Pages. No server and no build step.

## Features

- **Precise ratings:** score any film from 1.0 to 10.0 in 0.1 steps
- **Reviews and diary:** write reviews, set watch dates, and see your history
- **Watched, Likes, Watchlist:** track every film in one place
- **Movie pages:** poster, runtime, description, average rating, and rating distribution
- **Community board:** request movies, upvote and downvote, and comment
- **Profile:** stats, favorites, recently watched, and activity charts
- **Admin panel:** hidden panel for adding and managing movies and requests
- **Light and dark mode:** follows your system setting, with a manual toggle
- **Mobile and desktop friendly:** responsive layout built for touch and mouse
- **Live updates:** changes appear instantly, including across open tabs

## How It Works

Everything runs in the browser. Data is saved with `localStorage`, so it stays on the device and browser you used. Use the **Export JSON** option in the admin panel to back up your movies and import them on another device.

## Run It

**Online:** open the GitHub Pages link for this repo.

**Locally:** download `index.html` and open it in any modern browser.

## Deploy Your Own

1. Create a public GitHub repository.
2. Upload `index.html` to the main branch.
3. Go to **Settings**, then **Pages**.
4. Set Source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Visit `https://your-username.github.io/your-repo-name/`.

## Tech

HTML, CSS, and vanilla JavaScript in a single file. No frameworks or dependencies.

## Notes

- Data is stored per browser. Clearing browser data erases it, so export a backup regularly.
- Sharing data between visitors in real time would require a backend such as Firebase or Supabase.

## License

MIT. Free to use and modify.
