# Times Square

![MyBodyWatch](https://img.shields.io/badge/MyBodyWatch-News%20Feed-blue)
![License](https://img.shields.io/github/license/mybodywatch/times-square)

## Overview

Welcome to Times Square, the official content repository for the [MyBodyWatch](https://mybodywatch.app) app's news and information feed. This repository serves as a lightweight content management system for delivering updates, tutorials, and other important information to MyBodyWatch users.

[![Download on the App Store](https://img.shields.io/badge/Download%20on%20the-App%20Store-blue?logo=apple&style=flat-square)](https://apps.apple.com/app/mybodywatch/id6474689088)

### About MyBodyWatch™

MyBodyWatch™ is a wellness app that simplifies fitness tracking by generating a single, easy-to-understand BodyWatch Index (0-10) that reflects your overall body state. The app:

- Analyzes your sleep, resting heart rate (RHR), and heart rate variability (HRV)
- Creates personalized baselines unique to your body
- Updates your BodyWatch Index throughout the day by combining multiple factors
- Transforms complex health metrics into an actionable fitness index

This approach helps you understand your body's fitness status without needing to interpret multiple complicated metrics on your own.

## Purpose

Times Square provides:

- 📱 In-app notifications and news
- 🔍 Searchable documentation
- 🚀 Getting started guides
- 💡 Tips and tricks
- 🎉 Feature announcements and releases

The content hosted here is delivered directly to users via the MyBodyWatch app while also being publicly accessible and SEO-friendly.

## Structure

```
/
├── articles/
│   ├── getting-started/   # Onboarding materials
│   ├── tips/              # Tips and tricks
│   └── news/              # App updates and announcements
├── images/                # Image assets for articles
└── index.json            # Content index and metadata
```

## Contributing

We welcome contributions to improve our documentation! If you find an issue or want to suggest improvements:

1. Fork this repository
2. Create a feature branch (`git checkout -b amazing-improvement`)
3. Make your changes
4. Submit a pull request

For substantial changes, please open an issue first to discuss what you would like to change.

### Content Guidelines

- Use clear, concise language
- Include relevant images or diagrams when helpful
- Follow Markdown best practices
- Check for spelling and grammar errors

## For Developers

If you're a developer interested in how this content is integrated into the MyBodyWatch app, check out our implementation which:

- Fetches content directly from this repository
- Caches articles for offline reading
- Tracks read/unread status via Firebase
- Supports Markdown rendering in-app

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions about MyBodyWatch:
- Visit our [website](https://mybodywatch.app)
- Download the app on the [App Store](https://apps.apple.com/app/mybodywatch/id6474689088)
- Follow us on [Twitter](https://twitter.com/mybodywatch)

<a href="https://apps.apple.com/app/mybodywatch/id6474689088">
  <img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=250x83" alt="Download on the App Store" style="height: 60px;">
</a>

---

*Times Square is named after the famous New York City location known for its bright lights and constant updates - just like our news feed!*
