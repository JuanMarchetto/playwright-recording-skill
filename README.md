# Playwright Recording

Record browser interactions as video using Playwright. Capture demo videos, app walkthroughs, and UI flows with cursor highlighting, click ripple effects, cookie banner dismissal, and window scaling patterns.

## Install

Via the marketplace:
```
/plugin marketplace add JuanMarchetto/agent-skills
/plugin install playwright-recording@agent-skills
```

Or via [skills.sh](https://skills.sh):
```bash
npx skills add JuanMarchetto/playwright-recording-skill
```

Or manually:
```bash
git clone https://github.com/JuanMarchetto/playwright-recording-skill.git
cp -r playwright-recording-skill ~/.claude/skills/playwright-recording
```

## What's Inside

- Basic recording setup and configuration
- Recording patterns: form submission, multi-page navigation, scroll, login flow
- Cursor highlighting with CSS injection
- Click ripple effect visualization
- Interactive recording with ESC key stop
- Window scaling for laptop screens (record 1080p in smaller window)
- Cookie banner dismissal with comprehensive selector list
- Remotion output integration (WebM to MP4 conversion)
- Full API reference: browser context, page methods, selectors, timing utilities
- Device emulation presets (iPhone, iPad, Pixel, Galaxy)

## What's Inside (Files)

```
playwright-recording/
├── SKILL.md           # Full guide with patterns and examples
└── reference.md       # API reference, selectors, timing utilities
```

## Requirements

- Playwright (`npm install -D playwright`)
- Chromium (`npx playwright install chromium`)
- ffmpeg (for WebM to MP4 conversion)

## License

[MIT](LICENSE)
