# apps-release

Release channel for bananausagi's Android apps (APK + update metadata only).

| App | Package | Metadata |
|---|---|---|
| Pinball Recomp | org.pinball.worldfield | pinball-recomp/latest.json |
| Pinball Collection | org.pinball.collection | pinball-collection/latest.json |
| PocketRecomp | org.gen1recomp.japanese.preview | pocket-recomp/latest.json |

APKs are attached to the GitHub Releases of this repository. Each app checks its latest.json on launch and updates itself (SHA-256 verified).
No game data is distributed here.