# golden-retriever-skill

![alt text](gif.gif)

A Claude Code skill that explains anything dense — a system, a bug, a
financial model, a legal clause, a diff — the way John Tuld demanded in
*Margin Call*:

> "Maybe you could tell me what is going on. And please, speak as you
> might to a young child, or a golden retriever."

## What it does

Takes something complicated and gives you back the plain-English version a
smart non-expert gets in one read. No jargon, short sentences, plain
analogies, and the "so what" at the end.

## How to use

Type `/golden-retriever` followed by what you want explained — a URL, a
file, a pasted error, a concept:

/golden-retriever https://.../some-dense-design-doc
/golden-retriever why is this query slow?

Or just say "explain it simply", "ELI5", "dumb it down", or "plain
English" and the skill kicks in.

## The rules it follows

- **Punchline first.** The one sentence that matters leads.
- **No jargon.** Terms get replaced with their meaning.
- **Plain analogies.** A leaky bucket, a queue at a shop, an overdrawn
  account.
- **Small words, short sentences.** One idea each.
- **Why before how.** Consequence first, mechanism only if asked.
- **Numbers with a size.** "As much as we make in a year," not just a
  value.
- **Ends with the "so what."** One line on what happens next.

## Turning it off

It stays on once triggered. Say "stop", "normal mode", or ask for the full
detail to switch back.
