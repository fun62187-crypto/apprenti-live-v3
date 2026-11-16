# Apprenti Live Tracker

An application pulse desk for UK sixth-form students (16-18) seeking apprenticeships:
searchable live listings, multi-filter tracking, saved applications and fast deadline signals.

## Stack

React 19 + TanStack Start (SSR) on Cloudflare Workers, Vite, Tailwind CSS v4, TypeScript, D1 migrations.

## Layout

- `app/src/routes` - pages, SEO routes and tracker styles
- `app/src/components` - UI components and primitives
- `app/src/layouts`, `app/src/hooks`, `app/src/lib` - shell, hooks and helpers
- `app/migrations` - database schema
- `app/public` - icons, presets and web manifest

## Run

```
cd app
bun install
bun run dev
```

## Notes

Brand: white #FFFFFF, slate #F8FAFC, charcoal #0F172A, blue #2563EB; statuses green #10B981, amber #F59E0B, red #EF4444.
Seed listings are unverified and labelled as such; browser-only state is never presented as aggregated community data.
