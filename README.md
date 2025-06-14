<p align="center"> <img alt="Impstation" src="https://github.com/hereelabs/imp-station-14/blob/master/Resources/Textures/Logo/logo.png" /></p>

Impstation is a fork of Space Station 14, a remake of SS13 that runs on [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), a homegrown engine written in C#.

But this... isn't Impstation. Just a shitty little fork of it.

## Links
[Website](https://impstation.gay/) | [Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Standalone Download](https://spacestation14.io/about/nightlies/)

## Documentation/Wiki

SS14's [docs site](https://docs.spacestation14.com/) has documentation on SS14's content, engine, game design, and more.
Additionally, see these resources for license and attribution information:
- [Robust Generic Attribution](https://docs.spacestation14.com/en/specifications/robust-generic-attribution.html)
- [Robust Station Image](https://docs.spacestation14.com/en/specifications/robust-station-image.html)

## Contributing

Are you smart? Go contribute to [Impstation](https://github.com/impstation/imp-station-14), Not this. If, for some ungodly reason, you *really ***REALLY**** want to contribute here, just make a PR, and so long as it doesn't make the game unplayable, I'll merge it.

## Building

1. Clone this repo:
```shell
git clone https://github.com/hereelabs/imp-station-14.git
```
2. Go to the project folder and run `RUN_THIS.py` to initialize the submodules and load the engine:
```shell
cd space-station-14
python RUN_THIS.py
```
3. Compile the solution:

Build the server using `dotnet build`.

[More detailed instructions on building the project.](https://docs.spacestation14.com/en/general-development/setup.html)

## License

Content contributed to this repository after and including commit 7210960b2b30e17aa001f4e35a5d0f80ca548e53 (`15 August 2024 17:02:49 UTC`) is licensed under the GNU Affero General Public License version 3.0 unless otherwise stated. See [LICENSE-AGPLv3](./LICENSE-AGPLv3.TXT).

Content contributed to this repository before commit 7210960b2b30e17aa001f4e35a5d0f80ca548e53 (`15 August 2024 17:02:49 UTC`) is licensed under the MIT license unless otherwise stated. See [LICENSE-MIT](./LICENSE-MIT.TXT).

To be more specific, code in Content./Impstation, Resources//Impstation and any Impstation specific scripts in Tools are licensed under AGPLv3. Other files are originally from other codebases and are not owned by Impstation, though any code must be relicensable to AGPLv3. SS14 is MIT licensed so this forking is possible.

Most assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and copyright specified in the metadata file. For example, see the [metadata for a crowbar](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Note that some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.

## Attributions

When we pull content from other forks, we try to organize their content to their own subfolders in each of the projects to keep track of attribution and try to prevent merge conflicts.

Content under these subdirectories either originate from their respective fork, or are modifications related to content from their respective fork.

| Subdirectory     | Fork Name | Fork Repository | License |
|------------------|-----------|-----------------|---------|
| `_Impstation`    | Impstation | https://github.com/impstation/imp-station-14/ | AGPL 3.0 |
| `_CD`            | Cosmatic Drift | https://github.com/cosmatic-drift-14/cosmatic-drift | MIT |
| `_Corvax`        | Corvax | https://github.com/space-syndicate/space-station-14 | MIT |
| `_DV`            | Delta-V | https://github.com/DeltaV-Station/Delta-v/ | AGPL 3.0 |
| `_EE`            | Einstein Engines | https://github.com/Simple-Station/Einstein-Engines/ | AGPL 3.0 |
| `_EstacaoPirata` | Estacao Pirata | https://github.com/Day-OS/estacao-pirata-14/ | AGPL 3.0 |
| `_Goobstation`   | Goob Station | https://github.com/Goob-Station/Goob-Station/ | AGPL 3.0 |
| `_Harmony`       | Harmony | https://github.com/ss14-harmony/ss14-harmony | AGPL 3.0 |
| `_NF`            | Frontier Station | https://github.com/new-frontiers-14/frontier-station-14 | AGPL 3.0 |
| `_White`         | White Dream | https://github.com/WWhiteDreamProject/wwdpublic/ | AGPL 3.0 |
| n/a              | Monolith | https://github.com/Monolith-Station/Monolith | AGPL 3.0 |
| n/a              | Nyanotrasen | https://github.com/Fleshmung/Nyanotrasen/tree/master | MIT |
