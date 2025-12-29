# Misaka Treasure Chest

Binary package repository for Build Factory packages.

Pacman config (raw GitHub):

[buildfactory]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/Neycrol/misaka-treasure-chest/main/repo

Notes:
- Small packages are built by GitHub Actions from the source PKGBUILD repo.
- Heavy packages are built locally or on a self-hosted runner and uploaded into repo/.
