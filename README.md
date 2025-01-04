# Vanilla JavaScript Tarot Reader

A beautiful, client-side tarot card reader using the Plateau Tarot API.

## Features

- Pure vanilla JavaScript - no dependencies required
- Beautiful mystical design with card flip animations
- Responsive layout that works on mobile and desktop
- Uses the Plateau Tarot API for card data and images
- Card flip animations and smooth transitions
- Upright and reversed card readings

## Setup

1. Clone this repository
2. Open `index.html` in a web browser

That's it! No server setup required.

## API Integration

This reader uses the Plateau Tarot API:
- Base URL: `https://geraldburke.com/apis/plateautarot/`
- Automatically fetches a shuffled deck using Fisher-Yates algorithm
- Displays card images hosted on the API server

## Card Data Structure

Each card contains:
```json
{
    "name": "The Devil",
    "arcana": "Major",
    "suit": "none",
    "description": "Feelings of entrapment surround you...",
    "rank": "15",
    "symbols": "Sex. Restrictions. Addiction.",
    "imageURL": "https://geraldburke.com/apis/plateautarot/images/The Devil.jpg",
    "cardBack": "https://geraldburke.com/apis/plateautarot/images/Card Back.jpg",
    "id": 16
}
```

## Credits

- Card details written by Josh Petty @ BrainJar Games
- Images by Luciella Elisabeth Scarlett from [RWS Tarot Cards](https://luciellaes.itch.io/rider-waite-smith-tarot-cards-cc0)
- API by Gerald Burke
- Frontend implementation by [Your Name]

## License

This project is released under the Unlicense - functionally CC0 or public domain.
Do what you want with it. Credit is appreciated but not required.

## Contributing

Feel free to:
- Open issues for bugs or feature requests
- Submit pull requests for improvements
- Fork and modify for your own projects
