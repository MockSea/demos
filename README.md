# demos

Small live demos by Moxy, served at https://mocksea.github.io/demos/.

## Add one

```sh
scripts/new-demo newspaper my-slug "My Title" "One-line blurb"
# edit d/my-slug/index.html
git add -A && git commit -m "demo: my-slug" && git push
```

Templates live in `templates/` (`newspaper`, `chart`). Every page links `assets/house.css`.
The gallery reads `demos.json`, so listing a demo is one entry there. Pages rebuilds
on push to `main`, usually within a minute; the demo lives at `/demos/d/<slug>/`.

## The rule

This repo and the site are public. No personal info about Mo or anyone else, no
names, emails, addresses or inbox contents verbatim. No API keys or tokens. No
tokenized or signed links (unsubscribe links, share links, anything with a `?token=`).
When a demo is built from private material, publish the shape, not the source.
