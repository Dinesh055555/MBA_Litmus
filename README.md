# Litmus AI Coach — Premium Red & White Prototype

A responsive, single-page static web prototype for an MBA Litmus case competition. It includes a student dashboard, diagnostic study coach, quizzes, study planner, analytics, flashcards, mentor-connect demo and goals.

## Run locally

Open `index.html` in Chrome or Edge. No build or dependencies required. Google Fonts are optional and need internet; system fonts are used as fallback.

## Deploy on Render (recommended: Static Site)

1. Create a GitHub repository and upload **the contents of this folder** (not the ZIP itself).
2. Push to the `main` branch.
3. In Render, select **New → Static Site**, connect GitHub and select the repository.
4. Use **Build Command:** `echo "Static site ready"` and **Publish Directory:** `.` (a single dot).
5. Deploy. Render will issue a public HTTPS `onrender.com` URL.

You can alternatively deploy as a **Blueprint** using the included `render.yaml`, which configures the same static service.

## Share with judges

After deployment, open the public Render URL and test the navigation and quiz on mobile. Use **that public URL**, not a local file path or GitHub repository URL, for the hyperlink and QR code in the presentation.

## Important limitations

- Front-end demonstration only: **no real GPT-6 connection** and no server or user accounts.
- Recommendations are **rule-based**; data is illustrative.
- Mentor booking is simulated; no real booking is sent.
- User progress is not persisted across reloads.
- Do not enter personal or sensitive information; the demo is publicly accessible once deployed.
- Google Fonts are fetched from Google when online; other app functions require no external APIs.

## Files

- `index.html` — complete interactive app (HTML, CSS, JavaScript)
- `render.yaml` — optional Render Blueprint configuration
- `README.md` — instructions
- `.gitignore` — common local exclusions
