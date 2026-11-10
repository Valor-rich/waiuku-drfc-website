# Waiuku District Rugby Football Club website

A responsive, static club website for Waiuku DRFC. This is a separate project from the XV Nation rankings repository; the XVN project is a reference for maintainable structure and data separation, not a source of Waiuku club data.

## Files
- `index.html` — page structure and club content
- `styles.css` — responsive visual system and layouts
- `script.js` — mobile navigation and dynamic footer year

## Preview / deploy

GitHub Pages publishing source: `main` branch, repository root (`/`).
This is a static site and can be hosted with GitHub Pages:
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and `/ (root)`, then save.
4. Wait for GitHub Pages to publish the site.

## Content notes
- Fixtures and results link to the Waiuku Rugby Xplorer club page: https://xplorer.rugby/waiuku-drfc
- General club contact shown: info@waiukudrfc.co.nz
- Club address shown: King Street, Waiuku, New Zealand
- Team categories are introductory placeholders pending confirmation of the current grades and team names.
- Sponsor profiles, club imagery, merchandise details, social links and a live fixture feed still need approved content/assets.

## XVN reference
The XV Nation project separates stable team metadata from match facts. The same principle should be followed if this site later gains structured team, sponsor or fixture data: keep club profile information separate from match records and avoid using team names as persistent identifiers.
