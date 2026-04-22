# phgrund's theme

phgrund's theme is a dark Visual Studio Code theme tuned around deep blue editor surfaces, electric cyan accents, and clear syntax contrast built for long sessions.

## Preview

The theme focuses on:

- A dark, low-glare editor background.
- Cyan UI highlights for active state and navigation.
- Clear syntax colors for strings, keywords, functions, classes, markdown, JSON, CSS, and terminal ANSI colors.

## Installation

Install it from the Visual Studio Code Marketplace, then select it with:

1. Open the Command Palette.
2. Run `Preferences: Color Theme`.
3. Choose `phgrund's theme`.

## Release Notes

See `CHANGELOG.md` for the full history. The current release (0.0.2) updates the marketplace label to `phgrund's theme` and refreshes the copy to match the cyan-forward palette.

## Local Packaging

To build a local `.vsix` package:

```sh
npm install
npm run package
```

To publish to the Marketplace:

```sh
npm run publish
```

Make sure the `publisher` field in `package.json` matches your Visual Studio Marketplace publisher ID before publishing.
