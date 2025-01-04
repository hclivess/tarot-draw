# Vanilla JavaScript Tarot Reader

A beautiful, client-side tarot card reader with support for multiple traditional spreads.

## Features
- Pure vanilla JavaScript - no dependencies required
- Beautiful mystical design with card flip animations
- Responsive layout that works on mobile and desktop
- Three traditional spread types:
  - Single Card Draw for quick readings
  - Three Card Spread (Past/Present/Future)
  - Celtic Cross (10-card comprehensive reading)
- Upright and reversed card readings
- Sequential card flip animations
- Built-in card database for offline use
- Custom grid layouts for each spread type

## Setup
1. Clone this repository
2. Get the card images from [RWS Tarot Cards](https://luciellaes.itch.io/rider-waite-smith-tarot-cards-cc0)
3. Place the card images in the `images` folder
4. Open `index.html` in a web browser

That's it! No server or internet connection required.

## Card Data Structure
Each card contains:
```json
{
    "name": "The Devil",
    "arcana": "Major",
    "suit": "none",
    "description": "Feelings of entrapment surround you...",
    "rank": "15",
    "symbols": "Sex. Restrictions. Addiction."
}
```

## Spreads Available

### Single Card
- Quick daily guidance
- Simple yes/no questions
- Daily meditation focus

### Three Card Spread
- Past/Present/Future layout
- Mind/Body/Spirit readings
- Situation/Action/Outcome analysis

### Celtic Cross
1. Present Situation
2. Challenge/Crossing
3. Foundation
4. Recent Past
5. Possible Outcome
6. Immediate Future
7. Your Influence
8. External Influences
9. Hopes and Fears
10. Final Outcome

## Credits
- Card details written by Josh Petty @ BrainJar Games
- Images by Luciella Elisabeth Scarlett from [RWS Tarot Cards](https://luciellaes.itch.io/rider-waite-smith-tarot-cards-cc0)
- Frontend implementation by HCLivess

## License
This project is released under the Unlicense - functionally CC0 or public domain.
Do what you want with it. Credit is appreciated but not required.

## Contributing
Feel free to:
- Open issues for bugs or feature requests
- Submit pull requests for improvements
- Fork and modify for your own projects

## Acknowledgments
This project was inspired by the traditional Rider-Waite-Smith tarot deck and various online tarot applications. The goal was to create a simple, beautiful, and fully offline tarot reading experience.
