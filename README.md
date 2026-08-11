> The machines and the people who would actually keep the network running when there is no data centre to rent.

**The physical side of a network with no data centre.**

Physical and virtual support, distributed across the people and machines that actually run the network: the machines that hold it up, the people who keep them running, and whatever makes it worth their while to keep doing it.

## The problem it addresses

A network without an owner still runs on hardware someone paid for. If the support layer is not designed, the network quietly re-centralizes around whoever can afford to host it.

**How it works today.** Distributed systems still end up hosted by a handful of companies, which is where control quietly returns.

**What would change.** Capacity is contributed by many independent parties, and what they are owed for it is part of the design.

**Why the rest depends on it.** With no answer to who runs the machines, decentralization is a diagram.

## Where this stands

Drayker has internal material on support stations, centres and embassies that has not been published; what a support node is, what it owes the network and what the network owes back are all still open. The first public document about it is what makes it real for everyone else.

Nothing described here is implemented. This repository exists so that the first
document about it has somewhere to live and someone can argue with it in public.

## Scope

- Support nodes, physical and virtual
- Relation to Dk Network and LCrypt
- What the network owes a node
- Failure and replacement of a node

## Not in scope

- A deployed support network or any commitment of hardware.
- A payment, reward or compensation scheme for running a node.

## Role in the system

The hardware a network with no data centre would run on.

**Relations.** Sits under Dk Network · secured by LCrypt · its incentive overlaps DAF federative points.

**Depends on.** `dknetwork` · `lc` · `daf`

## First functions

These are concrete and unclaimed. Any of them can be opened as an issue and delivered
by one person.

1. Write the first description of what a support node is.
2. Model the incentive against the DAF federative points.
3. Map which parts of the network cannot run without it.

## How to contribute

Read [CONTRIBUTING.md](https://github.com/draykerdk/.github/blob/master/CONTRIBUTING.md)
and [GOVERNANCE.md](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md) in
the organization. In short: open or find an issue, say in the thread that you are taking
it, branch as `fn/<issue-number>-<short-name>`, and open a pull request against
`master`. There is no separate review branch.

Participation is voluntary and implies no compensation, employment or future claim.

## Sources of truth

- This repository, for what Distributed support is and is not.
- [`.drayker/component.yml`](.drayker/component.yml) — the machine-readable contract,
  validated on every pull request.
- [drayker.org/project/dsupport/](https://drayker.org/project/dsupport/) — the same record
  inside the portal, with the live board.
- [drayker.com/project/dsupport/](https://drayker.com/project/dsupport/) — the case for it,
  in plain terms.

---

Part of [Drayker](https://drayker.org) · content under CC BY 4.0
