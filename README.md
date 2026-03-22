# skills-restaurant

Claude Code skill suite for restaurant owners, managers, and chefs. Four skills, one install.

## Install

```bash
npx @gonzih/skills-restaurant
```

Or install as a dev dependency and skills are copied automatically on `postinstall`:

```bash
npm install @gonzih/skills-restaurant
```

Restart Claude Code after installing.

## Skills

### `/menu-description-writer`
Write enticing menu descriptions for any dish. Provide the dish name, key ingredients, prep method, and any notes — get back sensory-rich copy ready for your menu.

### `/catering-proposal`
Generate a full catering proposal: event overview, tiered menu packages, per-head pricing, staffing plan, event-day timeline, and terms. Ready to send to clients.

### `/staff-schedule-email`
Produce a weekly staff schedule email with shift assignments by day and role, coverage notes, key reminders, and swap instructions.

### `/review-response`
Respond professionally to online reviews (Google, Yelp, TripAdvisor). Works for both positive and negative reviews — thanks the guest, addresses specifics, and invites them back.

## Usage examples

```
/menu-description-writer Pan-seared duck breast, cherry gastrique, roasted beets, microgreens
/catering-proposal Corporate dinner, 80 guests, June 14, rooftop venue, $95/head budget
/staff-schedule-email Week of June 9, [paste staff list and shifts]
/review-response [paste review text]
```

## License

MIT
