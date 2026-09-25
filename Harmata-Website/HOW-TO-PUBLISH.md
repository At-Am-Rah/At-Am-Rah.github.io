# Harmata Group website — how to publish it

The `site` folder is a complete, self-contained website: plain HTML pages, one stylesheet, and an `img` folder. It uses **no Google services, no web fonts and no outside scripts**, so it loads entirely from whatever server hosts it. That matters for readers in mainland China, where Google (including Google Sites) is blocked.

To preview it, double-click `site/index.html`. It opens in your browser.

---

## Option A: GitHub Pages (free, about 10 minutes)

1. Create a free account at <https://github.com>. The username becomes part of the web address, for example `harmata-lab`.
2. Click **+ → New repository**. Name it exactly `USERNAME.github.io` (for example `harmata-lab.github.io`), make it **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in **everything inside** the `site` folder: all the `.html` files, `style.css`, and the `img` folder. Then click **Commit changes**.
   *Note:* `.nojekyll` is a hidden file. If you can't see it in Finder, press Cmd-Shift-. (period) to show hidden files. The site still works without it.
4. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, then branch **main** and folder **/ (root)**, and click **Save**.
5. After about a minute the site is live at `https://USERNAME.github.io/`.

**How well it works from China:** GitHub Pages is usually reachable from mainland China, but it can be slow or intermittently throttled. No free overseas host is guaranteed there. Before you announce the address, ask a student or colleague in China to open it.

## Option B (most reliable in China): a missouri.edu mirror

University `missouri.edu` servers are normally reachable from China. Send the zip file to the Chemistry Department web administrator (or Arts & Science IT). Ask them to host the folder as-is, for example at `chemistry.missouri.edu/harmata/`. The site needs no database or server software; any web server can host the files. You can run Option A and Option B together.

## Afterwards

- Replace the content of your old Google Site with one line pointing to the new address, so existing links still reach you.
- Put the new address in your email signature and on the department faculty page.

## Editing later

Each page is an ordinary HTML file that you can open in any text editor (TextEdit in plain-text mode, BBEdit, VS Code).

- To add a paper: open `publications.html`, copy an existing `<li id="p228">…</li>` line, change the number and text, and paste it at the top of the list.
- To change group members: edit `group.html`. Put photos in `img/`.
- To update GitHub: open the repository, click the file, click the pencil icon, edit, and commit. You can also re-upload the changed file.

---

## Please review these items

1. **Group roster.** The Group page still lists the members from the old site (2018–2020 cohort). Several have probably graduated. Move anyone who has left to `alumni.html` and add their degree year.
2. **Madi Clark and Adam Hunt** had no bio or photo. Madi's short bio comes from her two co-authored publications. Adam's is a one-line placeholder.
3. **New research text.** The old site had empty sections for Tröger's base, retro-Nazarov, cyclopentadienones, allenic sulfones and total syntheses. I wrote these from the titles of your publications, and I added two new sections: oxidopyridinium ions (your current core area) and collaborations. Please check the wording.
4. **Ten new publications (#219–228, 2022–2026)** were added from Crossref and PubMed. Entries #217 and #218, which were listed as "in press", now have their final citations. New entries carry a "new" badge and a DOI link. I left the *Organic Reactions* chapter (#223) without an asterisk. Add one if you consider it not refereed.
5. **Alumni table:** Rama Rao Tata's "last known location" was his own name on the old site, so I replaced it with "—". "Rashawn Ripa" appears as "Rawshan A. Ripa" in the 2022 *Chem. Eur. J.* paper. Please confirm the spelling.
6. **About Me:** "going on 36 years" is now "going on 40 years". I removed the COVID sentence.
7. **Chinese page (`zh.html`):** This is a short introduction for prospective students. A native speaker in the group could check it quickly.
