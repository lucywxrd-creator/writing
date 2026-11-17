# Lucy Ward: music writing portfolio

Live at: https://lucywxrd-creator.github.io/writing/

## Adding a new piece (about 2 minutes)

1. Open `_data/pieces.yml` and click the pencil icon (Edit).
2. Copy this block and paste it at the top of the right section (newest goes first):

```yaml
- title: "Artist – 'Song Name'"
  url: https://link-to-the-article
  publication: EARMILK
  type: singles
  date: Dec 2025
```

3. Fill it in. `type` is one of: `singles`, `releases`, `live`, `previews`, `features`.
4. Optional extra lines (two spaces in front, like the others):
   - `favourite: true` to show it in "My favourites" at the top
   - `editor_byline: true` for pieces published under the editor's name
   - `note: "Short line shown under the link"`
5. Click **Commit changes**. The site updates itself in a minute or two.

## Changing favourites

Add or remove `favourite: true` on any piece. Two or four favourites look neatest.

## If the page breaks after an edit

It's almost always spacing or a missing quote mark. Check that every line in your block starts with two spaces (the `- title` line has none), and that the title is wrapped in straight quotes. The Actions tab shows a red cross if the build failed; undo your last edit from the file's History if you're stuck.

## Files

- `_data/pieces.yml`: all the writing (the only file you normally touch)
- `_config.yml`: site title, email and the section names
- `index.html`: the page layout
- `styles.css`: the Lucy Ward design system (fonts and icons load from lucyaward.co.uk)
