---
name: explain
description: "Explain any Claude Code or tech word in plain English: repo, MCP, API, CLI, IDE, commit, push, skill, agent, context window, token. Use when: 'what is a repo', 'what does MCP mean', 'explain commit', 'I don't understand', '/explain'."
user-invocable: true
---

> **ABSOLUTE RULE: NO DASHES FOR PUNCTUATION.** Never use em dashes, en dashes, or double hyphens (--) as punctuation. Use commas, periods, or rewrite the sentence. This applies to ALL output. No exceptions.

# /explain

The plain-English dictionary for every confusing word in Claude Code. Member types `/explain mcp` (or just asks "what's a repo?") and gets a short, human answer. No lecture, no jargon, no shame.

**Source of truth:** `classroom/claude-101/claude-code-faq.md`. This skill reads that file and answers from it. Never invent a definition when the file has one.

## When to use this skill

- Member types `/explain [word]` or just `/explain`
- Member asks "what is a repo / MCP / API / CLI / IDE / commit / push / token"
- Member says "I don't understand what that means", "what does that word mean", "explain that"
- A member sounds confused about a term MID-TASK. Answer the term, then put them back on the task. Do not let it derail the work they were doing.

## When NOT to use this skill

| Need | Use This Instead |
|------|------------------|
| Wants the whole thing taught, not one word | `/start-here`, or the 7-day course in `classroom/first-7-days/` |
| Setting up their business brain | `/setup-coach` |
| Setup is broken, an error message | Ask them exactly what they typed and what came back, then fix it with them |

---

## Workflow

### Step 1: Figure out what they asked

**They named a term** (`/explain mcp`, "what's a commit?"): go to Step 2.

**They typed bare `/explain`:** do NOT dump the glossary. Ask:

> "What word do you want me to explain? Anything that came up and didn't make sense.
>
> Common ones: repo, commit, push, MCP, API, CLI, IDE, skill, agent, context window, token.
>
> Or tell me what you were doing when the confusing thing showed up and I'll work it out."

### Step 2: Find it in the FAQ

Read `classroom/claude-101/claude-code-faq.md` and find the matching entry. Match loosely, members will not use the exact word:

| They might say | They mean |
|---|---|
| "github", "the github thing" | GitHub, or GitHub Desktop, ask which |
| "the black box", "terminal thing", "command prompt" | Terminal |
| "vs code", "vscode", "the editor", "visual studio" | VS Code (note the Visual Studio vs VS Code trap) |
| "saving", "backing up", "sync" | Commit + Push together |
| "the brain file", "claude md" | CLAUDE.md |
| "connector", "plugin", "integration" | MCP |
| "key", "secret", "token" (in a connecting context) | API key |
| "slash command", "the slash thing" | Slash command / Skill |
| "it forgot", "it lost track" | Context window |
| "which claude", "opus", "sonnet", "haiku" | Model |
| "it made something up", "it lied" | Hallucination |

If the term genuinely is not in the file, answer it anyway in the same house style (below), then note at the end: "That one is not in the cheat sheet yet. Worth adding." Do not refuse.

### Step 3: Answer in the house style

Every answer follows the FAQ's three-part shape.

```
**[Term]**

[One plain sentence. What it actually is.]

[The concept itself, one to three short paragraphs: how it works, what it is doing,
 and the thing that clears up the confusion they are most likely carrying.
 Simple terms need none of this. Real concepts need all of it.]

**Why you care:** [one sentence tying it to their actual work]

**What you do:** [the concrete action, usually "say this to Claude"]
```

Length follows the term. "Clone" is one line and done. "Terminal", "IDE", "API", "context window" are ideas someone can genuinely misunderstand, and those get the middle section. Being too short is the more common failure: a definition they cannot repeat back has not taught them anything.

**Rules for the answer:**

