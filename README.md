# Timelock Contract

<!--
Badges provide a quick visual way to convey various information about your project. Below are several common types of badges. Feel free to uncomment, remove, or add new badges as needed for your project. Make sure to update the links so they point to the correct sources relevant to your project.

- Version: Shows the current version of your project based on the latest release.
- Test CI: Displays the status of your continuous integration testing.
- Lint: Shows the status of your code linting process.
- Code Coverage: Indicates the percentage of your code covered by tests.
- License: Shows the type of license your project is under.
- Docs: Links to your project's documentation.
- Discord: Provides a quick link to join your Discord server.
- Discussions: (Optional) If you use GitHub Discussions, this badge links to that section.
- JS Library: (Optional) If your project includes a JavaScript library, use this badge to link to it.

Remember to replace 'Maia-DAO/foundry-template' with your repository's path and update other relevant links to reflect your project's resources.
-->

[![Version][version-badge]][version-link]
<!-- [![Test CI][ci-badge]][ci-link] -->
[![Lint][lint-badge]][lint-link]
<!-- [![Code Coverage][coverage-badge]][coverage-link] -->
[![Solidity][solidity-shield]][ci-link]
[![License][license-badge]][license-link]
[![Docs][docs-badge]][docs-link]
[![Discord][discord-badge]][discord-link]
<!-- [![Discussions][discussions-badge]][discussions-link] -->
<!-- [![JS Library][js-library-badge]][js-library-link] -->

A treasury contract that executes governance actions. This contract holds funds and ownership of DAO contracts and executes actions from governance proposals.

## Contributing

If you’re interested in contributing please see our [contribution guidelines](./CONTRIBUTING.md)! This includes instructions on how to compile and run tests locally.

## Documentation

A more detailed description of the project can be found in the [documentation](https://v2-docs.maiadao.io/).

## Repository Structure

All contracts are held within the `./src` folder.

```ml
src
└── Timelock - "Timelock Governance Contract"
```

## Building

Forl this repo and run:

```bash
forge build
```

## License

[MIT](LICENSE) Copyright <YEAR> <COPYRIGHT HOLDER>

<!-- 
Update the following badge links for your repository:
- Replace 'Maia-DAO/foundry-template' with your repository path.
- Replace Maia DAO Discord link with your Discord server invite link.
-->

[version-badge]: https://img.shields.io/github/v/release/Maia-DAO/foundry-template
[version-link]: https://github.com/Maia-DAO/foundry-template/releases
[ci-badge]: https://github.com/Maia-DAO/foundry-template/actions/workflows/test.yml/badge.svg
[ci-link]: https://github.com/Maia-DAO/foundry-template/actions/workflows/test.yml
[lint-badge]: https://github.com/Maia-DAO/foundry-template/actions/workflows/lint.yml/badge.svg
[lint-link]: https://github.com/Maia-DAO/foundry-template/actions/workflows/lint.yml
[coverage-badge]: .github/coverage-badge.svg
[coverage-link]: .github/coverage-badge.svg
[solidity-shield]: https://img.shields.io/badge/solidity-%5E0.8.0-aa6746
[license-badge]: https://img.shields.io/github/license/Maia-DAO/foundry-template
[license-link]: https://github.com/Maia-DAO/foundry-template/blob/main/LICENSE
[docs-badge]: https://img.shields.io/badge/Ecosystem-documentation-informational
[docs-link]: https://v2-docs.maiadao.io/
[discussions-badge]: https://img.shields.io/badge/foundry-template-discussions-blueviolet
[discussions-link]: https://github.com/Maia-DAO/foundry-template/discussions
[js-library-badge]: https://img.shields.io/badge/foundry-template.js-library-red
[js-library-link]: https://github.com/Maia-DAO/foundry-template-js
[discord-badge]: https://img.shields.io/static/v1?logo=discord&label=discord&message=Join&color=blue
[discord-link]: https://discord.gg/maiadao
