# Google Auth Manager

[中文说明](README_CN.md)

---

Extract and backup your Google-authorized apps, with quick links to set up backup login methods.

## Features

- Extract authorized apps from Google permissions page
- 200+ services with login, settings, and security page URLs
- Bilingual (English / Chinese) interface
- Export backups as JSON or text
- Manual add for missing apps

## Why?

If you lose access to your Google account, you might not be able to log into services that only use "Sign in with Google". 

This tool helps you:
1. See all services linked to your Google account
2. Jump to each service's security settings
3. Set up email + password as backup login

## How to Use

1. Open [myaccount.google.com/connections](https://myaccount.google.com/connections)
2. Press `Ctrl+A` then `Ctrl+C` to copy the page
3. Paste into the text area, click "Parse"
4. Click the links to go to each service's settings

## Included Services (200+)

| Category | Examples |
|----------|----------|
| Productivity | Notion, Trello, Slack, Asana, Monday, Miro |
| Design | Figma, Canva, Adobe, Sketch, Framer |
| Development | GitHub, GitLab, Vercel, Docker, AWS, Firebase |
| Social | Discord, Twitter/X, LinkedIn, Reddit, Facebook |
| Entertainment | Spotify, Netflix, Steam, PlayStation, Nintendo |
| Shopping | Amazon, eBay, Airbnb, Uber, Booking |
| Cloud Storage | Dropbox, OneDrive, iCloud, MEGA |
| Learning | Coursera, Udemy, Duolingo, Codecademy |
| Finance | PayPal, Coinbase, Binance, Robinhood |
| AI Tools | ChatGPT, Claude, Midjourney, Perplexity |

## Privacy

- All data stays in your browser (localStorage)
- No data is sent to any server
- Open source

## License

MIT

## Contributing

Found a missing service? Submit a PR to add it to `database.js`.
