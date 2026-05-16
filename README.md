# Soul Arcade

An arcade-style name vibe reader. Type a name — get one of 54 fun verdicts.
Pure math, no mysticism, no data collection.

## How it works

- Type any English letters (max 20 characters)
- The app hashes the input deterministically and maps it to one of 54 verdicts
- Same input always produces the same output
- No phone numbers, no personal data, no AI, no tracking

## Tech stack

- Single-file HTML + CSS + vanilla JavaScript
- djb2 hash with Murmur3 avalanche finalizer
- Web Audio API for 8-bit sound effects
- LocalStorage for personal scan counter (never uploaded)
- Privacy-safe viral loop via one-way hash in shared URLs

## Live demo

Once GitHub Pages is enabled: https://denislunev.github.io/soul-arcade/

## Privacy

See [privacy.html](privacy.html) — the app collects zero data.

## License

Copyright (c) 2026 Denis Lunev. All rights reserved.
