<h1 align="center">BetterDiscordPlugins</h1>
<p align="center">A collection of plugins for the <a href="https://github.com/BetterDiscord">@BetterDiscord</a> client modification.</p>
<p align="center">
    <a href="https://discord.gg/9KAXM9ubfk"><img src="https://discordapp.com/api/guilds/514185816315265068/widget.png"/></a>
    <a href="https://discord.gg/9KAXM9ubfk"><img src="https://github.com/DiscordFormative/BetterDiscordPlugins/actions/workflows/release.yml/badge.svg"/></a>
</p>

# Development

This section is designed for people who are willing to contribute or want to modify the source code for personal use. Here you can find all the information for developing and building locally.


## Prerequisites

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org)
- [Yarn](https://yarnpkg.com/)

## Scripts

#### `yarn dev`

Watches for any changes and automatically builds the plugins directly to your plugins folder.

#### `yarn build`

Builds the plugins for distribution.

#### `yarn lint`
Lints your changes using [ESLint](https://eslint.org/).

#### `yarn lint:fix`
Same as above but also tries to fix any problems.

## Getting started

> Run these commands using any command line tool of your choice.

```bash
# Clone the repository and navigate to its directory.
git clone https://github.com/DiscordFormative/BetterDiscordPlugins && cd BetterDiscordPlugins

# Install all dependencies.
yarn install

# Run the dev script.
yarn dev

# Happy coding 🎉!
```

## Contributing

All contributions are welcome, whether they're a bug fix, a new feature, or even just a typo correction. Only make sure to always target the [develop](https://github.com/DiscordFormative/BetterDiscordPlugins/tree/develop) branch and don't commit your `dist` folder, [GitHub Actions](https://github.com/features/actions) takes care of the entire building process for us.
