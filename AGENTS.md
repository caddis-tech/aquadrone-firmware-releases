# aquadrone-firmware-releases

This repository follows the Caddis engineering standards. Read them before your first edit,
commit, or pull request: `../../../AGENTS.md` when this repository is cloned into caddis-hq's
`repos/`, as bootstrap does, and https://github.com/caddis-tech/caddis-hq/blob/main/AGENTS.md
otherwise. What follows is only what is specific to this repository.

Nothing here is edited by hand, and there is no code. The firmware repository's publish
workflow creates the releases, each carrying the compiled `.uf2` builds and a signed
`manifest.json`, and `DroneSetup.exe` downloads from them. A change to what gets published
belongs in that workflow, not here.

This repository is public. Nothing in it may carry an internal identifier: no cloud project
IDs, no CI secret names, no board numbers.
