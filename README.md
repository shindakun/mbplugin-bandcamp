# Bandcamp

Adds a Bandcamp short code to Micro.blog.

---

Usage:

```
{{< bandcamp id="767801457" url="masterbootrecord.bandcamp.com/album/c-defrag" artist="MASTER BOOT RECORD" album="C:\\>DEFRAG">}}
```
---

Example Post:

![example post](imgs/example.png)

---

Details for Nerds:

To get the ID of a Bandcamp album you can run `TralbumData.id` in the JavaScript console from the Bandcamp album page.
To get the album title use `TralbumData.current.title`.
To get the URL use `TralbumData.url`, note leave off the `https://` in the short code or micro.blog will attempt to auto link it.
To get the artist use `TralbumData.artist`.