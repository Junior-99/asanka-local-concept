# Asanka Local — independent website concept

Uncommissioned React website for a technology content series. **Not affiliated with or endorsed by Asanka Local.** No orders, bookings or payments are accepted.

## Run and deploy

Node 22+: `npm ci`, `npm run dev`. Build: `npm run build`. Output: `dist`. Vercel Vite preset or GitHub Pages static hosting; relative base supports both.

## Business problem and working features

Potential guests must piece together dish explanations, locations and contact details. A structured group-meal plan collects party size, date, branch and preferred dishes before a conversation.

- Searchable, filterable the food guide and working shortlist.
- Domain-specific meal plan builder collecting Number of guests, Preferred location, Preferred date, Meal arrangement.
- Plain-text download, persistent local records, editable status, search and filter dashboard, JSON export.
- Original true WebGL the asanka bowl, scroll rotation, drag interaction, lazy loading, offscreen render suspension, reduced-motion support and image fallback.
- Responsive, keyboard accessible interface; semantic forms and native modal focus handling.

## Dashboard limits

The local planner uses browser localStorage. The separate shared concept inbox uses authenticated Supabase access. No real business transactions or automatic business notifications occur. Do not store confidential information. Back up using export. Counts use actual saved records and start at zero. A saved plan is not a confirmed order or reservation.

Before official business use: obtain business approval and asset rights, confirm current details, replace illustrative content, add authenticated backend and notifications, configure owner access, and verify operational policies.

## Research and media

Checked 21 October 2026. Website status: No current standalone official website verified. Facebook is linked as the website by Restaurants10. A historical GhanaYello listing mentions asankaghana.com; its current status was not established. Do not claim they never had a website.

- https://www.facebook.com/AsankaLocalGH/ — linked public business profile inspected in Chrome
- https://www.citylifeaccra.com/restaurant-accra-listings/asanka-local
- https://www.restaurants10.com/GH/Accra/856482820882054/Asanka-Local
- https://www.ghanayello.com/company/1009/Asanka_Locals

Primary linked presence: https://www.facebook.com/AsankaLocalGH/

`public/social.webp`: Public Facebook cover photo · Asanka Local. Source: https://www.facebook.com/photo/?fbid=122096491209108886&set=a.122096491485108886. Rights remain with their owners; permission for reuse is not established.

`public/hero.webp`: generated using the built-in imagegen tool. Premium appetizing editorial photograph of a traditional dark earthenware asanka bowl with rich Ghanaian red red black-eyed bean stew, golden fried ripe plantain and fried fish, warm terracotta tabletop, tactile linen, late sun, no text or logos; illustrative, not a photographed restaurant dish.

All generated imagery and procedural 3D models are illustrative, not evidence of actual products, completed work or food served. No fabricated testimonials, sales or live availability. Business claims are sourced; proposed workflows are design inferences.

## Checks

Production build and dependency audit. Browser QA results and deployment URLs are recorded in the series content document. A passing build does not establish production backend readiness.

## Shared concept inbox

The public planner can optionally send a copy to the creator’s demonstration inbox after an explicit consent checkbox. This does not send anything to the real business. A shared Supabase backend provides bounded, validated submissions; anonymous users cannot read private records. Approved verified accounts can read their assigned sites, update statuses and internal notes, search, paginate and export records. Database policies enforce site membership; browser filtering alone is not trusted. The frontend includes only a publishable key. No service-role key is present.

Creator onboarding: open Dashboard, choose Register, create a password yourself, verify the account email, then sign in. The specifically approved creator email has been allowlisted privately. Other accounts receive no access by registering. The database isolation checks passed, but the creator’s email/password onboarding cannot be completed or verified until the user performs it. All sites remain uncommissioned concepts pending owner approval and operational handover.

Schema and rollback-based security tests are retained in the main workspace backend folder. The backend project was quoted at $0/month; no paid plan was selected. Usage limits and provider policies still apply.
