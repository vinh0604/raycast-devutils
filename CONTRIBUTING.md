# Contributing

[![CI](https://github.com/vinh0604/raycast-devutils/actions/workflows/ci.yml/badge.svg)](https://github.com/vinh0604/raycast-devutils/actions/workflows/ci.yml)

This is the source repo for the [Dev Essentials](README.md) Raycast extension. `README.md` doubles as the Raycast Store page, so keep it user-facing and put developer notes here.

## Development

```sh
npm install
npm run dev     # load into Raycast with hot reload
npm test        # unit tests (vitest)
npm run lint    # ESLint, Prettier and Raycast Store validation
npm run build   # production build
```

## Publishing

`npm run publish` submits the extension to the Raycast Store as a pull request on [raycast/extensions](https://github.com/raycast/extensions). It needs an interactive terminal for the GitHub sign-in.

`.github/`, `LICENSE` and this file stay in this repo only; they are not part of the Store copy.

## License

[MIT](LICENSE)
