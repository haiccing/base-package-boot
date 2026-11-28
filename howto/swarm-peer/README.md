# swarm-peer

A swarm's peer deployed: a child in a swarm of its own rather than its parent's.

A child is in its parent's swarm (`local`), unless a node above it says
it is a swarm, `{"kind":"swarm"}`: then it is that swarm's peer, its
unique URI `<swarm>/<name>`, by the swarm node's name. The swarm's node
is made first.

## Steps

The script, [steps.haicc](steps.haicc): each line as typed after `haicc`, what it answers under it; run with `howto/run`, shown here at info extraction.

## Notes

- **The swarm `local`** is refused as a swarm's name: it is the
  machine's own.
- **Where the swarm's node is** is the structure's: `swarms/` is the
  haicc component's way, any position works.
