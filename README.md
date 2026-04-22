# PHGrund Theme

PHGrund Theme is a dark Visual Studio Code theme built around deep blue editor surfaces, electric cyan accents, and readable syntax contrast.

## Preview

The theme focuses on:

- A dark, low-glare editor background.
- Cyan UI highlights for active state and navigation.
- Clear syntax colors for strings, keywords, functions, classes, markdown, JSON, CSS, and terminal ANSI colors.

## Installation

Install it from the Visual Studio Code Marketplace, then select it with:

1. Open the Command Palette.
2. Run `Preferences: Color Theme`.
3. Choose `PHGrund Theme`.

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
