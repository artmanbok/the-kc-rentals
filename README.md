# The KC Rentals — Marketing Site

Static marketing site for **The KC Rentals** (host: Emmanuel), furnished stays near IUP in Indiana, PA.

## Live URL

**https://wandering-resonance-8434.zerodeploy.app**  
(See `DEPLOY.txt` for expiry notes and alternate tunnels.)

## Files

- `index.html` — landing page (hero, stays with photo galleries, `#book` Instant Book panel, why us, FAQ, contact)
- `book.html` — dedicated Instant Book page with all four Airbnb Instant Book links
- `styles.css` — mobile-first hospitality styles (DM Sans + Fraunces)
- `images/` — real property photos downloaded from the host’s Airbnb listings (compressed JPEG)

## Local preview

```bash
npx --yes serve /workspace/kc-rentals-site
```

## Contact

- Phone: (240) 422-7744
- Email: thekcrentals@gmail.com

## Bookings

Primary CTAs (`Book a stay`, hero **Book on Airbnb**, mobile sticky) go to `#book`.
Each stay card and the book panel link to Airbnb Instant Book:

- Modern 2BR: https://www.airbnb.com/rooms/1725747304300638396
- Furnished 2BR + EV: https://www.airbnb.com/rooms/1691664304254164466
