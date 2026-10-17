# SmartBiz Uganda

A mobile-friendly, local-first sales, inventory, expense and estimated-profit tracker for small businesses in Uganda.

## Current MVP features
- Record sales and automatically reduce stock.
- Track product costs, selling prices, quantities and low-stock thresholds.
- Record operating expenses.
- View daily sales and gross profit, monthly recorded expenses, stock alerts and all-time summaries.
- Search sales and inventory.
- Export CSV reports and download/restore a JSON backup.
- Responsive interface for phones and desktops; UGX display.
- Progressive Web App (PWA) manifest, install prompt, service-worker app-shell caching and an installable SVG icon.
- Privacy notice for the current local-only prototype.

## Run it
Open `index.html` in a modern browser or host the repository as a static website. HTTPS hosting is required for service-worker/offline functionality in production (localhost is permitted for development). On supported browsers, use **Install app** or the browser menu's **Add to Home screen** option.

## Important limitations
- Records remain in the current browser on the current device using `localStorage`; they do not sync between devices and may be lost if browser data is cleared. Export backups regularly.
- This is an MVP, not audited accounting software. Net profit is calculated from recorded sales, saved product costs and entered expenses.
- No customer login, cloud sync, staff roles, tax calculations, online checkout or payment processing is included.
- No live deployment, app-store submission, or revenue is confirmed by this source-code commit.
- A separate payment provider and supported Ugandan payout route must be verified before charging users.

## Before monetisation / app-store release
1. Validate demand and pricing with real small-business owners.
2. Add secure authentication and cloud data storage if multi-device use is required; add tests, error handling and data export/deletion workflows.
3. Configure a verified support contact and production privacy policy.
4. Configure a production hosting account and custom domain (if desired), then test the deployed app on Android and iOS.
5. Create native store packages, screenshots, content ratings, privacy disclosures and developer accounts. Store accounts, fees, identity checks and review cannot be completed by source code alone.

## License
No license has been assigned yet. Ask the owner before reusing or redistributing the code.
