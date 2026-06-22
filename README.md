# DNS Records Cheat Sheet

A single-page visual cheat sheet for common DNS records, email authentication records, troubleshooting flow, and safer change checks.

The page is built as plain HTML and CSS in `index.html`, so it can be opened directly in a browser or hosted as a static site.

## What Is Included

- Common DNS record types: `A`, `AAAA`, `CNAME`, `MX`, `TXT`, `SPF`, `DKIM`, `DMARC`, `NS`, `CAA`, `PTR`, `SRV`, `SOA`, and `ALIAS`/`ANAME`
- Email security stack overview for `MX`, `SPF`, `DKIM`, and `DMARC`
- DMARC policy value guide
- SPF ending guide
- Common DNS mistakes and suggested fixes
- Basic troubleshooting flow for support tickets
- PowerShell `Resolve-DnsName` quick reference
- Golden rules for making DNS changes safely

## View Locally

Open `index.html` directly in a browser.

No build step, package install, or local server is required.

## Publish With GitHub Pages

This project is ready to publish as a static GitHub Pages site.

1. Push the contents of this folder to your GitHub repository.
2. In GitHub, open the repository settings.
3. Go to **Pages**.
4. Set the source to deploy from the main branch and root folder.
5. Save the setting and wait for GitHub Pages to publish the site.

Because `index.html` is at the repository root, GitHub Pages can serve it directly.

## Project Structure

```text
.
├── index.html
├── README.md
└── .gitignore
```

## Editing

All layout, styling, and content currently live in `index.html`.

For small wording changes, edit the relevant HTML section. For visual changes, edit the CSS inside the `<style>` block near the top of the file.

## Standards Referenced

The cheat sheet references core DNS and email authentication standards including SPF RFC 7208, DKIM RFC 6376, DMARC RFC 9989, DNS RFC 1034 and RFC 1035, RFC 2181, IPv6 AAAA RFC 3596, and CAA RFC 8659.

