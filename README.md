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

## Local photo update
Temporary Michigan football image: Ken Lund, September 26, 2015. CC BY-SA 2.0, https://creativecommons.org/licenses/by-sa/2.0/ . Original downloaded unchanged; CSS crops its displayed frame. Source: https://commons.wikimedia.org/wiki/File:University_of_Michigan_Football_Team_Taking_the_Field,_Michigan_Stadium,_University_of_Michigan,_Ann_Arbor,_Michigan_(21733038192).jpg .

## Faculty portraits
Nine illustrated transparent portraits in `assets/faculty/` were created using the built-in image generation tool from the official Michigan ECE directory photos. The selected layout displays them 40% smaller than the first local design. Local reference photographs, generation prompts, and unused comparison assets are excluded from publication.
