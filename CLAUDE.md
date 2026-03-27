# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static single-page website for Kalla LLC, a licensed esthetician business. No build tools, frameworks, or dependencies — just a single `index.html` and `favicon.svg`.

## Development

To preview locally, serve `index.html` with any static file server, for example:

```bash
python3 -m http.server 8080
# or
npx serve .
```

## Architecture

- **Single file:** All HTML, CSS, and JS lives in `index.html` — no separate stylesheet or script files.
- **Booking integration:** The CTA button links to an external Phorest booking system.
- **Design tokens (inline CSS variables):**
  - Background: `#0f0e0e`
  - Surface: `#1a1718`
  - Accent: `#b8899a` (rose/mauve)
  - Mobile breakpoint: `480px`
