# Our Memories 🌸

One site that holds all of Duy & Vy's memories.

```
index.html        ← landing page (the hub)
journal/          ← Our Travel Journal
letter/           ← Chưa Gặp Đã Nhớ (interactive letter)
```

## How to publish on GitHub Pages

1. Create a new repo on GitHub (e.g. `our-memories`).
2. Upload **everything in this folder** (drag & drop works: "Add file → Upload files").
3. Go to **Settings → Pages → Source: Deploy from a branch → main / root → Save**.
4. Your site will be live at `https://<username>.github.io/our-memories/`
   - Landing page: that URL
   - Journal: `.../our-memories/journal/`
   - Letter: `.../our-memories/letter/`

Your two old repos can then be archived or deleted — this one replaces both.

## How to add a new memory later ✨

1. Put the new page in its own folder, e.g. `anniversary/index.html`.
2. Open `index.html`, find the `memories` array near the bottom, and add one entry:

```js
{
  href: "anniversary/",
  emoji: "🎂",
  kicker: "Anniversary",
  title: "One Year Together",
  desc: "A little something for our first year.",
  cover: "linear-gradient(135deg,#f9eef1,#fdd9e2)"
}
```

3. Commit — a new card appears on the landing page automatically.
