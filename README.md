
# MagicHome v4 — Modern, Professional Magicbricks-Style Platform

## Run
npm install
npm run seed
npm run dev
Open http://localhost:5174

## What's in v4
- Modern blue theme, hero banner with featured city cards
- 10 cities × 5 localities × 10 flats = 500 apartments
- Each flat gets 6 images via Unsplash Source (bedroom, living room, kitchen, bathroom, balcony, exterior)
- Full flow: Apartment → Booking Form → Paytm QR (3s delay) → Success + PDF
- Owner KYC + post listing, Admin metrics, Reviews, Cancel/Refund

## Images
Images are fetched from Unsplash Source, using specific queries to ensure interiors/exteriors only.
This requires an internet connection; the browser caches images automatically.
