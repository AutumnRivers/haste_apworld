# Setup Guide for Haste Archipelago

Welcome to Haste Archipelago! This guide will help you set up the randomizer and play your first multiworld.
Whether playing, generating, or hosting an Archipelago room with Haste, you must follow a few simple steps to
get started.

Unfortunately, Mac OS is not officially supported at this time.

## Requirements

You'll need the following components to be able to play/generate with Haste:

- Install [Archipelago](https://github.com/ArchipelagoMW/Archipelago/releases) v0.5.1 or higher.\
   **Make sure to install the Generator if you intend to generate multiworlds.**
- The latest version of the [Haste APWorld](https://github.com/WritingHusky/Twilight_Princess_apworld/releases/latest).

If you intend to play under Linux, you will need to consider the following information.

- Grab the `tar.gz` version of Archipelago, not the `AppImage`. The file name should be similar to the following on the
  release page: `Archipelago_X.X.X_linux-x86_64.tar.gz`.

## Installation

All users should follow these steps:

1. Unzip the downloaded Haste APWorld zip file.
2. Double-click the `haste.apworld` file. It should automatically install the APWorld after a little while. You will get a
   little dialog window telling you it has been installed successfully. \* Alternatively, copy the `haste.apworld` to your Archipelago installation's `custom_worlds` folder (Windows default
   to: `%programdata%/Archipelago`).

## Setting Up a YAML

All players playing Haste must provide the room host with a YAML file containing the settings for their world.
The TP APWorld download includes a sample YAML file for Haste. The comments in that file explain each
setting's function.

Once you're happy with your settings, provide the room host with your YAML file and proceed to the next step.

Note: Please note the settings lable NOT IMPLEMENTED as these settings are still under devlopment

## Generating a Multiworld

If you're generating a multiworld game that includes Haste, you'll need to do so locally as the online
generator does not yet support Haste. Follow these steps to generate a multiworld:

1. Gather all player's YAMLs. Place these YAMLs into the `Players` folder of your Archipelago installation. If the
   folder does not exist, then it must be created manually. The files here should not be compressed.
2. Modify any local host settings for generation, as desired.
3. Run `ArchipelagoGenerate.exe` (without `.exe` on Linux) or click `Generate` in the launcher. The generation output
   is placed in the `output` folder (usually named something like `AP_XXXXX.zip`). \* Please note that if any player in the game you want to generate plays a game that needs a ROM file to generate,
   you will need the corresponding ROM files. A ROM file is not required for Haste at this stage.
4. In the next section, use the archive file `AP_XXXXX.zip` to host a room or provide it to the room host.

## Hosting a Room

If you're generating the multiworld, follow the instructions in the previous section. Once you have the zip file
corresponding to your multiworld, follow
[these steps](https://archipelago.gg/tutorial/Archipelago/setup/en#hosting-an-archipelago-server) to host a room. Follow
the instructions for hosting on the website from a locally generated game or on a local machine.

## Connecting to a Room

It is recommended that you open a text client along side the game, as the chat log is still in development.

1. If you haven't already subscribe to the [Archipelgo randomizer mod]() on steam.
2. Start Haste on steam.
3. When the main menu appears go to settings.
4. Chose an new / empty save (So you don't override old saves)
5. In the Archiplego Tab enable the Archipelgo mod
6. Fill out the data to connect to the server (Server name, port, username, password).
7. Start the game.

## Troubleshooting

- Ensure that you are running version v0.6.1 or higher of Archipelago, and the latest version of the world.
- Report issuses to the [Haste post](https://discord.com/channels/731205301247803413/1356638437872111687) on the furture-games channel on the [Archipelego discord](https://discord.gg/archipelago)
