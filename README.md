# atikul-itc.github.io

Personal academic website of Atikul Hoque. Plain HTML and CSS with no build step, hosted on GitHub Pages.

## Structure

```
index.html            Home: bio, research focus, news, recent papers
research.html         Dissertation chapters, other projects, field photos
publications.html     Articles, manuscripts, thesis, presentations
teaching.html         Teaching and mentoring
cv.html               CV highlights and PDF download
404.html              Not-found page
assets/css/style.css  All styling (colors and fonts are set at the top in :root)
assets/js/main.js     Mobile menu and footer year
assets/img/           Photos and figures (compressed for the web)
assets/Atikul_Hoque_CV.pdf
.nojekyll             Tells GitHub Pages to serve the files as they are
```

## Publish on GitHub Pages (one time)

1. Sign in to GitHub and click **New repository**.
2. Name it exactly `Atikul-itc.github.io`, set it to **Public**, and leave "Add a README" unchecked. Click **Create repository**.
3. On the empty repository page, click **uploading an existing file**.
4. Unzip `atikul-itc.github.io.zip` on your computer. Open the unzipped folder, select **everything inside it** (including the `assets` folder), and drag it into the upload area. Upload the contents of the folder, not the folder itself, so that `index.html` sits at the top level of the repository.
5. Click **Commit changes**.
6. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, and folder to **/ (root)**. Click **Save**.
7. Wait one or two minutes and open https://atikul-itc.github.io

Note: hidden files like `.nojekyll` can be skipped by drag and drop on some systems. If that happens, click **Add file > Create new file** in the repository, name it `.nojekyll`, leave it empty, and commit. The site also works without it.

## Common edits

* **Add a publication**: open `publications.html`, copy one `<li class="pub">` block, and edit the text and DOI.
* **Add a news item**: open `index.html` and copy one `<li><time>…</time>…</li>` line in the News list.
* **Replace the CV**: upload a new file named `assets/Atikul_Hoque_CV.pdf`. Keeping the same name means every link updates automatically.
* **Edit on GitHub directly**: open any file in the repository, click the pencil icon, edit, then **Commit changes**. The live site updates within a minute or two.

## Retire the Netlify site

When the new site is live, update the website link on LinkedIn, Google Scholar, and your email signature. Then delete the Netlify site, or archive the old `atikul-hoque-website` repository, so search engines stop indexing two versions.
