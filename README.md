# LuHuangMSFT.github.io

A simple professional calling card for Lu Huang, built with plain HTML and CSS.
There are no dependencies, scripts, external fonts, analytics, or build step.
The design uses a charcoal background, bold sans-serif typography, and cool-blue
accents, with a responsive layout and a visible keyboard focus indicator.

## Content

The homepage is `index.html`; its styles are included in the same file.
`favicon.svg` supplies the browser icon.

The name and introduction are editable draft copy, not a confirmed biography:

- **Name:** Lu Huang
- **Tagline:** Building the Web.
- **Introduction:** Find my work and connect with me on GitHub.
- **Profile:** <https://github.com/LuHuangMSFT>

Edit the visible copy, page title, and description in `index.html` together.

## Preview

Open `index.html` directly in a browser. Everything needed to render the page is
local, so no server or package installation is required.

## GitHub Pages

The root `index.html` is a standalone homepage compatible with GitHub Pages'
default Jekyll build; it does not need a theme or layout. When included in the
configured Pages source, it takes precedence over the README-generated homepage.
The existing `_config.yml` retains its `.well-known` include for verification
files, and `nc_test.html` is left unchanged.

GitHub Pages is currently configured to publish `main` from `/ (root)`, with HTTPS
enforced. No hosting configuration changes are needed. This implementation does
not change Pages settings, add a deployment workflow, or publish the feature
branch. The live site only changes when the homepage reaches the configured
publishing branch.