# Contact form

The contact page uses a secure, easy Netlify Forms setup with a honeypot field.

## Enable Netlify Forms

1. Deploy the site to Netlify.
2. Make sure the contact form exists on the built page.
3. Netlify will detect the form automatically.

## Spam protection

A hidden honeypot field is included (`bot-field`). Bots filling it are rejected.

## Template

The form is defined in:

- `themes/mikosch/layouts/_default/contact.html`

If you want a different form provider, replace the form markup in that file.
