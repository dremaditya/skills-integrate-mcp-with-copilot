# Draft issues: Front-end enhancements inspired by Rohan's portfolio

This file contains drafted GitHub issues for front-end/content improvements inspired by the external portfolio we reviewed. Each entry includes a title, a short description, and a quick link to open the issue in GitHub (click the link to prefill title+body).

---

## 1) Integrate Bootstrap & FontAwesome
**Description:** Add Bootstrap and FontAwesome to `src/static/index.html` and update `src/static/styles.css` to use Bootstrap grid and utilities. This will simplify responsive layout and provide icon assets for contact and social links.

Quick-create: https://github.com/dremaditya/skills-integrate-mcp-with-copilot/issues/new?title=Integrate%20Bootstrap%20%26%20FontAwesome&body=Add%20Bootstrap%20and%20FontAwesome%20to%20the%20project.%20Update%20`src/static/index.html`%20to%20include%20Bootstrap%20CSS%20and%20FontAwesome%20and%20refactor%20`src/static/styles.css`%20to%20use%20Bootstrap%20utilities.%0A%0AWhy:%20Simpler%20responsive%20layout%20and%20icon%20support.%0A%0AFiles%20to%20change:%0A- src/static/index.html%0A- src/static/styles.css

---

## 2) Add hero / profile / projects sections
**Description:** Add a hero with background image and new sections: Profile/About, Projects showcase, and a styled Projects area similar to Rohan's portfolio. Use Bootstrap containers/columns for layout.

Quick-create: https://github.com/dremaditya/skills-integrate-mcp-with-copilot/issues/new?title=Add%20Hero%20%2F%20Profile%20%2F%20Projects%20Sections&body=Add%20a%20hero%20section%20with%20background%20image%20and%20create%20`Profile`%20%2F%20`Projects`%20sections.%20Use%20Bootstrap%20grid%20for%20layout%20and%20placeholders%20for%20project%20images.%0A%0AFiles%20to%20change:%0A- src/static/index.html%0A- src/static/styles.css%0A- add%20images/%20assets

---

## 3) Project showcase with hover overlay effects
**Description:** Implement project cards with overlay/hover effects (e.g., `figure.effect`) showing title, tags, and link to demos. Add related CSS transitions/animations.

Quick-create: https://github.com/dremaditya/skills-integrate-mcp-with-copilot/issues/new?title=Add%20Project%20Showcase%20with%20Hover%20Overlay%20Effects&body=Implement%20project%20cards%20with%20hover%20overlay%20effects%20(similar%20to%20`figure.effect`).%20Include%20images%2C%20titles%2C%20tags%2C%20and%20links%20to%20demos.%0A%0AFiles%20to%20change:%0A- src/static/index.html%0A- src/static/styles.css%0A- add%20images/%20assets

---

## 4) Add Contact section with `mailto:` and social links
**Description:** Replace or augment the footer with a Contact section that includes `mailto:` email, LinkedIn, and other social links using FontAwesome icons. Ensure links open in new tabs where appropriate.

Quick-create: https://github.com/dremaditya/skills-integrate-mcp-with-copilot/issues/new?title=Add%20Contact%20Section%20with%20mailto%20and%20Social%20Links&body=Add%20a%20Contact%20section%20with%20`mailto:`%20email%2C%20LinkedIn%2C%20and%20other%20social%20links.%20Use%20FontAwesome%20icons%20and%20make%20links%20open%20in%20new%20tabs.%0A%0AFiles%20to%20change:%0A- src/static/index.html%0A- src/static/styles.css

---

## 5) Fix asset path separators and image availability
**Description:** Normalize image paths to use forward slashes (`images/...`) in all HTML/CSS, add missing images to `src/static/images/`, and ensure all references work cross-platform and in deployments.

Quick-create: https://github.com/dremaditya/skills-integrate-mcp-with-copilot/issues/new?title=Normalize%20Image%20Paths%20and%20Add%20Missing%20Assets&body=Replace%20backslash%20path%20separators%20with%20forward%20slashes%20in%20HTML%20and%20CSS.%20Add%20required%20images%20to%20`src/static/images/`%20and%20verify%20asset%20loading%20locally%20and%20in%20deployments.%0A%0AFiles%20to%20change:%0A- src/static/index.html%0A- src/static/styles.css%0A- add%20src/static/images/

---

## 6) Improve typography: Add Open Sans (Google Fonts)
**Description:** Add Open Sans via Google Fonts or `@font-face` to improve typography; update headings/body fonts in `src/static/styles.css`.

Quick-create: https://github.com/dremaditya/skills-integrate-mcp-with-copilot/issues/new?title=Add%20Open%20Sans%20Typography%20and%20Improve%20Fonts&body=Add%20Open%20Sans%20(via%20Google%20Fonts%20or%20`@font-face`)%20and%20update%20`src/static/styles.css`%20to%20use%20it%20for%20headings%20and%20body.%0A%0AFiles%20to%20change:%0A- src/static/styles.css

---

### Next steps
- Click any quick-create link above to open a prefilled GitHub issue and submit it.
- If you want, I can automatically open these issues for you (requires repository issue-creation permissions in the connected account). Alternatively I can file these as committed files; let me know which you prefer.
