# Font Lineup

Type a text once and see it in all 1,900+ fonts at the same time, instead of changing the font one by one to compare. It was built for MakerWorld’s customizer, where choosing a font from a very long list is slow, so you can find a font first and then copy its name into the model. It is just as useful for any design work, such as Inkscape projects, labels or signs, where you want to try many fonts quickly before you decide.

**Open it here: https://karlashi.github.io/font-lineup/**

There is nothing to install or download. It works in your browser.

## How to use it

1. Open the link above.
2. Type your text in the **Your text** box. Every font card updates to show it.
3. Use the **size** slider to make the previews larger or smaller.
4. Narrow the list with the style buttons (Sans, Serif, Display, Handwriting, Mono) or type part of a name into **Find a font name**.
5. Click the star on the fonts you like. The **Starred** button then shows only those.
6. Click **Copy name** on a card and paste the name into the font field in MakerWorld.

Bold and italic are chosen in MakerWorld's own font dialog. The **Styles** link on each card opens that font on Google Fonts, where you can see all its styles.

## Installed fonts

Click **Show installed fonts** to see which fonts are already on your computer. They move to the top of the list with an **Installed** label, and the **Installed** button shows only them.

- **Chrome and Edge:** the browser asks for permission to read your list of fonts. The page then also shows installed fonts that are not in the MakerWorld list, labeled "not in list". MakerWorld's online customizer can only use fonts from its own list. The other fonts are useful in programs that read your computer's fonts, such as OpenSCAD.
- **Firefox and Safari:** these browsers do not let a page read the full font list. The page checks which fonts from its own list are installed and marks those. Other installed fonts will not appear.

The page never reads your fonts until you click the button, and nothing leaves your computer.

## Keeping the font list current

The list contains the 1,908 font families of Google Fonts, which MakerWorld's customizer is based on. MakerWorld does not publish its own list, so a few names may be missing there, or newer on one side than the other. If MakerWorld does not find a name, check the exact spelling in its font dialog.

To see whether anything changed, click **Check for new fonts**. The page compares its list with a current one and shows what was added or removed. Nothing changes until you click **Update my list**. The page does not check by itself when it opens. Your updated list is saved in your own browser, and **Go back to the built-in list** undoes it.

## Good to know

- You need an internet connection. The font previews are loaded from Google Fonts while you scroll.
- Your stars and any list update are saved in your own browser, on your own device. They are not shared with other people or other devices.
- This is an unofficial helper. It is not connected to MakerWorld or Bambu Lab.

## Using it offline or sharing a copy

Open the page, then use your browser's **Save page as** to keep a copy. Previews still need an internet connection.

## For the person who maintains this page

The whole tool is one file, `index.html`. To publish a new version, open this repository, choose **Add file**, then **Upload files**, drop in the new `index.html` with the same name, and click **Commit changes**. The link stays the same and shows the new version within a couple of minutes.
