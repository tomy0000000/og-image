# [Open Graph Image as a Service](https://og-image.tomy.tech)

<img align="right" src="https://og-image.vercel.app/tweet.png" height="300" />

Serverless service that generates dynamic Open Graph images that you can embed in your `<meta>` tags.

For each keystroke, headless chromium is used to render an HTML page and take a screenshot of the result which gets cached.

See the image embedded in the tweet for a real use case.

## Usage

```html
<meta
  property="og:image"
  content="https://og-image.tomy.tech/Hello%20World.png"
/>
```

## Changelog

The fork is based on [vercel/og-image@e77be57](https://github.com/vercel/og-image/commit/e77be575492b98e80b71e430c962b1c121feff23)

- Add the `dracula` theme
- Change default font to `Noto Snas TC` to support Chinese characters
  - Lookout for changes on vercel/og-image#108 for better solution
- Add Tomy Logo to the image

## Credit

This is a fork of [vercel/og-image](https://github.com/vercel/og-image)
