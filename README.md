# Twitter Thread to Markdown

This Chrome extension extracts Twitter threads and copies them to your clipboard in Markdown format.  Useful for note-taking!

## Features

* Extracts text, links, and images (TODO: Image support is not yet implemented) from Twitter threads into Markdown format.
* Copies the extracted Markdown text to your clipboard.
* Can be executed via a command (`Ctrl+E` or `Command+E`) and a context menu.

## Development Instructions

1. Clone the repository.
2. Navigate to the project directory: `cd twitter-thread-to-markdown`
3. Install dependencies: `bun install`
4. Compile TypeScript: `bun run build` (If `bun run build` returns an error, check your `tsconfig.json` settings.  If necessary, generate `tsconfig.json` using `tsc --init` and adjust the settings.)
5. In the Chrome extensions management screen, load `dist/manifest.json` (The `dist` folder is generated after building).


## License

MIT License


## Contributing

Pull requests are welcome.


## Disclaimer

This extension does not use the Twitter API. Therefore, it may stop working due to changes in Twitter's specifications.
