# aquadrone-firmware-releases

This repository follows the Caddis engineering standards. Read them before your first edit,
commit, or pull request: `../../../AGENTS.md` when this repository is cloned into caddis-hq's
`repos/`, as bootstrap does, and https://github.com/caddis-tech/caddis-hq/blob/main/AGENTS.md
otherwise. What follows is only what is specific to this repository.

**If this copy is not inside caddis-hq, say so first.** Look for caddis-hq in the folders above
this one: a folder that holds both `repos.yml` and `AGENTS.md`. If there is none, tell the person
once, at the start, in plain words: this copy was not set up through caddis-hq, so the shared
rules, the step-by-step guides in its `docs/`, and the other repositories this one works with
are not here. The fix is to clone caddis-hq, run its bootstrap script as its README says, and
start again from the copy that makes. Until then, read the standards with
`gh api repos/caddis-tech/caddis-hq/contents/AGENTS.md -H "Accept: application/vnd.github.raw"`,
and if that fails too, say you are working without them.

Nothing here is edited by hand, and there is no code. The firmware repository's publish
workflow creates the releases, each carrying the compiled `.uf2` builds and a signed
`manifest.json`, and `DroneSetup.exe` downloads from them. A change to what gets published
belongs in that workflow, not here.

This repository is public. Nothing in it may carry an internal identifier: no cloud project
IDs, no CI secret names, no board numbers.

There is nothing to check before a commit, because nothing is committed here by hand. A release
here reaches every technician, so an assistant never creates, edits, or deletes one.
