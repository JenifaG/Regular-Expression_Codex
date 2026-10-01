# Pattern Lab

A small, static regex learning story. Students travel with Nia and Byte through six animated chapters, then try each pattern themselves. No build step or server functions are required.

## Run locally

Open `index.html` in a browser, or serve this folder with any static file server.

## Deploy to Netlify

Connect the GitHub repository in Netlify and use the default configuration. `netlify.toml` publishes the repository root; there is no build command. You can also deploy the folder with Netlify Drop.

## Learning flow

- Six guided missions introduce digits, character sets, boundaries, groups/backreferences, optional characters, and exact repetition.
- Hints, examples, and the “idea” cards reveal extra explanation on demand.
- The sandbox lets students edit patterns and text; the concept map expands individual regex tokens and compares regex with context-free grammars.

The interactive matcher uses JavaScript's regular-expression engine with a Python-style syntax subset. Most examples work in Python `re` as written, but the sandbox is not executing Python. Engine differences and invalid patterns are surfaced in the interface.
