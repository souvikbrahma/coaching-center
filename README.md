# Fly High Academy website

Single-page website for **Fly High Academy**, a defence entrance and SSB interview coaching centre in New Town, Kolkata, led by Gp Capt Kaushik Sinha (Retd), Ex-GTO.

## What's on the page

- Hero with the academy's tagline, Google rating (5.0, 142 reviews) and calls to action
- Mentor section
- Programs: SSB Interview, NDA Written + SSB, CDSE & AFCAT Written, PABT / CPSS, Sainik School / RIMC / RMS, Spoken English & Personality
- The five-day SSB procedure, with how the academy trains for each day
- Excerpts from public Google reviews
- Enquiry form, address, hours and contact links

## Enquiry form

On submit, the form validates name and phone, then opens a WhatsApp message to **+91 91637 22921** with the enquiry pre-filled. No server is required.

When the page runs as a claude.ai artifact, it also saves enquiries to the artifact database and shows the owner an "Enquiries received" table. Outside claude.ai that code does nothing. To store leads on your own host, add a `fetch()` to your backend or CRM inside the form's submit handler in `index.html`.

## Files

```
index.html   the whole site (HTML, CSS, JS in one file)
img/         images generated with OpenArt (Kling 3 Omni)
```

## Run or deploy

Open `index.html` in a browser, or serve the folder from any static host (GitHub Pages, Hostinger, Netlify). No build step.

## Before going live

- `img/mentor.jpg` is AI-generated. Replace it with a real photo of Gp Capt Sinha.
- Confirm the founding year ("since 2022", from Justdial) and the list of SSB boards with the academy.
