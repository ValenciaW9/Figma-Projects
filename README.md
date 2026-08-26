# Commons — Neighborhood Tool Share & Events

A mobile app concept that helps neighbors share tools and plan local events, all anchored to a single coordinate-based map. Instead of separate listings and calendars, everything nearby — a borrowable drill, a community garden cleanup — shows up as a pin you can walk to.

## Concept

- **Map home screen** — tool and event pins within a walkable radius, filterable by type
- **Tool listings** — photo, owner, distance, rating, and availability status
- **Event listings** — date/time, host, RSVP count, and any tools the event needs
- **Post flow** — drop a pin (or use current location) to list a tool or create an event
- **Profile & trust** — borrow history, hosted events, simple star ratings

## Design

Full interactive mockup: [View in Figma](https://www.figma.com/design/tBaPIID5zTgDfOAalFINEe)

Palette: deep forest green (tools), warm clay (events), soft cream background — a warm, grounded, "neighborhood notice board" feel rather than a generic map app look.

`/design` — exported screens from the Figma file

## Prototype

`/prototype` — a working React demo (`commons-app-prototype.jsx`) covering:
- Map view with tappable tool/event pins and a detail sheet
- Browse view (flat list of nearby tools and events)
- Post flow entry screen

Built with React + [lucide-react](https://lucide.dev) icons. Drop into any React + Tailwind-less environment — all styling is inline for portability.

## Status

Concept and prototype stage — not yet connected to a backend or real geolocation data.
