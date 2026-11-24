# CLAUDE.md

- `npm run dev` starts Vite, `npm run build` type-checks with `vue-tsc -b` and builds. No tests or linter; unused locals fail the build.
- Single page, no router, no backend. `src/data.ts` holds all content (illustrative), `src/reservation.ts` the booking state, `src/demo.ts` the link to the services page.
- **Plate discs** (`src/data.ts`): `width` / `left` / `top` centre the round plate of each photo in the disc. A new photo must be a plate shot from above and needs its own values. Dishes without a photo use a colored label (`vinyl`).
- Closed on Mondays, lunch only on Sundays; dates are computed from today.
- The restaurant does not exist: no reviews or awards, keep the demo notice, never connect the form to a real third party. See `PRODUCT.md`.
