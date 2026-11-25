# child

A child mrepo deployed, read through its parent, redeployed and torn down.

From the boot mrepo (`.`), the host is a child; from the host, a node.
Each is built from a package's list, placed by its unique URI
(`local/host`, `local/node-1`), runs its own runtime and is reached
through its parent by its shortcut.

## Steps

The script, [steps.haicc](steps.haicc): each line as typed after `haicc`, what it answers under it; run with `howto/run`, shown here at info extraction.

## Notes

- **Tear down from the inside out**: a child's own children are not
  torn down with it.
- **What the install's mrepos are**: the work folder's `mrepos/`, the
  boot component's how-to `registry`.
- **Again**: a deploy of what is there, a teardown of what is not: a
  warning, nothing done (idempotent).
