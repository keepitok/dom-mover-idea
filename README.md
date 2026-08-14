# Dom Mover

A vibe-coded sketch of a browser tool idea: visually direct changes to an existing page, then copy a structured brief for a coding agent.

Move, resize, restyle, edit, duplicate, or remove page elements. Dom Mover records the direction behind those changes; it does not edit source code.

## Try it

Open [`index.html`](./index.html) in a browser, or add the script to a page:

```html
<script src="dom-mover.js"></script>
```

1. Click **Select**, then move or edit the elements that should change.
2. Click **Copy** to copy the recorded changes to your clipboard.
3. Paste the result into a coding agent with a prompt like this:

```text
Implement the following Dom Mover directions. First inspect the relevant template and styles, explain the intent you infer, then make a responsive implementation. Treat captured offsets as visual direction, not literal pixel values.

[paste the copied Dom Mover brief here]
```

This is an exploratory prototype, not a production-ready visual editor.

## License

[MIT](./LICENSE)
