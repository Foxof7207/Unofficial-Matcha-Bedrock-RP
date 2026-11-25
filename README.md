# Unofficial Matcha Resource Pack for Bedrock

An unofficial, **incomplete** Bedrock resource pack for use with a Minecraft server running GeyserMC. It includes resource-pack files and a custom mappings file.


## Requirements

- A Minecraft server with [GeyserMC](https://geysermc.org/wiki/geyser/setup) installed
- [Floodgate](https://geysermc.org/wiki/floodgate/setup) installed if Bedrock players will join without a Java Edition account
- Access to your server’s files and permission to restart the server

Follow the official setup guides above to install GeyserMC and Floodgate before continuing.

## Download the files

Download the latest release from this repository. It should contain:

- `matcha_mappings.json`
- `item_mappings.json`
- `Match_Bedrock_Ressource_Pack_Part_1.zip`
- `Match_Bedrock_Ressource_Pack_Part_2.zip`

Keep the two ZIP files as they are; **do not extract them**. Make sure you download all three files from the same release.

## Install the pack

1. Stop your server before changing its files.
2. Upload both ZIP files to Geyser’s `packs` folder:
   `/plugins/Geyser-Spigot/packs/`
3. Upload `matcha_mappings.json` to Geyser’s `custom_mappings` folder:
   `/plugins/Geyser-Spigot/custom_mappings/`
4. Check that the files are in the correct folders and that their filenames have not changed.
5. Start OR restart your server.

Bedrock players can then join through your Geyser setup. If the pack does not appear or load, check the troubleshooting section below.

## Troubleshooting

- **The pack does not load:** Confirm that both ZIP files are in `packs` and the mappings file is in `custom_mappings`.
- **A file is missing:** Download all three files from the same release.
- **Nothing changes after installation:** Restart the server and reconnect from the Bedrock client.
- **Still having trouble?** Open an issue in this repository. Include your server software and version, Geyser version, your latest.log via [this website](https://mclo.gs/), and the steps you have already tried.

## Disclaimer

This is an **unofficial and incomplete** Matcha resource pack for Bedrock. Some features may not work as expected, and the pack may change between releases. Contributions and reports of reproducible issues are welcome.
