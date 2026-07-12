# Contributing to CodeZero

Thank you for your interest in contributing to CodeZero! We are happy about every contribution, whether it is a bug report, a new feature, a plugin, or improved documentation.

## Where does my contribution belong?

This repository is the **release repository**. It contains the official releases, the Docker Compose setup, and the product README. The actual source code of CodeZero lives in separate repositories inside the [code0-tech organization](https://github.com/code0-tech).

Please open issues and pull requests in the repository that matches your topic:

| Repository | What it is |
|---|---|
| [sculptor](https://github.com/code0-tech/sculptor) | The web frontend where you build flows and manage projects |
| [sagittarius](https://github.com/code0-tech/sagittarius) | The backend that orchestrates data, users, and flows |
| [aquila](https://github.com/code0-tech/aquila) | The runtime gateway that keeps your flows updated |
| [taurus](https://github.com/code0-tech/taurus) | The runtime that executes your flows |
| [draco](https://github.com/code0-tech/draco) | Flow triggers such as HTTP/webhook and cron |
| [velorum](https://github.com/code0-tech/velorum) | The AI orchestrator that generates and edits flows |
| [hercules](https://github.com/code0-tech/hercules) | The Action SDK for building your own plugins |
| [centaurus](https://github.com/code0-tech/centaurus) | The central place for all actions |
| [pictor](https://github.com/code0-tech/pictor) | The base UI component library |
| [tucana](https://github.com/code0-tech/tucana) | The gRPC interface library between all services |
| [telescopium](https://github.com/code0-tech/telescopium) | The documentation published at [docs.codezero.build](https://docs.codezero.build) |

If you are not sure where your topic belongs, just open an issue here or ask on [Discord](https://discord.com/invite/AyMB7DtA7P). We will point you to the right place.

## Contributing to this repository

Contributions here are welcome for:

- The README and product presentation
- Images and other assets
- Problems with the Docker Compose setup

Please note: the compose file and the `.env` template are updated automatically by our release tooling. If you spot a problem with them, open an issue first so we can fix it at the source.

## Reporting bugs

1. Check the existing issues in the matching repository to avoid duplicates.
2. Describe what you did, what you expected, and what happened instead.
3. Include your setup where relevant, for example the release tag (`IMAGE_TAG` in your `.env`), your operating system, and relevant logs from `docker compose logs`.

## Suggesting features

Feature ideas are always welcome. Open an issue in the matching repository and describe the problem you want to solve, not only the solution you have in mind. If you want to discuss an idea first, the [Discord](https://discord.com/invite/AyMB7DtA7P) is the fastest way to reach the team.

## Pull requests

1. Fork the repository you want to contribute to and create a branch for your change.
2. Keep pull requests focused. One topic per pull request makes reviews faster.
3. Write a clear description of what your change does and why.
4. Please write issues, pull requests, and code comments in English.

## Building plugins

You can extend CodeZero without touching any core repository. Plugins (actions) add new nodes, flow types, and triggers to a runtime. The [hercules](https://github.com/code0-tech/hercules) Action SDK is the starting point, and the [documentation](https://docs.codezero.build) covers the details.

## Community

Be respectful and constructive. We want CodeZero to be a welcoming project for everyone. Our [Code of Conduct](CODE_OF_CONDUCT.md) applies to all community spaces.

- 💜 [Discord](https://discord.com/invite/AyMB7DtA7P): ask questions and talk to the team
- 📚 [Docs](https://docs.codezero.build): guides and reference documentation

Thank you for helping to make CodeZero better!
