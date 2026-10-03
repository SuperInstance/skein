# The Receiver

**The default is supervision. Automatic is the exception that requires active permission.**

## The 2-bit system

The watcher's signal has four states:

| Signal | Watcher | What runs |
|--------|---------|-----------|
| **Yes** | present, approves | routine A |
| **No** | present, redirects | routine B |
| **Manual** | present, escalates | human / higher model |
| **Silence** | absent | **nothing automatic** |

The receiver — the cell that interprets the signal — treats **manual and silence identically**: keep watching as if it's manual. Don't run automatic routines. Stay alert for change.

But they mean different things. *Manual* = the watcher chose to take over. *Silence* = the watcher is gone. The system must distinguish them because *watcher gone* is itself an emergency — the supervision the routines depend on has vanished, and nobody chose that.

## Why silence isn't yes

The 99 okays were active endorsements, not passive absence-of-objection. Silence isn't endorsement. And the routines were only ever safe *under supervision* — the woodcutter chopping with no one watching the map isn't degraded, it's unsafe.

**Fail to manual, not to automatic.** If the watcher goes quiet, hold. The burden of proof is on proceeding, not on halting.

## Watchers all the way up

The receiver doesn't hand off and sleep. On manual: it watches the manual operator. On silence: it watches *for the watcher.* Every cell watches the cell below. Captain watches the autopilot. Receiver watches the captain. The next cell watches the receiver. All the way up to the human.

## As vocabulary

*The receiver* (noun) — the cell that interprets a watcher's signal and manages what runs. *Receive* (verb) — to hold the 2-bit state and enforce the default-to-supervision rule. *No signal* — the fourth state, treated as manual by the receiver, flagged as unconfirmed. *Fail to manual* — the design principle: silence stops automatic, never permits it.
