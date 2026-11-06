# Michigan Circuits Research Center — local website preview

Working center concept for University of Michigan. The name, membership model, and benefits are provisional.

## Preview locally

From this repository folder, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1 --directory .
```

Open http://127.0.0.1:8000. No installation or build is needed. Stop the server with Control-C.

## Files

- `index.html`: public content and clearly labeled member-access placeholder
- `styles.css`: responsive dark blue, white, and maize design
- `script.js`: accessible mobile navigation

Google Fonts are optional network resources; system fonts are used when unavailable. Faculty links point to public Michigan ECE profiles. The temporary illustrative lab photograph is not of Michigan students or a Michigan lab. Photo by Yohannes Bogale Fentie, CC0: https://commons.wikimedia.org/wiki/File:Students-Teacher-in-the-Lab.jpg . Downloaded from https://upload.wikimedia.org/wikipedia/commons/c/cb/Students-Teacher-in-the-Lab.jpg . Replace later with an authentic Michigan photograph whose publication rights have been confirmed.

No authentication or private data is included. GitHub Pages alone cannot securely protect student listings, research projects, early results, or agendas. Select a separate secure member-access service before adding any such resources; never put private data in this public repository.

The repository root is the static site root. GitHub Pages publishes from `main` and `/`. Public URL: https://wentzloff.github.io/ .
