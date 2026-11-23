# Tri-State Detailing website

A single-page static website for Tri-State Detailing LLC.

- `index.html` is the whole page (no build step, no frameworks).
- `images/` holds the logo, SystemX logo and job photos.

## Preview locally
Double-click `index.html` to open it in a browser.

## Editing with Claude Code
Open this folder in Claude Code and describe the change, e.g.
"add a third photo to Recent Work" or "change the Basic Detail price to $210".

## Going live
Hosted on GitHub Pages at https://tristatedetailingllc.com.
The `CNAME` file tells GitHub Pages which domain to serve; don't delete it.

DNS records at the registrar:

| Type  | Host | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| AAAA  | @    | 2606:50c0:8000::153 |
| AAAA  | @    | 2606:50c0:8001::153 |
| AAAA  | @    | 2606:50c0:8002::153 |
| AAAA  | @    | 2606:50c0:8003::153 |
| CNAME | www  | jdfrancisco1.github.io |

## Brand notes
Green #01A450, black #111111, white. Headings in Barlow Condensed 800/900 italic, body in Inter.
Booking link: https://jobrail.net/b/tri-state-auto-detailing-llc
