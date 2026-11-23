# ClaimSaathi

Mobile-first health-insurance claim companion for India and global users.

## MVP features
- Claim document readiness checklist (saved locally in the browser)
- Policy wording keyword finder for common clauses
- Hospital bill vs insurer settlement arithmetic comparison
- Claim rejection / deduction review checklist
- Editable insurer representation letter generator

## Run locally
Open `index.html` in a browser. No build step, API key, account, database or paid service is required.

## Deploy
Import this GitHub repository into Vercel. It is a static HTML/CSS/JavaScript site; no framework or build command is needed.

## Privacy
This MVP performs its tools in the browser. Checklist ticks are stored in browser localStorage. Policy text and claim details are not sent to a server by this code. Avoid entering Aadhaar numbers, OTPs, passwords, bank details or unnecessary medical information.

## Important limitations
ClaimSaathi is an independent information and document-organisation tool, not an insurer, insurance intermediary, medical provider or law firm. Keyword detection is not policy interpretation. Bill comparison is arithmetic only. Generated letters are drafts and must be checked for accuracy. The tool cannot determine coverage, guarantee claim approval or recover money. Always verify the policy wording, insurer instructions, applicable deadlines and official grievance process.

## Stack
Static HTML, CSS and vanilla JavaScript. No third-party runtime dependencies.
