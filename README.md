[README.md](https://github.com/user-attachments/files/33325134/README.md)
# Portfolio site (Tinubu Damilola Frank)

Static site: `index.html` is the whole page. `Tinubu_Damilola_Frank_Resume.pdf` is the resume linked from it.

## Host it free on GitHub Pages
1. On GitHub, create a repository in the dixkox account named `dixkox.github.io` (public).
2. Upload everything in this folder (index.html, the PDF, .nojekyll) with Add file > Upload files, then Commit.
3. Open the repository Settings > Pages. Under Build and deployment choose Deploy from a branch, branch `main`, folder `/ (root)`, Save.
4. After a minute the site is live at https://dixkox.github.io

## Use dixkox.online
1. In Settings > Pages > Custom domain enter `dixkox.tech` and Save (tick Enforce HTTPS when it appears).
2. At the domain registrar's DNS settings add four A records for `@` pointing to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153, and a CNAME for `www` pointing to dixkox.github.io.
3. Wait for DNS to update (minutes to a few hours).

## Add a new certification later
1. Open `index.html` on GitHub and click the pencil (Edit).
2. Search for `Other training` or the school's dropdown (for example `Quantic School`).
3. Copy an existing line like `<li><span>Name, Issuer</span><time>2026</time></li>`, paste it in the right list, change the text, and update the number in the dropdown heading.
4. Commit. The live site updates in about a minute.
