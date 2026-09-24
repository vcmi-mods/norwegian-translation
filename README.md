The documentation for translation is [here](https://github.com/vcmi/vcmi/blob/develop/docs/translators/Translations.md).

Information for dubbing are [here](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)

Please create a new issue [here](https://github.com/vcmi-mods/norwegian-translation/issues/new) for any mistake.

# How to play to Heroes of Might and Magic III in Norwegian

1. Buy _Heroes of Might and Magic III Complete Edition_ on GOG (not the HD version)
1. Install the game
1. Download VCMI (free)
1. Install VCMI
1. When installing VCMI, specify the location of the base game's `Data`, `MP3`, and `Maps` folders.
1. Set the language to _Norwegian_
1. Install the _Norsk oversettelse_ mod
1. Launch the game

# Slik spiller du Heroes of Might and Magic III på norsk

1. Kjøp _Heroes of Might and Magic III Complete Edition_ på GOG (ikke HD-versjonen)
1. Installer spillet
1. Last ned VCMI (gratis)
1. Installer VCMI
1. Når du installerer VCMI, spesifiser plasseringen til basisspillets mapper `Data`, `MP3` og `Maps`.
1. Sett språket til _Norsk_
1. Installer _Norsk oversettelse_-modden
1. Start spillet

# How to dub

1. Copy a prolog/epilog from [`norwegian-translation/content/config/vcmi-norwegian/campaigns.json`](https://github.com/vcmi-mods/norwegian-translation/tree/vcmi-1.7/content/config/vcmi-norwegian)
2. Go to [Next-gen Kaldi: Text-to-speech](https://huggingface.co/spaces/csukuangfj/text-to-speech)
4. Paste the speech text
5. Select _Norwegian_
6. Select a model (ex. supertonic)
4. Select a voice (ex. `3`)
7. Click on _Generate_
8. Download the audio file
9. Retrieve the property for the speech in the [`norwegian-translation/content/config/vcmi-norwegian/campaigns.json`](https://github.com/vcmi-mods/norwegian-translation/tree/vcmi-1.7/content/config/vcmi-norwegian) file
10. Retrieve the related audio filename in the [empty-translation mod](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)
11. Rename the audio file
12. Move the file to `norwegian-translation/content/sounds/` folder

# How to contribute

1. Go to the GitHub mod page: https://github.com/vcmi-mods/norwegian-translation
2. Fork the repository by clicking on the "Fork" button
3. Browse to the file you want to change
4. Click on the pencil button to edit the file
5. Edit the file
6. Click on the "Commit changes..." button
7. Click on the "Pull request" tab
8. Click on the "Create Pull Request" button
9. Write a description and create the PR (Pull Request)