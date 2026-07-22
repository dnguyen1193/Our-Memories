# Our Memories 🌸

One site that holds all of Duy & Vy's memories.

```
index.html       ← landing page (the hub)
journal.html     ← Our Travel Journal
letter.html      ← Chưa Gặp Đã Nhớ (interactive letter)
letter-a*.…      ← the letter's music, lyrics & fonts
```

Live at: `https://dnguyen1193.github.io/Our-Memories/`

## How to add a new memory later ✨

1. Add the new page as a single file, e.g. `anniversary.html`.
2. Open `index.html`, find the `memories` array near the bottom, and add one entry:

```js
{
  href: "anniversary.html",
  emoji: "🎂",
  kicker: "Anniversary",
  title: "One Year Together",
  desc: "A little something for our first year.",
  cover: "linear-gradient(135deg,#f9eef1,#fdd9e2)"
}
```

3. Commit — a new card appears on the landing page automatically.
