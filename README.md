# Wayfarer — Travel & Relocation Planner

A responsive, local-first trip and relocation planning demo for journeys between cities and countries worldwide. Wayfarer brings the journey into one workspace, from route and budget planning through documents, departure, arrival, and settling in.

## Run locally

1. Install Node.js 20.19+ or 22.12+.
2. Run `npm install` from the project directory.
3. Run `npm run dev` and open the local URL printed by Vite.

Use `npm run build` to produce the production build and `npm run lint` to check source files.

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## Included features

- Overview dashboard with progress, next steps, document shortcuts, and destination highlights.
- Editable trip profile for any origin and destination city/country, target month, travel purpose, party, currency, and a user-entered budget target.
- Personal trip roadmap with add/complete actions and progress tracking.
- Copilot-style planning prompts tailored to the saved trip route and purpose.
- Arrival-week checklist, local setup checklist, move-day packing plan, and final-week checklist.
- Move brief with a print-optimized layout.
- Document vault that accepts PDF, JPG, and PNG files and lists file metadata locally.
- General destination planning checklist and explicitly illustrative reminders; verify requirements for your nationality and trip with official sources.
- Preferences, complete demo-data reset, mobile navigation, and browser-local persistence.

## Demo behavior and privacy

The app has no backend. Plan details, checklist state, notification preferences, and document names/metadata are saved in this browser's local storage. Uploaded file contents are not transmitted or stored by the app; selecting a file only adds its name and basic metadata to the local demo vault. Reset demo data restores the starter workspace.

## Scope and accuracy

There is no connected AI model, OCR, account system, official data feed, or live regulatory monitoring. Guidance, timelines, document labels, and updates are illustrative examples—not current official requirements or legal, financial, travel, or immigration advice. The budget target is entered by the user and is not a destination cost estimate. Confirm real requirements with relevant authorities and qualified professionals.

## Production considerations

Before using this as a real service, add authenticated server-side storage, secure document handling and retention controls, verified and dated official information sources, tested accessibility, automated interaction tests, and appropriate privacy/legal review. Do not upload real sensitive documents to this demo.
