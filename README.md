# ARIA Docset Generator

Generates [ARIA 1.1] docset bundles for [Dash].

![Screenshot](screenshot.png)

## Downloading Docsets

See the [Releases] page.

## Generating Docsets

1. Boot into the shell (requires [Docker]):

   ```sh
   $ ./bin/shell
   ```

2. Run the generate command:

   ```sh
   $ ./bin/generate
   ```

The docset should have been generated in the project root. Just double-click to
add it to Dash.

[ARIA 1.1]: https://www.w3.org/TR/wai-aria-1.1/
[Dash]: https://kapeli.com/dash
[Releases]: https://github.com/jgwhite/aria-docset-generator/releases
[Docker]: https://www.docker.com/docker-mac
