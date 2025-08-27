# Userscripts

A collection of userscripts for browser extensions like Tampermonkey, Violentmonkey, and Greasemonkey. These scripts enhance web browsing by adding custom functionality to websites.

## Available Scripts

### AniList Progress Addon
Display your current chapter/episode progress on the cover image.

- Install: [https://greasyfork.org/en/scripts/546580-anilist-progress-addon](https://greasyfork.org/en/scripts/546580-anilist-progress-addon)
- Source: [anilist/anilist-progress-script.js](anilist/anilist-progress-script.js)

### Website Redirects
Redirect specified websites to designated locations while preserving paths and query parameters.

- Source: [website-redirects/website-redirects-script.js](website-redirects/website-redirects-script.js)

## Development

This project uses [Biome](https://biomejs.dev/) for linting and formatting.

### Setup
```bash
npm install
```

### Available Scripts
- `npm run check` - Run Biome checks (linting, formatting, and import sorting)
- `npm run format` - Format code with Biome
- `npm run fix` - Auto-fix issues with Biome
- `npm run ci` - Run Biome in CI mode (stricter checks for continuous integration)
- `npm run clean` - Remove node_modules

### Debug Logging
Enable debug logging by running this in the browser console and then refreshing the page:
```javascript
localStorage.setItem("userscript-addon-logging", "true")
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run `npm run check` to ensure code quality
5. Submit a pull request

## License

MIT License - see [LICENSE](LICENSE) file for details.
