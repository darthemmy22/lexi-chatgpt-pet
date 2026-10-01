# Lexi — ChatGPT Desktop Pet

Lexi is a miniature animated assistant with long dark wavy hair, black rectangular glasses, a black dress, and a white cardigan.

![Lexi waving](preview.webp)

## Download and install

Download **Lexi-v1.0.0.zip** from this repository or its Releases page.

### Windows

1. Extract the ZIP.
2. Press Ctrl+L in File Explorer and open `%USERPROFILE%\.codex\pets` (create the `pets` folder if needed).
3. Copy the extracted `lexi` folder into `pets`.
4. The resulting folder must contain `lexi/pet.json` and `lexi/spritesheet.webp`, without an extra nested `lexi` folder.
5. In the desktop app, open **Settings → Pets → Refresh**, choose **Lexi**, and use `/pet` to show it.

If you use a custom CODEX_HOME, use its `pets` folder instead. No installer or executable is included.

### macOS

Copy the extracted `lexi` folder to `~/.codex/pets/`, then refresh the pet picker.

## Compatibility

- Packaged for the desktop custom pet system: sprite version 2, transparent WebP, 1536 × 2288 pixels, 8 × 11 cells.
- Uses the existing installed Lexi artwork without alteration.
- Includes nine standard animation rows and sixteen look-direction frames.
- Structural validation passed without errors or warnings. Installation on other devices has not been independently tested.
- **Dot avatar compatibility is not verified.** Official Dot documentation describes built-in appearance customization but does not document importing these pet files. This release does not promise that Lexi can replace the Dot profile avatar.
- The ChatGPT web pet uploader currently documents a different 1536 × 1872 format. Do not upload this version-2 desktop sheet there.
- These files provide an appearance only, not an agent, personality, voice, or app permissions.

## Use

You may download and install Lexi for your personal use as a custom pet. No broader redistribution or commercial-use license is granted in this release; contact the maintainer about those uses.

Community-created release; not affiliated with or endorsed by OpenAI.

## Sources

- [Official pets guide](https://learn.chatgpt.com/docs/pets)
- [Official Dot setup guide](https://learn.chatgpt.com/docs/dots/getting-started)

## Version 1.0.0

First public package of the existing Lexi desktop pet. See `SHA256SUMS.txt` to verify the downloaded pet files.
