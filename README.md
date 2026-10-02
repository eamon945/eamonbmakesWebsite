# Eamon B Makes — GitHub Pages

Static recreation of the Wix portfolio site, structured for GitHub Pages.

## Before publishing

1. Add your real project images/video under `assets/images/`.
2. Replace the placeholder gallery blocks in the two project pages with `<img>` / `<video>` elements.
3. Put your final domain in the `CNAME` file at the repository root.
4. Push the folder to GitHub and enable Pages from the repository's Pages settings.

GitHub Pages supports custom domains. For an apex domain, GitHub currently documents A records pointing to:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

For `www`, use a CNAME pointing to `<your-github-username>.github.io`.

The current build deliberately uses plain HTML/CSS so there is no framework or build system to maintain.
