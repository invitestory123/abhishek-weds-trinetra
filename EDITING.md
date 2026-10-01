# Editing Guide — Dr Abhishek & Dr Trinetra Wedding Reception

Customer customization guide for `abhishek-weds-trinetra` (Bengali wedding invitation featuring cinematic curtain reveal video, authentic Bengali couple portraits, "Tenu Leke Main Jawanga" soundtrack, love story milestones timeline, scratch-to-reveal card, and Google Maps integration).

## Primary Customer Data

All text, dates, events, venue, and images live in:
- `editable/wedding-data.js`

### Current Configuration:
- **Couple Details**:
  - `couple.groom`: `"Dr Abhishek"` (Son of Mr Biswa Deb Mukherjee & Mrs Mitu Mukherjee)
  - `couple.bride`: `"Dr Trinetra"` (Daughter of Dr Tapas Kumar Barman and Dr Bijita Barman)
  - `couple.openingDate`: `"13 · December · 2026"`
  - `couple.heroDate`: `"13 · 12 · 2026"`
- **Countdown**:
  - `countdown.targetISO`: `"2026-12-13T19:30:00+05:30"` (7:30 PM)
- **Love Story & Milestones**:
  - `story.quote`: `"The best things in life are better shared with the people we love most."`
  - `story.message`: Invitation message from Mr. and Mrs. Mukherjee
  - `story.milestones`:
    - We Met: 9th March 2023
    - Engagement: 27th October 2024
    - Finally Tying Knots: 11th December 2026
- **Scratch-to-reveal Save the Date Card**:
  - `scratchCard.day`: `"Sunday"`
  - `scratchCard.date`: `"13"`
  - `scratchCard.monthYear`: `"December · 2026"`
  - `scratchCard.city`: `"Asansol"`
- **Events**:
  - `events[]`: Wedding Reception (`13 Dec 2026`, `7:30 PM onwards`, `Railway Officers Club, Asansol`)
- **Venue**:
  - `venue.name`: `"Railway Officers Club"`
  - `venue.addressLine1`: `"Domohani Railway Colony"`
  - `venue.addressLine2`: `"Asansol, West Bengal - 713303"`
  - `venue.cityTag`: `"Touch to explore · Asansol, West Bengal"`
  - `venue.mapsUrl`: `"https://maps.app.goo.gl/pTetwGBT4AHWF9W39"`
- **Music**:
  - Track: `Tenu Leke Main Jawanga` (`editable/assets/tenu-leke.mp3` — trimmed from 0:30 build-up)
  - Start Time: `0` (immediate playback)
- **Assets**:
  - `assets.video`: Opening curtain reveal (`editable/assets/sm.mp4`)
  - `assets.flowFrame`: Poster frame image (`editable/assets/flow-first-frame.webp`)
  - `assets.heroArt`: Bengali wedding couple illustration (`editable/assets/abhishek-trinetra-hero.webp`)
  - `assets.storyPhoto`: Bengali couple portrait (`editable/assets/abhishek-trinetra-story.webp`)
  - `assets.ogImage`: Social preview card (`editable/assets/abhishek-trinetra-og.jpg`)

## Testing

```bash
node --check editable/wedding-data.js
node --check assets/index-DLpsKpIv.js
```
Open in local browser.
