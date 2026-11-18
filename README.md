# Hoppy Digitals website

## Run locally
1. Install Node.js (LTS).
2. Extract this ZIP.
3. Open the project folder in VS Code.
4. Run `npm install`.
5. Run `npm run dev`.
6. Open the local URL shown in the terminal.

## Build
Run `npm run build`. Vite outputs the production website to `dist`.

## Deploy to Netlify
1. Push this project folder to a GitHub repository.
2. In Netlify choose **Add new project → Import an existing project**.
3. Connect GitHub and select the repository.
4. Build command: `npm run build`.
5. Publish directory: `dist`.
6. Deploy.

The included `netlify.toml` already defines these settings and the SPA fallback.

## Replace brand assets
Put the approved original logo at `public/assets/hoppy-logo.png` and the founder portrait at `public/assets/founder-israel.jpeg`. The supplied logo and founder portrait are already included in `public/assets/`. Keep their filenames unchanged. Three Excel dashboard videos are also included and embedded in the portfolio section.

## Notes
- Contact form currently uses a mailto fallback; connect Netlify Forms or a form service before launch for reliable form submissions.
- Booking uses a Calendly placeholder URL. Replace `YOUR_CALENDLY_LINK` in `src/main.jsx` after creating the booking event.
- CRM demo uses browser localStorage and sample data. It is a portfolio demo, not a production CRM and has no authentication or server database.
- Project screenshots/videos should replace the labeled portfolio media placeholders before public launch.
