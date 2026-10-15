# WordPress Audit Checklist

Mark each item `OK`, `Needs attention`, `Critical`, or `Not checked`.

## 1. Updates
- WordPress core on the latest stable version
- All plugins updated; list any that are abandoned (no update in 2+ years)
- Active theme and parent theme updated
- PHP version supported by WordPress and the hosting provider
- Unused plugins and themes deactivated and deleted

## 2. Security
- SSL certificate valid, HTTPS forced site-wide
- Admin accounts reviewed; no unknown users, no user named "admin"
- Strong passwords and 2FA for admin users
- Security plugin or firewall active; last scan result
- Login page protected (limit attempts or rename/hide where appropriate)
- File editing disabled in the dashboard
- No sign of malware: unknown files, spam links, unexpected redirects

## 3. Backups
- Automatic backup schedule exists (daily or weekly)
- Last successful backup date
- Backups stored off the server (cloud storage, not only the host)
- A restore has been tested at least once in the last 6 months

## 4. Performance
- PageSpeed / Core Web Vitals for mobile and desktop (use the numbers the user provides)
- Caching plugin or host-level cache active
- Images compressed and served in modern formats
- Heavy plugins or scripts slowing key pages
- Database clean: revisions, spam comments, expired transients

## 5. SEO basics
- Home page title and meta description present and unique
- XML sitemap submitted to Google Search Console
- `robots.txt` not blocking important pages
- No accidental "noindex" on live pages
- Broken links (404s) on key pages
- Headings structure sensible (one H1 per page)

## 6. Uptime and hosting
- Uptime percentage for the period (only if monitoring data is provided)
- Any downtime incidents, with duration and cause
- Hosting resource usage within plan limits

## 7. Content and forms
- Contact and enquiry forms deliver emails (test only with permission)
- Email deliverability: SPF/DKIM set up for the sending domain
- Cookie/privacy notices present where required
- Key pages up to date (contact details, prices, offers)
