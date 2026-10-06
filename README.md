# Beanora – Premium Coffee & More

A modern, responsive coffee shop landing page built with plain HTML, CSS and JavaScript. No frameworks, no build step.

**Created by Jagdish Maliwad**

## Features

- Hero section with animated steam, floating cup and drifting coffee beans
- Signature Drinks cards (Caramel Latte, Cappuccino, Cold Brew) with **Order Now** buttons
- **Order Tea** button (top right) that opens a tea menu panel with six teas
- Shared order cart with a running item count and total
- Our Story banner and mobile app section with App Store / Google Play buttons
- **Book Your Cozy Spot** appointment form: name, email, date, time, guests, occasion, coffee or tea preference, and message, with validation and a booking confirmation
- Fixed Beanora logo that scrolls back to the top
- Scroll-reveal animations, hover effects and button shine
- Responsive layout for desktop, tablet and phone
- Respects the "reduce motion" setting

## Getting started

1. Download `index.html`. All images are embedded in the file, so nothing else is needed.
2. Open it in any modern browser.

## Project structure

```
index.html   # the full site: markup, styles, scripts and images
README.md    # this file
```

## Customising

| What | Where |
|------|-------|
| Drink names and prices | the `.card` blocks in the "Signature Drinks" section |
| Tea menu | the `teas` array in the script at the bottom of `index.html` |
| Colours | the CSS variables in `:root` at the top of the `<style>` block |
| Booking time slots | the time loop under `// Booking form` in the script |

## Notes

- The booking form and cart run in the browser only. Bookings and orders are not saved or sent anywhere. Connect the form to an email service or backend to receive real bookings.
- Fonts (Playfair Display, Caveat, Poppins) load from Google Fonts, so an internet connection is needed to see them.

## Author

**Jagdish Maliwad**

© 2026 Jagdish Maliwad. All rights reserved.
