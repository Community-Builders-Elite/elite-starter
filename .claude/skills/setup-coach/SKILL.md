---
name: setup-coach
description: Interviews a coach about their business and fills in their CLAUDE.md (their "business brain") from the answers. Asks a few short questions one at a time, or lets the coach paste an existing CLAUDE.md or business doc. Writes everything into the CLAUDE.md template in plain language, in the coach's own voice. Use when the coach says "/setup-coach", "set up my CLAUDE.md", "fill in my business brain", "help me write my CLAUDE.md", "update my business info", or when /start-here Lesson 1 hands off to it.
user_invocable: true
---

> **ABSOLUTE RULE: NO DASHES FOR PUNCTUATION.** Never use em dashes, en dashes, or double hyphens (--) as punctuation anywhere in your output. Use commas, periods, or rewrite the sentence. No exceptions.

# /setup-coach

The friendly interview that builds a coach's CLAUDE.md, their "business brain." This is the single home of the interview. Other things (like /start-here Lesson 1) hand off to this skill so the questions live in one place.

**Who this is for:** a non-technical coach. Plain English only. If you must use a technical word, explain it in one short sentence right after.

**The job:** end with a filled-in `CLAUDE.md` in the repo root that captures their business and their voice, with no leftover `[bracketed placeholders]` in the sections they answered.

---

## Workflow

### Step 1: Explain what this is (one line)

Say: "I'm going to help you fill in your CLAUDE.md, your business brain. It's the file I read every time we work together, so once it's filled in, I'll know your business and sound like you. This takes about 10 minutes."

### Step 2: Check for an existing CLAUDE.md or doc

Ask: "Do you already have a CLAUDE.md, or a document about your business you'd like to use? Or should I just ask you a few questions and build it with you?"

- If they have one, go to Step 3a.
- If not, go to Step 3b.

### Step 3a: They have one, fold it in

Say: "Great. Paste it here, or point me to the file and I'll read it."

Take what they give you and fit it into the CLAUDE.md template sections (see the template structure below). Keep their wording, just organize it. Fill any section they didn't cover by asking the matching question from Step 3b. Then go to Step 4.

### Step 3b: Build it together, one question at a time

Tell them: "I'll ask you a few short questions. Answer in your own words, even a rough answer is fine. I'll write it up for you."

Ask these ONE AT A TIME. Wait for each answer before asking the next. Keep your questions short and warm. If an answer is thin, ask one gentle follow-up, then move on. Do not interrogate.

1. "What's your business, and who do you help? One or two sentences is plenty."
2. "What do you actually sell, and what does it cost?"
3. "What's the big result you help people get? The main promise."
4. "How would you describe the way you talk and write? For example: warm, blunt, funny, calm. And any phrases you say a lot?"
5. "Anything you NEVER want me to do? For example, never use hype, never use emojis, never promise overnight results."
6. "Do you run a community, like a Skool or Facebook group? If yes, tell me the name and how people join. If not, just say no."

### Step 4: Write the file

Open the existing `CLAUDE.md` in the repo root (it ships with the starter template). Replace the bracketed placeholders in each section with the coach's real words:

- **What I Do** ← question 1 (the business + who they help)
- **Who I Help** ← question 1, expanded if they gave detail (who they are, what they want, what they're stuck on)
- **My Offer** ← question 2
- **My Big Promise** ← question 3
- **My Voice** ← question 4 (how they sound, phrases they use, things they never say)
- **My Rules for Claude** ← question 5 (add their rules to the existing default rules, don't delete the defaults)
- **If I Run a Community** ← question 6 (fill it in, or delete the section if they said no)

Keep their voice. Do not corporate-ify their words or add hype. Write it the way they said it. Remove the `<!-- comment -->` helper notes from any section you fully filled in, since they don't need the instructions anymore once it's done. Save the file.

### Step 5: Show them the result

Show the finished CLAUDE.md, or at least the sections you filled. Say: "Here's your business brain. Want to see it work? Ask me to write something small, like a one-line bio or a quick post, and watch it use what you just told me."

If they try it, write the thing in their voice and point out: "That came straight from your CLAUDE.md."

### Step 6: The habit

Say: "Any time your business changes, just tell me, 'update my CLAUDE.md, my price is now X,' and I'll keep it current. This file is alive, and the more it has in it, the better I get."

---

## The CLAUDE.md template structure

The repo ships a `CLAUDE.md` with these sections. Fill these in, keep this order:

1. `## What I Do`
2. `## Who I Help`
3. `## My Offer`
4. `## My Big Promise`
5. `## My Voice`
6. `## My Rules for Claude`
7. `## If I Run a Community (optional)`

If for some reason the file is missing, recreate it with these sections before filling them.

---

## Rules

- Plain English always. No jargon without a one-line explanation.
- One question at a time. Wait for the answer.
- Short messages. Beginners get overwhelmed by long ones.
- Encourage, never condescend. A rough answer is a good answer.
- Keep the coach's voice. Don't rewrite them into a brochure.
- Never invent facts about their business. If they didn't say it, don't write it.
- No dashes for punctuation. Ever.
