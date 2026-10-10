# Cookbox Cafe

A React/Vite demo ordering experience for Cookbox Cafe.

## Included flows

- Demo Google and email sign-in.
- Signed-in users are taken to their account dashboard when they select **Account** from the top or bottom navigation.
- Local demo profile, favourites, saved delivery details, and order history.
- Guest-friendly demo checkout with card, bank transfer, and USSD preview states.
- Basket persistence in `localStorage`.
- Basket clearing after a completed demo checkout or after a WhatsApp order is confirmed.
- Responsive mobile ordering shell with menu categories, search, journal, and admin preview.

## Run locally

```bash
pnpm install
pnpm dev
```

## Validate

```bash
pnpm check
pnpm build
```

> This project is a frontend demo. No real authentication, payment, order tracking, or customer database is connected.
