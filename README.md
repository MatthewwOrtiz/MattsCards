# OPTCG card viewer

Static page that reads `My_OPTCG_Cards.numbers` and lets you edit the `#` and `Deck #` columns.

## Put it on GitHub Pages

1. Create a repo and add these files to the root: `index.html`, `.nojekyll`, and `My_OPTCG_Cards.numbers`.
2. In the repo go to **Settings > Pages**, set the source to **Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

The page loads `My_OPTCG_Cards.numbers` from the same folder automatically.

## Heads up: Pages sites are public

Anything in the repo, including the Numbers file, can be read by anyone with the link. If you'd rather not publish it, leave the file out of the repo. The page will then ask you to pick the file instead (Chrome and Edge remember it for next time).

## Saving edits

GitHub Pages can't write files, so edits are saved in your browser (per device).

- **Save** (or Cmd/Ctrl+S) keeps your edits in this browser.
- **Download edits** gives you `My_OPTCG_Cards.edits.json`. Commit that file next to `index.html` and every device will pick up the edits. You can also use **Import edits** on another device.
- **Export .xlsx / .csv** downloads the full sheet with your edits, which you can open in Numbers.

## Updating the collection

Replace `My_OPTCG_Cards.numbers` in the repo and commit. Pages can take a few minutes to refresh, so hard-reload if the old data shows up.
