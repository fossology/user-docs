# Website

## Structure discussions
With discussions from project members, we cameup with this rough draft for the documentation.
Please feel free to comment on the doc directly.

Link to the doc: https://docs.google.com/document/d/1t8kjri0mdgdo-ja5vSKmV18ClhMurwFqY8Ek-S-2IZQ/edit?usp=sharing

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
