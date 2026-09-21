# paper-aisle-invitation

A FreeWebStore template for **business.lifestyle** by **@Aa11rn**.

# The Paper Aisle — Digital Baat Pakki Invitation

A mobile-first digital wedding invitation card built on the Week 9 Paper
Aisle studio design: ivory and plum surfaces, mauve and champagne accents,
elegant Cormorant Garamond typography, and SVG-only ornament.

## Features

- Tap-to-unlock opening wax seal with a one-time welcome
- Mock music toggle (Music / Pause state + toast; a real track plugs in at launch)
- Scratch-to-reveal ceremony date — finger, cursor, or tap/Enter
- Live threading countdown with compact hero ticker
- Four-moment program timeline with times
- Venue card with Google-Maps button
- Dress-code note with colour-palette swatches
- Three pre-wedding event cards with map links
- RSVP form: name + email + attending choice + party size, with loading,
  success, duplicate-reply, and reset states and a persisted confirmed-guest
  counter + social-proof avatar stack
- Add-to-my-calendar `.ics` export with a clipboard fallback
- Closing arch with couple names and date · venue
- Toast notifications, bottom RSVP bar, and back-to-top
- Scroll-reveal animations with prefers-reduced-motion support
- Fully slot-annotated (`data-fws-slot`) for FreeWebStore content editing

## Included Files

```
paper-aisle-invitation/
├── index.html            # Main template page
├── package.json          # Node dependency file (FWS CLI)
├── template.config.json  # FWS template metadata
├── tailwind.config.js    # Tailwind design tokens reference
├── preview.png           # Template preview image (add your own)
└── README.md             # This file
```

## Customization

All editable content regions are marked with `data-fws-slot` attributes.
Couple names, parents, ceremony type, date, venue, and event details all
carry slots — a real couple swaps in without touching code. Edit these
directly in the HTML or via the FreeWebStore editor after publishing.
See `slots.md` for the slot reference used by this template.

## Publishing

```sh
npx @freewebstore/cli doctor     # local validation
npx @freewebstore/cli login      # one-time GitHub App install
npx @freewebstore/cli publish    # upload + create repo + queue for review
```

## License

MIT (auto-set by `fws init`). FreeWebStore requires MIT for community
templates — see CONTRIBUTING.md in the platform docs for the why.
MIT — see `template.config.json` for details.