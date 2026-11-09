# Golf Club TV — landing pubblica

Pagina "in arrivo" per il pubblico: spiega cos'è Golf Club TV e raccoglie le email di chi vuole essere avvisato al lancio.
Un unico file statico (`index.html`), nessuna build: si pubblica con GitHub Pages, Netlify, Vercel o qualsiasi hosting statico.

- Lingua: italiano di default, pulsante IT/EN in alto (link diretto in inglese: `?lang=en`).
- Configurazione (in fondo a `index.html`):
  - `CONTACT_EMAIL` — email per i creator e per i contatti.
  - `SIGNUP_ENDPOINT` — URL di un servizio che raccoglie le iscrizioni (es. Formspree, Brevo, Mailchimp). Se vuoto, il form "Avvisami" apre una email verso `CONTACT_EMAIL`.
