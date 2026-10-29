# Valorwright Games

Static website for Valorwright Games LLC, a 100% veteran-owned indie studio in Kilgore, Texas. Built as plain HTML and CSS for GitHub Pages and the custom domain valorwright.com.

No build step. No analytics. Fonts are self-hosted.

## Preview locally

From the repository root:

```sh
python3 -m http.server 8080
```

Open http://127.0.0.1:8080/

Root-relative links (`/dna-forge/`, `/css/styles.css`) need a server. Opening the HTML files directly will not load the stylesheet.

## Before launch

- Create the mailbox `contact@valorwright.com`, or replace that address everywhere it appears.
- Read the assumptions comment at the top of `privacy/index.html` and edit the policy so it matches the shipping game.
- GitHub Pages is not enabled in this repository. Publishing and DNS steps belong in the pull request that added the site.

Cinzel and Source Sans 3 are included under the SIL Open Font License. See `fonts/OFL-Cinzel.txt` and `fonts/OFL-SourceSans3.txt`.
