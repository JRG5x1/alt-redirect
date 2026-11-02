# alt.5x1.com

5x1 apps moved to [apps.5x1.com](https://apps.5x1.com) (repo `JRG5x1/alt`). This site sends browsers there, keeping the path.

`source.json` is a copy of the AltStore source, because AltStore can't follow a page redirect: phones that added `https://alt.5x1.com/source.json` keep getting updates. BEep's `ci/publish.py` refreshes the copy on every publish.
