# Lexi — ChatGPT Desktop Pet

Lexi is a miniature animated assistant with long dark wavy hair, black rectangular glasses, a black dress, and a white cardigan.

![Lexi, Office Lexi, and Sgt Lexi side by side](https://raw.githubusercontent.com/darthemmy22/lexi-chatgpt-pet/5beec4151beccf77ace2bce123dceaf51a945f16/all-three-lexi-side-by-side.webp)

## Themes

- [Original Lexi](https://github.com/darthemmy22/lexi-chatgpt-pet/releases/tag/v1.0.0) — black dress and white cardigan.
- [Office Lexi](https://github.com/darthemmy22/lexi-chatgpt-pet/releases/tag/office-lexi-v1.0.0) — blazer, notebook, and coffee.
- [Sgt Lexi](https://github.com/darthemmy22/lexi-chatgpt-pet/releases/tag/sgt-lexi-v1.0.0) — Marine sergeant theme with loose hair, glasses, ribbons, khaki blouse, and navy skirt.

Each themed ZIP includes its own setup instructions. Install the `office-lexi` or `sgt-lexi` folder for the theme you choose.

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

