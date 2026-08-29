# Design Mockups (Adobe XD, 2019)

Three Adobe XD / Illustrator source files from **September–October 2019**: a logo sketch, the mockup for my own portfolio site, and a paid personal-website design for a client. Binary design sources, committed verbatim at their real modification times.

---

## Provenance

> This repository was reconstructed in 2026 from a filesystem archive. These files were never under version control at the time.
>
> **Commit dates are the real modification times of the original files**, recovered with `stat`. The work happened between **2019-09-06 09:50** and **2019-10-22 16:05** local time (UTC+03:30). Three commits are dated 2026 — the README, plus any rendered previews or corrections. Each says which it is in its commit message.
>
> One limit worth stating: a modification time is not an authorship time. It records when a file was last written, which for a copied or re-saved file is later than when the work was done. This drive holds duplicated trees, so some files were certainly moved between them. These dates are therefore a faithful transcription of the filesystem's timeline and a **floor** on when the work happened — not independent proof of authorship on that date.

## Contents

| File | Modified | Size | What it is |
|---|---|---|---|
| `LOGO SCATGH.xd` | 2019-09-06 09:50 | 54 KB | Logo sketches. The filename is a misspelling of "sketch". |
| `hom-asg.xd` | 2019-09-24 08:27 | 10 MB | The design for my own portfolio site — `hom-asg` for Homayoun Asghari. |
| `mahdi nasirzade PW.xd` | 2019-10-22 16:05 | 9.7 MB | A personal-website design for a client, Mahdi Nasirzadeh. `PW` = personal website. |

## The client job

`mahdi nasirzade PW.xd` is the only thing that survives of that job. **No built site exists anywhere in the archive** — not a folder, not a stray HTML file. The design was delivered; nothing was ever coded from it. Whether that was the client's decision or mine, I no longer know.

## How this relates to `homasg-portfolio`

`hom-asg.xd` is the design for the site in my [`homasg-portfolio`](https://github.com/homayoun-asghari/homasg-portfolio) repository. It does **not** predate that code, which is what I assumed before checking the timestamps:

```
2019-09-19 18:07  homasg/index.html          first coded page
2019-09-22 19:08  homasg/pages2/home.html    second coded layout
2019-09-24 08:27  Skaches/hom-asg.xd         <- this file
2019-09-24 08:43  homasg/pages/home.html     third coded layout, 16 minutes later
```

The XD file lands between the second and third attempts at the code — sixteen minutes before the third. It is not a plan that was then built. It is a designer stepping back into the tool he was fluent in after two coded layouts refused to line up, and then going straight back to the HTML. Both the design and the site were abandoned within a month.

## What is wrong with it

- **GitHub cannot preview `.xd` files.** They render as a download link and nothing more. You need Adobe XD to open them, and Adobe discontinued XD as a standalone product; the format is on its way to being unreadable.
- No exported PNG or JPG previews existed in the archive. Renders extracted from each `.xd` bundle's own stored preview image are committed under `previews/` in a clearly dated 2026 commit, so the designs can be seen in the browser. Those renders are 2026 artifacts; the `.xd` sources they come from are the 2019 originals, unmodified.
- The `hom-asg.xd` and `mahdi nasirzade PW.xd` files are 10 MB and 9.7 MB — XD embeds full-resolution raster assets rather than referencing them, so most of that weight is bitmaps I did not author.
- Filenames contain spaces and a spelling error, preserved as they are.

## Attribution

The vector and layout work in these files is mine. Raster images embedded inside them — stock photography and texture fills — are not, and I no longer have a record of where they came from. Treat any photograph you find inside these files as third-party.

The source directory on disk was `Project/Skaches/`.


## Previews

**GitHub cannot display `.xd` files.** Every source file here has a rendered image under `previews/`, extracted in 2026 from the Adobe XD bundle's own stored preview render. These are renders of the committed originals, not new work, and they are added in a clearly dated 2026 commit.

- `previews/LOGO SCATGH-2.png`
- `previews/LOGO SCATGH.png`
- `previews/hom-asg-2.png`
- `previews/hom-asg.png`
- `previews/mahdi nasirzade PW-2.png`
- `previews/mahdi nasirzade PW.png`
