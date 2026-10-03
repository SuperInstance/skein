# The Scroll

**Share the trajectory, not the interior. The quilt as a federated learning system.**

## The visible learning

When an agent learns by ticking back and forth with its environment — observe, act, observe, correct — every tick can be logged. Input, output, state change. The overcorrection on tick 47. The adjustment on tick 48. The moment it clicks on tick 132.

This isn't just a record. It's the **learning itself, made visible.** Not the final distilled model, but the *process* of getting there. You can scroll back and watch the agent figure it out.

## Federated across cells

Cell A (excavator) logs its entire learning trajectory. Cell B (bulldozer — similar but different) doesn't start from zero. It reads A's scroll:

- Not the raw sensor data (stays in the room)
- Not the interior distributions (stays in the room)
- The *interaction pattern*: when ground was soft, bucket speed dropped by X; when the load shifted, counter-rotation increased by Y

The *shape* of the learning transfers. The discovery phase gets skipped. This is federated: **each cell's interior stays private; what crosses is the distilled trajectory.** Enough to learn from, not enough to see inside.

## Faster and smaller

As the system matures, learning moves *out* of model weights and *into* the interaction loop. What was once "retrain the model" (weeks, GPUs, opaque) becomes:

- A binary check nudging its threshold (one tick)
- A pruned model updating a gain (a few ticks)
- An agent switching routines (one decision)
- A room adding an instrument (one externalization)

The network gets smarter through *interaction*, not through *training runs.* The frontier model remains the source of novel intelligence. But the *accumulation* lives in the scrolls, in the rooms, in the shared patterns — not in any single set of weights.

## As vocabulary

*The scroll* (noun) — the visible tick-by-tick trajectory of an agent learning. *Read the scroll* — to learn from another cell's interaction history. *Scroll-sharing* — the federated mechanism: trajectories cross, interiors don't. *Tick* (noun/verb) — one observe-act-observe cycle; the atomic unit of visible learning.
