# Update log

Every version of the website gets an entry here, a git tag `vX.XXX` and a GitHub release.

## 1.001 — 2026-10-29

Contact page, two new app pages, and the same text as the WordPress site.

### Added
- **Contact Us** page (`contact.html`): office, email and social cards; a message form that opens the visitor's email app with the message ready to send; Volunteer and CSR / Partnership sections; links to both Trust websites.
- **OPD Drug Directory** page (`opd-drug-directory.html`), including its sister app **OPD Memory**.
- **OPD Clinic Record** page (`opd-clinic-record.html`): offline daily OPD register, Excel and Google Drive features, free trial then licence.
- **Our Apps** section on the Home page with cards for all three apps.
- Contact, OPD Drug Directory and OPD Clinic Record links in every page's menu and footer.

### Changed
- Home, About and Divyangjan Calculator text now matches vinyasvastha.wordpress.com word for word (charter quote, Divyangjan card, focus-area text, button labels).
- "Volunteer", "Inquire" and "Contact" buttons now go to the Contact page instead of opening email directly.
- `style.css`: styles for the contact form, full-width soft sections and the closing banner.

### How to test
1. Open https://vinyasvastha.github.io and check the menu shows all seven links.
2. On Home, check the Our Apps cards open each app page.
3. On Contact Us, fill the form and press Submit: your email app should open with the message filled in.
4. Check the "WordPress Site ↗" link opens vinyasvastha.wordpress.com.
