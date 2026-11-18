# DH 150 final project template: Archive Site

This repository is a starting point for your final project website. You will write your artifact notes, AI analyses, and paper in an online editor, and the site updates itself. You do not need to install anything or know how to code.

## Part 1. Make your own copy (one team member does this)

1. Make a free GitHub account at github.com/signup if you do not have one. The username becomes part of your site's web address, so choose one you are comfortable making public.
2. Open this page. Click the green **Use this template** button, then **Create a new repository**.
3. Under **Owner**, choose your own account. Under **Repository name**, type a short lowercase name with no spaces, for example `dh150-red-team`. Choose **Public**, then click **Create repository**.

## Part 2. Turn on the website

1. In your new repository, click **Settings**, then **Pages** in the left menu.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Set the branch to **main** and the folder to **/ (root)**, then click **Save**.
3. Wait one to three minutes. Refresh the Pages settings screen and your site address will appear at the top. It looks like `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`.

## Part 3. Fill in the three settings

1. Back on the repository's main page, click the file `_config.yml`, then the pencil icon to edit it.
2. Change the three lines marked **CHANGE ME**: `title`, `team`, and `baseurl`. For `baseurl`, type a slash and then your repository name exactly, for example `"/dh150-red-team"`. If this is wrong, your site will look like plain unstyled text.
3. Click **Commit changes**, then **Commit changes** again. Wait a minute or two and reload your site.

## Part 4. Add your teammates

The person who created the repository opens **Settings**, then **Collaborators**, then **Add people**, and adds each teammate by GitHub username. Each teammate must accept the invitation (check email or github.com/notifications).

## Part 5. Write your site in the online editor

1. Go to **pagescms.org** and sign in with GitHub. Choose your repository when asked. If it asks you to install the Pages CMS app on the repository, say yes.
2. The left menu has everything you need:
   - **Home page** and **About**: your welcome text and team information.
   - **Artifacts**: one entry per artifact (5 to 20). Fill in the creator and rights fields every time. Upload one image per artifact if you have one, keeping files under about 2 MB. Write your museum plaque text in the main box.
   - **AI analyses**: one entry per analysis (at least 5, each a different type).
   - **Argument paper**: your 1500 to 2000 word essay and works cited list.
3. Click **Save** in the editor. Your change appears on the live site after one or two minutes.
4. **Delete the sample entries** (the Frankenstein artifact and the sample analysis) or overwrite them with your own.

## Check your progress

Visit `/checklist/` on your site (add it to your site address). It counts your artifacts, words, and analyses against the assignment requirements. The counts are approximate.

## Submit

When you submit your site address on BruinLearn, it'll look like `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`. Open it in a private browser window first to make sure it works for someone who is not logged in.

## Things to remember

- **The site is public.** Anyone with the link can read it.
- **Copyright.** Use only what you have the rights to use. For things you cannot reproduce, quote only the short parts you need for commentary, or link to YouTube or another platform that allows it. Record your reasoning in each artifact's rights field.
- **Video and audio.** Do not upload large files. Paste the embed link from YouTube or SoundCloud into the embed field.
- **Describe your images.** The image description field is read aloud by screen readers. One or two plain sentences is enough.

## If something goes wrong

- **The site looks like plain text with no styling.** The `baseurl` in `_config.yml` does not match your repository name. Check spelling, the leading slash, and capital letters.
- **You see a 404 page.** Pages may not be turned on, or it may still be building. Wait two minutes, then recheck Part 2.
- **Your edits or new posts do not show up.** Wait a minute or two and do a hard refresh (Ctrl+Shift+R on Windows, Cmd+Shift+R on Mac). You can watch the build under the repository's **Actions** tab: a green check means it worked and a red X means it failed.
- **Pages CMS cannot see your repository.** Make sure you installed the Pages CMS app on that repository, and that you are signed in with the GitHub account that has access to it.
- **Pages CMS is not working at all.** You can edit any file directly on GitHub instead: open the file, click the pencil icon, and commit. Entries live in the `_artifacts` and `_analyses` folders.
