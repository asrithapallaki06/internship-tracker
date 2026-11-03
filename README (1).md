# Charm School Tracker

My personal internship, co-op and job application tracker. It's one file (`index.html`) with no setup or build step.

## Put it online with GitHub Pages

1. Go to github.com and click **New repository**. Name it something like `internship-tracker`.
2. Choose **Public** (see the note below about private), then click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html` and this `README.md`, and click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then click **Save**.
5. Wait a minute or two, then refresh that page. Your link appears at the top, like `https://YOUR-USERNAME.github.io/internship-tracker/`.
6. Open it in Chrome and bookmark it.

### Public vs private repo
On a free GitHub account, Pages only works on a **public** repo. A **private** repo with a Pages site needs GitHub Pro. Students can get Pro for free through the GitHub Student Developer Pack (education.github.com/pack). Once you have it, you can switch the repo to Private in Settings and the site keeps working.

Either way, **your applications are never in the repo or on GitHub.** They save only in the browser you use. Anyone who finds the link sees an empty tracker, not your list.

## Your data
- Everything saves automatically in that browser, on that device.
- **Back up** downloads a `.json` file of your whole list. Do this now and then.
- **Restore** loads a backup. Use it to move your list to your phone or another computer, or if you clear your browser data.
- Clearing site data or using a private/incognito window starts you with an empty list.

## Making changes
Edit `index.html` right on GitHub (open the file, click the pencil icon, then **Commit changes**). The site updates within a minute or two.

Easy things to change:
- **Colors:** the `--bg`, `--accent`, `--panel` and similar lines near the top of `<style>` (the second set is dark mode).
- **Statuses:** the `STATUSES` list in the `<script>`.
- **Job types:** the `TYPES` list.
- **Charm lessons:** the `LESSONS` list.
- **Academy name and motto:** search for `Petal Point Princess Academy`.
