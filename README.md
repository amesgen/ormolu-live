# Ormolu Live

Play around with [ormolu](https://github.com/tweag/ormolu) in the browser via GHCJS!

## Development

If you use nix, make sure to [set up the binary cache for haskell.nix](https://input-output-hk.github.io/haskell.nix/tutorials/getting-started/#setting-up-the-binary-cache).

### Building the site with GHCJS

```
nix-build -A website
```

The site will be in `result`.

### Local development with JSaddle

In a `nix-shell` (or if you have cabal installed), run

```
ghcid -r -W
```

and open `http://localhost:8080` in a Chromium-based browser.

## Acknowledgements

https://github.com/monadfix/ormolu-live
