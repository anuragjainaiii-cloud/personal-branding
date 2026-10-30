# Anurag Jain — Personal Branding Website

## Start locally
1. Install Node.js 20+.
2. Run `npm install` in this folder.
3. Run `npm run dev` and open the displayed local URL.
4. Run `npm run build` to check production output.

## No-code edits with AI
Ask an AI coding assistant: "Edit src/content.js to update the website content. Preserve the design and verify npm run build." All text, links and portfolio stories are centralized in `src/content.js`.

## Before publishing — required
- Your supplied landing-page photo is included at `public/portrait.jpg`.
- Your Topmate booking link is configured in `src/content.js`: `https://topmate.io/anurag_jain22`.
- Verify job title (LinkedIn/Bold profile differs from the latest user-provided title), product-level claims, award names, patent metadata and publishable metrics.
- Replace broad LinkedIn article links with direct URLs if desired.
- Add your preferred public email if you want email contact.
- Review employer confidentiality and permissions before publishing product names, pricing, screenshots, customer data or internal metrics.

## Deployment
Import the folder into GitHub and Vercel. Framework preset: Vite. Build command: `npm run build`; output directory: `dist`.

## Acceptance criteria
- `npm run build` exits successfully.
- All six menu links navigate to their corresponding sections.
- At 375px, 768px and 1440px widths, content does not overflow horizontally.
- Every visible external link opens a real intended destination.
- Confirm the photo crop and test the Topmate booking destination in a browser before launch sign-off.
- Every public metric and product claim must be approved by Anurag.

## Revision process
Change one section at a time; run build, check desktop/mobile, review text and links, then publish. If data is unknown, keep a clear placeholder or omit the claim; never invent it.

## Sources consulted
- https://www.linkedin.com/in/anurag-jain-a981ab19/
- https://bold.pro/my/anurag-jain-pm

The website uses polished summaries, not verbatim reproduction of source profile descriptions.
