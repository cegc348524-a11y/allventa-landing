# Allventa Óptica — Project Plan

## Approved scope

Create a Spanish-language, responsive, single-page website for Allventa Óptica using the user's supplied HTML as the content and visual reference. The user approved building it in the current workspace and retaining the WhatsApp number and branch details shown in that reference. Because `index.html` is an existing directory/reparse point, the user approved creating `allventa-optica.html` at the workspace root instead and preserving that existing path unchanged.

## Audience and purpose

Help prospective customers in Caracas learn about the optical center's clinical services and locations, and contact the business to request an appointment through WhatsApp.

## Page structure

- Header with the supplied Allventa logo, the slogan “Hoy verás bonito,” and responsive navigation.
- Hero introducing the visual diagnosis center and appointment/contact calls to action.
- Promotional ribbons for the frames offer and photochromic single-vision lenses with Blue or AR, each followed by a supplied image.
- Clinical services: OCT, ocular ultrasound, and comprehensive vision exam, with a supplied clinical image.
- Sections titled “Nuestros optometristas” and “Nuestras oftalmólogas”; add named staff profiles only after names and credentials are supplied.
- Frames and lenses information based on the supplied copy, with the supplied video converted to silent local formats; no unverified brand names.
- Educational section explaining digital multifocal lenses, adaptation, and a WhatsApp contact link.
- Partner section showing the user-supplied Novak, Rodenstock, and Liberty logos.
- Two location cards: CC Galerías El Recreo and CC Propatria (Nivel 4, al lado del SAREN), with their supplied opening hours.
- Footer and a floating WhatsApp contact link.

## Technical approach

- Static HTML and CSS in `allventa-optica.html`, with the supplied logo in `assets/allventa-logo.png`; no backend, database, build tool, or mock data.
- Use semantic landmarks, keyboard-visible focus, mobile navigation, meaningful accessible names, valid in-page anchors, and safe attributes for links opened in a new tab.
- Preserve the provided WhatsApp contact number and branch copy. Verify business details before publishing.

## Out of scope

- Booking forms, payments, analytics, backend/API integrations, and deployment.
- Unverified brands, medical claims, or additional contact information.
