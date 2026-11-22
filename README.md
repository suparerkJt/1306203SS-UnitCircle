# 1306203 Signals & Systems – interactive apps

Eight interactive web apps (plain HTML/JavaScript, no server needed):

| Tab | File |
|-----|------|
| Unit Circle & Sinusoids | `apps/unit-circle.html` |

`index.html` is the page with the eight tabs. A tab can be linked directly,
e.g. `https://USERNAME.github.io/REPO/#ct-operations`.

## Publish on GitHub Pages

1. Sign in at https://github.com and click **+** -> **New repository**.
   Name it (e.g. `signals-systems`), keep it **Public**, click **Create repository**.
2. Click **uploading an existing file**. Drag in `index.html`, `.nojekyll`,
   `README.md` and the whole `apps` folder, then click **Commit changes**.
   (If your browser hides `.nojekyll`, skip it - the site works without it.)
3. Open the repository's **Settings -> Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**,
   choose branch **main** and folder **/ (root)**, click **Save**.
5. Wait 1-2 minutes. The address appears at the top of the Pages settings:
   `https://USERNAME.github.io/REPO/`

## Test on your own computer first

Open a terminal in this folder and run `python -m http.server 8000`, then open
http://localhost:8000 (opening `index.html` by double-click may also work,
but a small web server is the most reliable).

## Updating later

Edit a file on GitHub (pencil icon) or upload a new copy and commit.
The site refreshes automatically after about a minute.
