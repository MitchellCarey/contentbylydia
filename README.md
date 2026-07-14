# ContentByLydia landing page

Public landing page for the Made to Market founding waitlist.

## Preview locally

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Structure

- `index.html`: page content and metadata
- `styles.css`: responsive design system and layout
- `script.js`: navigation, reveal effects, FAQ and form behaviour
- `assets/`: local brand imagery

## Waitlist integration

The form currently provides client-side validation and a demonstration success state. Connect the submit handler in `script.js` to the chosen email platform before using the page to collect live sign-ups.
