# howtos-node

A how-to's mrepo deployed below a howtos node: its unique URI the path below it.

A node whose document says `{"kind":"howtos"}` is the root of a
namespace: an mrepo below it has the path below it as its unique URI,
a how-to's key (`<org>/<package>/howto/<name>`) then its own name. It is
placed by that path under the work folder's `mrepos/`, the install's
registry, and linked at its position. No unique URI is a prefix of
another's: an mrepo inside another's folder is refused.

## Steps

The script, [steps.haicc](steps.haicc): each line as typed after `haicc`, what it answers under it; run with `howto/run`, shown here at info extraction.

## Notes

- **One name below it** is no unique URI: a namespace and a name at
  least.
- **A swarm in a how-to's namespace**: what a how-to's mrepo deploys is
  in its namespace, a swarm's peers too
  (`.../howto/query/swarm-1/peer-1`).
