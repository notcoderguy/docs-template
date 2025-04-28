# Docs Template

This is a documentation template that integrates [shadcn](https://shadcn.dev/) with [Docusaurus](https://docusaurus.io/), a modern static website generator. It provides most of the functionality needed to create and manage a documentation website efficiently.

### Installation

```bash
$ bun install
```

### Local Development

```bash
$ bun start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ bun build
```

This command generates static content into the `build` directory and can be served using any static content hosting service.

### Deployment

Using SSH:

```bash
$ USE_SSH=true bun deploy
```

Not using SSH:

```bash
$ GIT_USER=<Your GitHub username> bun deploy
```

If you are using GitHub Pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
