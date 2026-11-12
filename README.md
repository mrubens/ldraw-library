# LDraw parts library, for the web

A copy of the official [LDraw parts library](https://library.ldraw.org) (the complete library, November 2026 release),
served by GitHub Pages so web apps can read part files straight from a browser (the official site doesn't allow that):

    https://mrubens.github.io/ldraw-library/parts/3001.dat
    https://mrubens.github.io/ldraw-library/p/stud.dat

The files are as LDraw publishes them in `complete.zip` (its `mklist` tools left out), with LDraw's own folders at the top:
`parts/`, `p/`, `models/`, `LDConfig.ldr`.

## License and credit

The LDraw parts library is © the LDraw.org contributors, licensed under CC BY 2.0 and CC BY 4.0 under the LDraw
Contributor Agreement: see `CAreadme.txt`, `CAlicense.txt` and `CAlicense4.txt`. This repository only redistributes it
unchanged; credit belongs to LDraw.org and the part authors named in each file.

LDraw™ is a trademark owned and licensed by the Estate of James Jessiman. LEGO® is a trademark of the LEGO Group,
which does not sponsor, authorize or endorse this.

## Updating

Download the latest `complete.zip` from library.ldraw.org, unzip it, replace these folders with its `ldraw/` contents,
commit and push. Pages republishes on its own.
