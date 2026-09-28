# Knot & Cross Collective — Website

A responsive, polished static website for **Knot & Cross Collective**, prepared for GitHub hosting and the domain **knotandcross.co.za**.

## Included
- Premium single-page website with Home, About, Services, Our Work, Designer Incubation, Community, Vision/Mission and Contact sections.
- Supplied Knot & Cross logo, founder photos, garment images and workspace images.
- Responsive mobile/tablet/desktop navigation and layout.
- WhatsApp CTAs linked to **+27 63 631 2998**.
- Contact form configured with the free FormSubmit forwarding service to **Design@knotandcross.co.za**.
- `CNAME` already contains `knotandcross.co.za` for GitHub Pages.
- No npm/build step required.

## Publish to GitHub Pages
1. Upload the **contents of this folder** to the root of the GitHub repository.
2. Commit and push.
3. GitHub → **Settings → Pages** → deploy from the publishing branch → `/ (root)`.
4. Keep the included `CNAME` file.
5. At the domain registrar, use the current GitHub Pages DNS records displayed by GitHub for `knotandcross.co.za`. Do not use old IP records copied from random tutorials because GitHub can update them.
6. Enable HTTPS in GitHub Pages after DNS propagation.

## Contact form
The form posts to `https://formsubmit.co/Design@knotandcross.co.za`. FormSubmit may ask for a one-time activation/confirmation the first time the form is used. Complete that confirmation so future enquiries are forwarded.

If you later want to change providers, replace the form `action` and hidden fields in `index.html`. Good free alternatives include Web3Forms and Formspree.

## Email
The website does not create the mailbox itself. `Design@knotandcross.co.za` must exist with the email provider/hosting service used for the domain. The form forwarding service then delivers website enquiries to that mailbox.

## Before launch
- Confirm domain DNS and HTTPS.
- Submit a test contact form and complete any FormSubmit activation email.
- Test every WhatsApp link.
- Confirm the final founder names/photos and portfolio captions.
- Add a Privacy Policy / POPIA notice before collecting personal information at scale.
