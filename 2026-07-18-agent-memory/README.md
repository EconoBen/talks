# Agent Memory

**Applied AI Conference 2026**, hosted by GDG Chapel Hill
Chapel Hill, North Carolina, July 18, 2026. 29 slides, 29 minutes 55 seconds.

An agent hits a timeout, retries, and charges the customer twice. I use that to work through the difference between context and memory, where an organization's evidence actually lives, what is worth keeping, and how you would prove that remembering changed what the agent did. From the first chapters of my O'Reilly book, *Agent Memory*.

## Links

- Video: https://youtu.be/4SjLQAIiDoM
- Transcript: https://econoben.dev/transcripts/agent_memory_applied_ai_2026.txt
- Talk page: https://econoben.dev/talks

## Files

| File | What it is |
| --- | --- |
| `agent-memory.pdf` | The deck as delivered, exported to PDF |
| `agent-memory.pptx` | Source deck, if you want the build order and speaker notes |

## What the talk covers

The spine is one purchasing incident, followed end to end.

A call to a vendor's purchase API times out. The obvious fix is a retry, and the retry is what causes the duplicate charge, because a timeout says the response was lost, not that the write never happened. That gap is where the talk lives.

From there it works through the difference between context and memory, five stages that turn scattered company documents into evidence an agent can reach, deciding which encounters are worth keeping, the split between semantic, episodic, and procedural memory, what to do when a kept memory goes stale, why forgetting is rarely deletion, and how you would actually measure whether memory changed an agent's behavior.

It closes by replaying the same timeout against an agent that kept the right evidence.

## Colophon

The mascot in the corner of each slide is Atlas, my dog. The bird on the book cover is O'Reilly's choice, not mine.
