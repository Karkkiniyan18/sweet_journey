# Sweet Journey Website

A responsive static website inspired by the provided modern furniture/Shopify theme reference, adapted for a chocolate-wrapper business.

## Pages

- `index.html` — Demo login page
- `home.html` — Home page with 9 image frames
- `orders.html` — Order creation form + browser localStorage demo
- `contact.html` — WhatsApp, Instagram, reference image frame and business details
- `prices.html` — Wrapper pricing cards

## How to run

1. Extract the ZIP.
2. Open `index.html` in your browser.
3. Use any username and password on the demo login page.
4. Replace the placeholder frames with your images.
5. Update the sample WhatsApp numbers, Instagram ID and prices.

## Adding images

Replace a placeholder such as:

```html
<div class="image-placeholder">
  <span>IMAGE 01</span>
</div>
```

with:

```html
<div class="image-placeholder">
  <img src="assets/your-image.jpg" alt="Chocolate wrapper sample">
</div>
```

Then add this CSS if needed:

```css
.image-placeholder img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

## Important

This is a front-end demo. Login and order saving use browser `localStorage`; they are not secure authentication or a real database. For production, connect a backend such as Flask, Firebase, Supabase or MongoDB.


## Updated version
- Login now asks for Gmail address and mobile number.
- The three supplied reference images are included in `assets/`.
- The home hero, first three gallery cards and contact reference frame use the supplied images.
