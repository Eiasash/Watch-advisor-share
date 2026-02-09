# Style Compass v3.3

A smart, mobile-first outfit recommendation app with AI-powered features, mood tracking, and style analytics.

**[Launch App](https://eiasash.github.io/Watch-advisor-share/)**

## Features

### Core
- **5 Vibe Modes** - Casual, Formal, Date Night, Sporty, Creative
- **Outfit Recommendations** - Curated outfits with match scores, weather adjustments, and search/sort
- **Outfit of the Day** - Daily curated pick that changes each day
- **AI Critique** - Get fashion expert analysis powered by Claude API
- **Outfit Composite** - Generate and save shareable outfit images

### Wardrobe
- **Custom Wardrobe** - Add your own clothing items manually
- **Batch Image Upload** - Drop photos for AI auto-recognition of type, color, material, pattern, and season
- **Duplicate Detection** - Fuzzy matching prevents duplicate wardrobe entries
- **Custom Outfit Generator** - Create outfits from your personal wardrobe

### Tracking & Analytics
- **Style DNA Radar** - 5-axis personality chart (Boldness, Versatility, Formality, Creativity, Trendiness)
- **Temporal Comparison** - See how your style evolved vs 30 days ago
- **Mood Tracker** - Log your mood with each outfit selection
- **Star Ratings** - Rate outfits 1-5 stars, shown in history
- **Color Palette Analyzer** - Harmony analysis (complementary, analogous, triadic, etc.)
- **Streak Counter** - Track consecutive days of outfit picks
- **12 Achievements** - Unlockable badges with progress tracking

### Quality of Life
- **Dark Mode** - Full dark theme with toggle
- **Daily Style Tips** - 21 rotating fashion tips
- **Favorites** - Save and manage your best outfits
- **Pull to Refresh** - Swipe down to shuffle recommendations
- **Haptic Feedback** - Tactile response on mobile
- **Keyboard Shortcuts** - 1-5 for vibes, R to refresh, D for dark mode, Ctrl+S to save
- **Share Outfits** - Web Share API with clipboard fallback
- **Offline Support** - Works offline with local data persistence

### Data & Privacy
- **Auto-Save** - Continuous save to localStorage + IndexedDB backup
- **Export/Import** - Full JSON data export and import
- **No Account Required** - All data stays on your device
- **XSS Protection** - All user input is sanitized

## Tech Stack

Single-file HTML/CSS/JS app (no build step, no dependencies):
- **APIs** - Claude API (critique + vision), Open-Meteo (weather), Nominatim (geocoding)
- **Storage** - localStorage + IndexedDB dual persistence
- **Graphics** - Canvas 2D for composites and radar charts
- **PWA-ready** - Mobile-optimized with touch gestures

## Setup

1. Open the [live app](https://eiasash.github.io/Watch-advisor-share/)
2. Go to **Settings** and add your Anthropic API key for AI features
3. Enable **Location Services** for weather-based recommendations
4. Start picking outfits!

## License

MIT
