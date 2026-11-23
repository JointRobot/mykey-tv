# MyKey TV

Kids' channel for ages 5-10 with Myrah and Kiyarah (sister to AIMTV). One self-contained page: autoplay TV, bedtime stories (Appa Loves You), paint, craft, rhymes, treasure hunt. English + Hindi voices built in.

- `index.html` is the whole site (voice clips are embedded).
- `manifest.webmanifest`, `sw.js`, `icons/` make it installable on phones ("Add to Home Screen") and usable offline.
- Weekly update: add the new story/episode to `index.html`, then bump `VERSION` in `sw.js` so installed copies refresh.
- Hosting: Cloudflare Pages, build command none, output directory `/`.
- Safety: made for kids. No comments, no tracking, no ads, no links out.
