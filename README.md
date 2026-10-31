# LAYA Health — First product: LAYA Sleep

A self-contained static landing page for **LAYA Health**, featuring its first offering, **LAYA Sleep**.

## Deploying on GitHub Pages

1. Under the `agh3000` GitHub account, create a **public empty repository** named `laya-health`.
2. Place the root files (`index.html`, `thanks.html`, `.nojekyll`, `README.md`) directly on its `main` branch.
3. Go to **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.
4. Expected public URL after deployment: `https://agh3000.github.io/laya-health/` (not live until GitHub Pages is configured).

The initial website highlights LAYA Sleep. Future offerings can be added under LAYA Health without changing the parent brand.

## Signups

GitHub Pages is static. The signup form deliberately does **not** accept submissions until an endpoint is configured. To enable it, configure a proper HTTPS provider (e.g., Formspree) with spam protection and a privacy policy, then set the `FORM_ENDPOINT` value in `index.html`. Do not request or store protected health information via this form.

## Status

LAYA Health and LAYA Sleep are working names, not trademark-cleared. The clinic and medical services are **pre-launch**. The illustrations are conceptual and do not depict actual patient data or current clinical services.