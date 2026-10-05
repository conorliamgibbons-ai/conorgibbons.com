# conorgibbons.com

Single-page portfolio. Static HTML, no build step.

- `index.html` is the whole site. Design system carried over from the earlier CCG Consulting page (dark, teal, Inter).
- `resume.pdf` is referenced by the Resume buttons. Export the current resume Google Doc as PDF and drop it here with that exact name.
- `conor.jpg` is optional. Uncomment the `<img>` in the About photo card to use it.
- Text in teal brackets on the live page is a placeholder Conor has to fill (interview counts, nominee count, findings). Search `class="fill"`.

## Hosting (GitHub Pages)
1. Push this folder to a GitHub repo.
2. Settings > Pages > Source: Deploy from branch, branch `main`, folder `/ (root)`.
3. Settings > Pages > Custom domain: `conorgibbons.com` (the `CNAME` file already matches).
4. At the registrar holding conorgibbons.com, add: `A` records for the apex pointing at GitHub Pages (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a `CNAME` for `www` pointing at `<github-username>.github.io`.
5. Tick "Enforce HTTPS" once the certificate issues (can take an hour).

## Rules
No semicolons or em dashes anywhere in site copy.
