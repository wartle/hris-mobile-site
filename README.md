# hris-mobile-site

Official landing page, support, privacy policy, and terms of use for the **Dalaguete HRIS** mobile app — the employee attendance &amp; self-service application for the Municipality of Dalaguete, developed by ITSM.

Static site (plain HTML/CSS/JS) intended for GitHub Pages.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | Landing page (features, modules, security, get-the-app) |
| `privacy.html` | Privacy Policy (RA 10173 / Data Privacy Act aware) |
| `terms.html` | Terms of Use |
| `support.html` | FAQ &amp; support |
| `contact.html` | Contact information |
| `css/styles.css` | Site styles (brand: purple → green) |
| `js/main.js` | Nav toggle, smooth scroll, scroll-reveal, image skeletons |
| `images/` | App icon, LGU seal, screenshots |
| `CNAME` | Custom domain for GitHub Pages |

## Before publishing

The legal pages are templates. The Municipality of Dalaguete should:

- Confirm the **Data Protection Officer (DPO)**, **HRMO**, and **MIS** contact details in `privacy.html`, `terms.html`, `support.html`, and `contact.html`.
- Have the legal office review the Privacy Policy and Terms of Use.
- Adjust the `CNAME` (currently `hris.wartle.app`) to the intended domain, or remove it if not using a custom domain.
- Replace/add marketing screenshots in `images/screenshots/` as desired.

## Local preview

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

then visit <http://localhost:8000>.
