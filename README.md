# Kuwait University — Microsoft 365 Storage & Teams Cleanup FAQ

Bilingual (Arabic RTL / English LTR) static FAQ site for Kuwait University faculty, teaching assistants, staff, and students covering:

- Urgent backup steps for Class Teams older than 3 years (University Council Decision 1/2026)
- Bulk downloading and copying files from Microsoft Teams and SharePoint
- OneDrive quotas and retention rules
- Outlook & email storage hygiene
- General Microsoft 365 file management best practices

## Structure

- `index.html` — Arabic (primary, `dir="rtl"`)
- `en/index.html` — English (`dir="ltr"`)
- `assets/style.css` — Shared stylesheet using CSS logical properties
- `assets/ku-logo.png` — Kuwait University emblem
- `.nojekyll` — Disables Jekyll processing on GitHub Pages

## Local Preview

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/` (Arabic) or `http://localhost:8080/en/` (English).
