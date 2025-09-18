# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML brand dashboard for MagnaPharm pharmaceutical products. The project consists of individual HTML pages for different pharmaceutical brands (Bronchostop, Caffetin, Co-lactase, Familia Guard, Fervex, Sargenor, Upsavit) with a central index page that serves as the main hub.

## Architecture

- **Static HTML Structure**: Pure HTML/CSS/JavaScript implementation with no build system
- **Styling**: Uses Tailwind CSS via CDN with custom CSS for animations and brand-specific styling
- **Fonts**: Google Fonts (Inter family) loaded via CDN
- **Layout**: Responsive design with mobile-first approach using Tailwind utilities
- **Navigation**: Central hub (index.html) with individual brand pages accessible via branded cards

## File Structure

- `index.html` - Main brand hub with navigation cards to individual brand pages
- `[brand-name].html` - Individual brand dashboard pages (bronchostop.html, caffetin.html, etc.)
- `README.md` - Basic project description

## Key Design Patterns

- **Brand Cards**: Consistent hover effects with translateY animations and color-coded branding
- **Accordion Components**: Expandable sections used in brand pages for organizing content
- **CSS Custom Properties**: Used for dynamic brand color theming on hover states
- **Fade-in Animations**: CSS keyframes for smooth page load transitions

## Working with Brand Pages

Each brand page follows a similar structure:
- Brand-specific color scheme defined in CSS custom properties
- Accordion-style content organization
- Consistent navigation back to the main hub
- Responsive grid layouts for content sections

## Development Notes

- No package.json or build process - changes can be made directly to HTML files
- All dependencies loaded via CDN (Tailwind CSS, Google Fonts)
- Romanian language content (`lang="ro"`)
- Mobile-responsive design using Tailwind's responsive utilities