# Jharokha Remote releases

Built installers for Jharokha Remote, a Windows remote-desktop product. **No source code lives here**; the source is in a private repository.

**Download:** [latest release](https://github.com/mcankalx/jharokha-releases/releases/latest). Other versions are under [Releases](https://github.com/mcankalx/jharokha-releases/releases). Check the SHA-256 in the release notes against the file you downloaded before you install it.

## Read this before you install

* **Manual, self-signed build.** These installers are built by hand on a developer PC and signed with a **self-signed certificate** (`CN=Ampro Technologies` from 0.2.1; 0.2.0 and earlier: `CN=TriloInfotech.com`). Automatic (CI-based) builds are still to come. A real code-signing certificate has not been bought yet.
* **Windows will show an "unknown publisher" warning** (the UAC prompt and SmartScreen), because no Windows computer trusts a self-signed certificate. That is expected for these builds. Only continue (More info, then Run anyway) for a file whose SHA-256 matches the one in the release notes.
* **The licence text is an unreviewed draft.** The licence page in the installer was written by the development team and **no lawyer has reviewed it**. These builds are for **pilot use only**, pending formal legal review.
* **Please share this link only within the intended pilot audience.** The repository is public, so anyone with the link can download the files; do not post it elsewhere.
* Needs 64-bit Windows and the Microsoft Edge WebView2 Runtime (included in Windows 11 and current Windows 10).
