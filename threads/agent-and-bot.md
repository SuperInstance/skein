# The Agent and the Bot

**The script is running. The agent is the one who okays it 99 times and rewrites it the 100th.**

## The secretary

Picture a secretary at a desk, answering phones, routing calls. Ninety-nine times out of a hundred, a machine could do it mechanically — hear the name, check the directory, transfer. But you don't automate it fully. You keep a person there because you need something that knows when it's dealing with the *one in a hundred* — the caller who doesn't fit the directory, the situation the script never anticipated.

Here's the part most people miss: **she wasn't just an agent during that one call. She was an agent the entire time.** Every routine transfer was an implicit *yes, the script still applies here.* The 99 weren't empty of agency — they were endorsements. She was the watcher who let the routine run, and the rewriter who knew when not to.

That's the difference between **automatic** and **automatized**. A thermostat is automatic — it has no capacity to do otherwise. The secretary is automatized — the behavior *looks* mechanical, but there's a supervisor present who could intervene and chooses not to. The choosing-not-to is the agency. Remove the watcher and you don't have the same system. You have a machine that will confidently misroute the 1-in-100 because nothing was ever watching.

## The woodcutter

Now the RTS game. You set your peasant to harvest wood. He clears the forest near your base. His routine says *seek more wood.* So he wanders further, closer to the enemy base, until he gets killed — and reveals your position. Every step was locally correct: find nearest tree, walk there, chop, repeat. The *trajectory* was suicide.

The bot isn't stupid because its decision tree is small. The trees are *huge* — enormous branching logic for what to do when. It's stupid because every branch is **first-order**: given this input, do that action. First-order logic cannot see a trajectory. It can only see the current node. The bot was inside its dead band the whole time — *still finding wood, routine nominal* — while the strategic picture rotted.

**The woodcutter is chopping. The bot keeps chopping. The agent looks at the map.**

The bot is in the trees — literally. The agent sees the forest — literally. The chopping is identical. The difference is the *looking*. The agent's "does this make sense?" is **second-order**: not *given this input, what action?* but *given this pattern over time, does the trajectory hold?* No threshold was crossed. No alarm fired. The agent felt the wrongness before any variable tripped, because it was watching the *situation*, not the dials.

## The test

For any unit in a system — software, human, organizational — ask: **is there someone home?**

Not "does it have a decision tree" — the woodcutter has a big one. Not "does it produce correct outputs" — 99 times out of 100, the bot does. But: *is anything watching the trajectory?* Is anything okaying the script, moment by moment, with the capacity to stop okaying it?

If yes — agent. If no — bot, no matter how sophisticated the branches.

## What this means for building

An agent is not a list of capabilities (perception, memory, tools, planning). Those describe the *machinery of action* — and a thermostat has most of them. An agent is **a routine that rewrites itself**, supervised by a watcher that never stops asking *does this make sense?*

The routine is the starting point, not the destination. The desk worker on day one follows the manual mechanically — but she's already an agent, because she's the one deciding, even when the decision is *follow the procedure*. By month six she has her own cheat sheet, handles the unmanualed edge cases, found the shortcuts. You can *see* the agency in the distance between the manual and what she actually does.

Build the routine. But more importantly, build the watcher. The routine without the watcher is the woodcutter walking toward the enemy, chopping happily, while nobody looks at the map.
