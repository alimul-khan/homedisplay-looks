# Home Display looks for Roku

Pictures and layouts for the frame styles, colour themes, Day/Evening backgrounds and "no pictures" option of the
Home Display Roku app. The standard look is built into the app; the Roku downloads any other look from here
(served by GitHub Pages) the first time it is chosen.

- `looks/<Frame>-<Theme>-<day|evening>-<art|noart>.json` — the layout of every screen for one look
- `images/` — pictures, named by their contents so looks share them

Made by `roku/tools/export/export-looks.py` in the Home Display project from the Android app's own drawing code.
