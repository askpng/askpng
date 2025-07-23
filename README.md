### askpng ⁉️

Hello there! I'm a Technical Writer. I write docs, guides, and FAQs to help users solve software problems effectively. I'm interested in a lot of things - OSS, AI/ML, and computers being some of them, as well as culture and languages.

My GitHub hosts learning projects - mostly Linux-y. They're experimental in nature, and I'm proud to have grown by creating and maintaining them!

#### atomic-t480s
[atomic-t480s](https://github.com/askpng/atomic-t480s) is a set of custom Atomic Fedora images - Silverblue and Kinoite - built using the [BlueBuild](https://blue-build.org/) tool. It's a nifty tool that simplifies the creation of `Containerfile`s. Build recipes are written in YAML, a very human-readable markup language. Some configs are written in Bash.

This project was created with the intention of sharing use-ready variants of Atomic Fedora for Lenovo T480(s) devices. On stock Fedora, both Workstation and Atomic variants, users are required to manually install enablement utilities, such as `TLP`, and drivers for the fingerprint sensor to work correctly. In addition, hardware acceleration packages are built into the image - stock Fedora does not ship these packages due to its project guidelines. This image aims to eliminate the need - users only need to run initializing commands and complete a reboot to get their T480(s) fully ready for use.

atomic-t480s is considered stable and self-maintaining.

#### solarpowered
[solarpowered](https://github.com/askpng/solarpowered) is a set of custom Atomic Fedora image that I daily drive on my personal devices - a Lenovo T480s, a desktop PC, and a Steam Deck.

This project was created on my second year of transitioning to Linux from Windows. Building solarpowered and its variants took rigorous testing and many trial-and-errors; it taught me a lot about patience and paying attention to details. I am very happy with how it turned out, and I will keep experimenting with this project.

Changes made to the source images are mostly made to accommodate to my needs and personal preference.

This project is greatly inspired by the [Universal Blue](https://universal-blue.org/) initiative.
