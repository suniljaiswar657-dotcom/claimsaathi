# ClaimSaathi

Mobile-first health-insurance claim companion for India and global users.

## MVP features
- Claim document readiness checklist (saved locally in the browser)
- Policy wording keyword finder for common clauses
- Hospital bill vs insurer settlement arithmetic comparison
- Claim rejection / deduction review checklist
- Editable insurer representation letter generator with print / save-as-PDF support
- User-controlled clearing of saved checklist ticks\n- Local consolidated claim review report with print / PDF and HTML download
- Transparent pricing preview: free core tools and proposed one-time Plus claim pack

## Run locally
Open `index.html` in a browser. No build step, API key, account, database or paid service is required.

## Deploy
Import this GitHub repository into Vercel. It is a static HTML/CSS/JavaScript site; no framework or build command is needed.

## Privacy
This MVP performs its tools in the browser. Only checklist ticks are stored in browser localStorage, and users can clear them with the Clear saved checklist control. Other entered policy and claim text, including generated review reports, is processed in the current page and is not sent to a server by this code. The page loads web fonts from Google Fonts, so the browser may contact Google to retrieve those fonts. Avoid entering Aadhaar numbers, OTPs, passwords, bank details or unnecessary medical information.

## Important limitations
ClaimSaathi is an independent information and document-organisation tool, not an insurer, insurance intermediary, medical provider or law firm. Keyword detection is not policy interpretation. Bill comparison is arithmetic only. Generated letters are drafts and must be checked for accuracy. The tool cannot determine coverage, guarantee claim approval or recover money. Always verify the policy wording, insurer instructions, applicable deadlines and official grievance process.

## Stack
Static HTML, CSS and vanilla JavaScript. No third-party runtime dependencies.


## Pricing and payments
The site currently shows a pricing preview only: free core tools and proposed ClaimSaathi Plus pricing of ₹149 per claim pack (global target US$2.99). These prices are not validated market pricing and are not purchasable. No checkout or payment collection is active. Before launch, implement server-side payment verification, order records, refunds, access control and privacy/security review. Never treat a browser-only flag as proof of payment.
