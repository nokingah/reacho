# Reacho

Collection of media site enhancement userscripts with generic branding for analysis and distribution.

## Scripts

- **media-sorter.js** - Album sorting by views/videos with SPA support
- **media-suite.js** - Full-featured media enhancement suite with download, filters, and infinite scroll
- **media-rotator.js** - Video rotation (90°) with fit-to-screen capabilities
- **media-suite-ultimate.js** - Premium media viewer with feed mode, downloads, and tracking

## Quick Start

1. Install [Tampermonkey](https://www.tampermonkey.net/) or similar userscript manager
2. Copy script content into new Tampermonkey script
3. Update `@match` URL patterns for your target site
4. Save and refresh the site

## Features

### Media Sorter
- Sort albums by views or video quantity
- SPA-safe with auto-reapply on content changes
- Stable sort order with original index tracking

### Media Suite
- Album filtering (by content type, view status)
- Video duration metadata and filtering
- Like count display and tracking
- Infinite scroll with rate-limit handling
- Responsive settings modal

### Media Rotator
- 90° rotation controls (left/right/reset)
- Maintains rotation in fullscreen
- Per-player rotation state

### Media Suite Premium
- Advanced feed viewer (desktop/phone layout)
- Smart downloading with ZIP compression
- Video player with timeline scrubbing
- Favorites tracking
- Auto-hide controls
- Keyboard navigation (j/k/space/d)

## Analysis Notes

These scripts are sanitized of site-specific branding for neutral code analysis. Original variable names and logic patterns are preserved to demonstrate:
- DOM manipulation and event handling
- State management and localStorage persistence
- Rate-limiting and error recovery
- SPA compatibility patterns
- Media extraction and processing
- UI framework integration
