# Tajwri Altib Salla Theme

Luxury Arabic-RTL starter theme for Salla, built around the provided Tajwri Altib brand assets.

## Included

- `twilight.json` starter setup for Salla Twilight
- Branded homepage with RTL layout
- Shared header, footer, styles, and light JS interactions
- Minimal placeholder templates for the standard Salla page paths
- Localized copy in Arabic and English

## Structure

- `src/assets/images`: copied brand visuals from the provided asset pack
- `src/assets/styles/app.css`: global theme styling
- `src/assets/js/app.js`: mobile navigation and scroll behavior
- `src/views/layouts/master.twig`: shared layout
- `src/views/pages/index.twig`: branded homepage

## Notes

- This is a handcrafted starter bundle, not a full export from Salla CLI.
- The homepage is intentionally brand-led and mostly static so it can be imported safely before wiring live store data.
- Product, cart, blog, and account pages are included as lightweight placeholders and should be connected to live Salla variables/components during final integration.

## Next steps

1. Push this folder to a GitHub repository.
2. Import the repository from Salla Partners as a Twilight theme.
3. Replace placeholder links and sections with live store data or Salla built-in components as needed.
4. Preview with `salla theme preview` after connecting the bundle to your partner account.
