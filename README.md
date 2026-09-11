# Travello

Travello is a responsive travel-booking interface prototype for exploring destinations, tour cards, and a detailed Dubai itinerary.

## Core features

- Featured destination and tour-package cards with durations, ratings, itineraries, and displayed prices.
- Detailed trip page with gallery, duration and route selectors, highlights, itinerary, reviews, and package information.
- Login/register, currency picker, search, callback request, and enquiry interface components.
- Tourism-board content and responsive navigation.
- Animated interactions built with Framer Motion.

## Technology stack

- Next.js 14 and React 18
- JavaScript and JSX
- Tailwind CSS and Radix UI
- Framer Motion and Lucide icons

## Prerequisites

- Node.js 20 or newer
- npm (a `package-lock.json` is included)

## Local setup

```bash
git clone https://github.com/varunisrani/travello.git
cd travello
npm ci
npm run dev
```

The development server is available at `http://localhost:3000` by default.

To create and serve a production build:

```bash
npm run build
npm run start
```

The manifest also defines `npm run lint`.

## Configuration

The current source does not read any environment variables.

## Project structure

```text
src/app/          Primary App Router pages and global styles
src/components/   Tour listing, booking detail, navigation, forms, and UI primitives
src/lib/          Shared styling utility
app/              Additional legacy/duplicate App Router pages
public/           Static assets
```

## Status and limitations

This is a static front-end prototype. Tour listings, reviews, prices, and itineraries are embedded in components; search, login, registration, callback, and enquiry forms are not connected to a backend or payment/booking system. Several images are loaded from third-party hosts, and the repository contains overlapping `app/` and `src/app/` page trees.