# HoloCons

A [PaperMC/Paper](https://github.com/PaperMC/Paper) fork intended to be run as the backend for the Hololive Construction Minecraft server.

## Contact

Join us on [Discord](https://discord.gg/UUNsCKP3Ms).

## License

All patches are licensed under the MIT license unless otherwise noted in the patch headers.

[![MIT License](https://img.shields.io/github/license/HoloConsMC/HoloCons?&logo=github)](LICENSE.md)

See [PaperMC/Paper](https://github.com/PaperMC/Paper) and [PaperMC/Paperweight](https://github.com/PaperMC/paperweight) for the licenses of material used by this project.

## Contributing

### Initial setup

First, clone this repository. Do not download it.

Then run `./gradlew applyPatches` in the root directory. The project is now ready for use in your IDE.

To get a full list of tasks, run `./gradlew tasks`.

### Creating a patch

Patches are effectively just commits in either `holocons-api` or `holocons-server`. To create one, add a commit to either repo and run `./gradlew rebuildPatches`, and a patch will be placed in the patches folder. Modifying commits will also modify corresponding patch files.

Refer to Paper's [CONTRIBUTING.md](https://github.com/PaperMC/Paper/blob/HEAD/CONTRIBUTING.md) for more detailed information.
