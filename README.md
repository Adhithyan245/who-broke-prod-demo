# WHO BROKE PROD? — static demo

An AI incident investigation where everyone is confident and the logs disagree.

This is a static demo of a **controlled, deterministic simulator**. Scripted rule-based agents blame
each other for a simulated outage, and an investigator checks their claims against a simulated event log.
The page replays 4 fixed scenarios × 3 coordination topologies from a pre-built JSON bundle (`data/`).

- No real systems, people, incidents or data. No API keys. No network calls beyond loading these files.
- Results describe the simulator only and say nothing about real engineering teams or organisations.
- Limitation: verdict files in `data/verdicts/` are public, so a verdict can be opened before the reveal.
