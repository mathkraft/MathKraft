# MathKraft website

A complete static site. No installation, build tools, subscriptions, or API keys are required. The header uses a text-only MathKraft wordmark. The banner and simple plus-sign favicon are original SVG vector artwork. All assets and fonts are local/system-based; the only external service loaded by the site is your embedded Google Form.

## Files
- index.html — page text and embedded form
- styles.css — layout, colors, and mobile styles
- assets/banner.svg — geometric hero banner
- assets/favicon.svg — browser icon

## Preview
Open index.html in a browser, keeping the other files alongside it. You need an internet connection for the Google Form. The form can also be opened using the link above it. Its submission flow has not been independently tested here; no test responses were sent.

## Upload to GitHub Pages
1. Unzip this download.
2. Open your MathKraft repository on GitHub. Choose Add file → Upload files.
3. Upload the CONTENTS of this folder, including the assets folder. index.html and styles.css must be at the repository root, not inside an extra mathkraft folder. Commit the files.
4. Open Settings → Pages. Under Build and deployment, choose Deploy from a branch, select your main branch and /(root), then Save. If your repository uses another default branch, select that instead. Pages availability for private repositories depends on your GitHub plan.
5. Wait for GitHub to display the published URL. Open that URL and check both the page and form on your phone.

All asset references are relative, so the page works at a project URL or at your custom domain. No CNAME file is included: first test the default GitHub Pages URL, then configure mathkraft.com in Settings → Pages and follow GitHub's current DNS instructions at GoDaddy. Enforce HTTPS when it becomes available. There is no need to change your separate personal website.

Current official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

GitHub Pages has restrictions on hosting online businesses and sites primarily facilitating commercial transactions. Confirm suitability for your circle before launch. These same files also work on a static host such as Netlify with no code changes.

## Editing
Edit visible text in index.html. Venue, schedule, and start date are intentionally unconfirmed. The expected fee is approximately $5. No session length, group size, or registration commitment is promised.

Adjust the iframe height in styles.css if your form is longer or shorter (desktop 1500px; mobile 1700px). Google's embedded form may scroll independently; use the always-visible new-tab link as a fallback. The website does not store form responses; access them through your own Google Forms account. Changes to questions within the same Google Form appear automatically.

The square puzzle uses a built-in HTML disclosure element and works without JavaScript. The layout includes keyboard focus styles, a skip link, semantic headings, reduced-motion support, and responsive sizing.