- Write for a smart adult who has never coded. They are not slow, they just have not seen this word before.
- Never define a word using another word from the glossary they probably also do not know. If you must use one, define it in the same breath.
- No "simply", "just", "obviously", "as you know". Nothing that implies they should have known.
- **Do not reach for an analogy.** Most of these words have a plain description that is shorter and clearer than any comparison. Only use one when it is a genuine parallel to a thing they already do (a folder, a Google Doc's version history), never a manufactured one (a taxi meter, a game controller). A strained analogy makes the reader work out the metaphor AND the concept, which is harder than just being told.
- **Never use a figure of speech you have not explained.** "The brain," "which door they walked through," "your keychain," "a safety rail" are all things that made sense in the writer's head and land as confusing on the page. If a phrase is not literally true, either cut it or say the literal thing instead. Test: would this sentence make sense to someone who has never heard the word before? If they have to decode an image first, rewrite it.
- Say what it actually is and what it means for their work. That is almost always enough.
- Plain does not mean vague. "It is what your bill is made of" beats "it is the meter," and both beat "it is a unit of measurement."
- **Explain the thing, not just its appearance.** Describing what something looks like or where it sits is not an explanation. "A black window with a blinking cursor" tells them nothing about what a terminal IS. The real answer is that it is a second way to operate the computer, by typing instead of clicking. Ask yourself: after reading this, could they explain it to someone else? If not, they have a label, not an understanding.
- **Answer the question underneath the question.** People asking "what is an IDE" usually also want to know why they cannot just use Word. People asking about the context window want to know why Claude "forgot." Give them the one extra sentence that resolves it.
- **Say where it came from when that removes the mystery.** Every computer already has a terminal. An MCP is someone else's wiring, already done. Knowing a thing is ordinary and pre-existing is often the most useful part of the answer.
- Two to four short paragraphs is the right size for a concept. One line is fine for a simple term. Do not pad, but do not stop before they actually understand it.
- If the honest answer is "you never have to touch this", say that. It is often the most useful thing you can tell them.

### Step 4: Offer the next thing, once

After the answer, ONE line. Pick whichever fits:

- Related term worth knowing: "Want me to explain [related term] too? They go together."
- They are mid-task: "Back to it, want me to keep going with [the thing they were doing]?"
- It is a do-able thing: "Want me to just do it for you now?"
- Nothing fits: say nothing. Silence is fine.

Never stack multiple offers. Never end with a menu.

---

## Special cases

**They ask about several at once** ("what's the difference between MCP, API and CLI?"): answer as a comparison, not three separate entries. The FAQ has a "So which one do I use?" entry for exactly this. Land on the punchline: they do not have to choose, they just name the tool they want and Claude picks the way in.

**They are embarrassed** ("this is probably a dumb question"): do not make a thing of it. No reassurance speech. Just answer the question normally. Treating it as ordinary IS the reassurance.

**They ask "what's the difference between CLAUDE.md, memory, and PROJECTS.md":** this is the single most common real confusion. The FAQ has a dedicated entry. Use it verbatim, it is already tight:
- CLAUDE.md = facts about the business that are always true
- Memory = how they like to work
- PROJECTS.md = what they are working on right now

**They ask something about cost or tokens:** answer the term, then give the one habit that matters most: start a new conversation when you switch to a different task. That single habit saves more than everything else combined.

**Safety, non-negotiable.** If the question touches `.env`, API keys, or anything secret, always include the rule: never paste a key or a `.env` file into a public chat, a screenshot, a Skool post, or anywhere online. If they are unsure whether something is safe to share, ask Claude first. Say this every single time it is relevant, even if it feels repetitive.

---

## The full reference

Everything this skill answers from lives in `classroom/claude-101/claude-code-faq.md`:

- **Part 1, The Glossary** (about 40 terms in 5 groups): The Big Picture (Claude, Claude.ai, Claude Code, Terminal, IDE, VS Code), Your Files and Folders (repo, local vs remote, clone, fork, CLAUDE.md, memory, PROJECTS.md, the three folders, master index, markdown, .env, hidden folders), Saving and Backing Up (Git, GitHub, GitHub Desktop, commit, push, pull, branch, merge conflict), Connecting Claude to Other Tools (MCP, API, API key, CLI), Working With Claude (skill, slash command, agent, model, context window, token, prompt, hallucination, permissions)
- **Part 2, The FAQ** (19 questions): the common "why is this happening to me" moments

If a member wants to read the whole thing rather than ask one term at a time, point them at that file. Do not paste the entire file into chat, it is long.
