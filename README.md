# RideVanta Website — GitHub Pages

A responsive, single-page static website for RideVanta transport and taxi enquiries.

## Publish on GitHub Pages
1. Create a new public GitHub repository named `ridevanta`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. GitHub Pages will show the published URL after deployment.

## Required setup before publishing
Open `index.html` and edit the two constants near the bottom:
- `RIDEVANTA_WHATSAPP = "91XXXXXXXXXX"` — replace with your WhatsApp Business number including country code, digits only.
- `RIDEVANTA_EMAIL = "hello@ridevanta.in"` — replace with your real business email.

The booking and partner forms open WhatsApp with a prefilled enquiry. They do not store data or confirm rides automatically. This launch version does not include live availability, fare calculation, payment processing, customer accounts, driver dispatch or a database.

## Custom domain
After buying a domain, configure it in **Settings → Pages → Custom domain** and add the DNS records GitHub provides. Do not guess DNS values; use the values shown by GitHub for your domain.

## Before accepting real bookings
Confirm your business model and applicable transport/aggregator legal requirements with a qualified professional and relevant state authority. Verify operator/vehicle/driver documents and communicate that a booking is confirmed only after manual confirmation.
