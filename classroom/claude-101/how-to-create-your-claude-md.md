# How to Create Your CLAUDE.md File

Your CLAUDE.md is the brain of your business repo. It's the one file Claude reads at the start of every single session. Get it right and Claude works like a team member who's been with you for a year. Get it wrong (or skip it) and you'll re-explain your business every time you open a new chat.

Here's how to build one that actually works.

## The One Rule That Matters

Your CLAUDE.md should only contain things Claude **can't figure out by looking at your files**.

Claude can read your folders. It can find your past content. It can see what's in your repo. What it can't see is what's in your head: who you are, what you sell, who buys it, how you talk, and the rules for how you want Claude to behave.

That's what goes in CLAUDE.md. Context and judgment, not inventory.

## A Quick Word on /init

Claude Code has a built-in command called `/init`. Run it in a project and Claude scans everything (folder structure, existing docs, README) and generates a starter CLAUDE.md from what it finds.

Here's the catch: `/init` was built for software projects. On day one of a business repo, there's nothing in the files yet. It can map your folders, but it can't discover your offer, your customer, or your voice. Those only exist in your head.

So `/init` handles the mechanical half. The interview handles the half that matters. If you're using the starter kit, skip `/init` entirely, the template is already built for you. Just run the interview.

## Step 1: Run the Interview

In the starter kit, type `/setup-coach` and Claude interviews you, one question at a time, then writes the file for you. It takes about ten minutes.

If you're building a CLAUDE.md from scratch somewhere else, say: "Interview me one section at a time to build my CLAUDE.md. After each section, draft that part of the file and show it to me before moving on." Then answer these 7 groups of questions:

**1. The Business in One Breath**
- What do you sell, to whom, and what does it cost?
- What's your current monthly revenue and your target?
- What's the single biggest bottleneck right now?

**2. The Customer**
- Describe your best customer: where they are now, where they want to be, and what they've already tried that failed.
- What exact words do they use to describe their problem? (This feeds every piece of copy Claude ever writes for you.)

**3. Voice**
- Paste 2 or 3 things you wrote that sound most like you. (This works better than trying to describe your voice. Nobody can describe their own voice.)
- What phrases do you say all the time? What words or styles do you never want in your content?

**4. Proof**
- What results can you claim that are true and verifiable? Revenue, client counts, awards.
- What are you NOT allowed to claim? (This one rule prevents more damage than any other.)

**5. The Offer Stack**
- Walk through every tier: name, price, what's included, how someone buys it.
- Anything retired that Claude should never mention?

**6. Team and Tools**
- Who's on the team and who owns what?
- What tools run the business? CRM, email platform, community platform, which accounts.

**7. Rules of Engagement**
- What should Claude always do before writing content for you?
- What should it never do without asking?
- What has an assistant or AI gotten wrong for you in the past? (Gold. This surfaces your real rules.)

Close with one last question: "What would you only learn about my business after working with me for a month?"

## Step 2: Let It Grow From Corrections

Here's what most people miss. The best lines in your CLAUDE.md won't come from the interview. They'll come from Claude getting something wrong and you correcting it.

So make sure this rule is in the file from day one (the starter kit template already includes it):

> "When I correct you or express a preference, ask me if it should be added to CLAUDE.md."

Now every real correction becomes a permanent rule. After two weeks of actual work, your file will be full of battle-tested rules like "never use this phrase," "always check the offer doc before writing sales copy," and "never claim numbers we can't verify."

Interview answers are guesses. Corrections are proof. You want both.

## What a Finished CLAUDE.md Looks Like

Seven sections, in this order:

1. **The Business:** what you sell, current numbers, biggest bottleneck
2. **The Customer:** who they are, their words, what they've tried
3. **Voice:** tone, key phrases, banned words
4. **Proof:** what you can claim, what you can't
5. **The Offer:** every tier, every price, what's retired
6. **Team and Tools:** who does what, what runs the business
7. **Rules:** the always-do and never-do list

A note if you're using the starter kit: your template already has its own version of these sections with friendlier names, like "What I Do" and "My Big Promise." Same idea, same order of importance. Use the sections your template ships with, they map to everything above.

Keep it tight. If a section starts getting long, move the detail to its own file (like `reference/offer.md`) and leave a one-line pointer in CLAUDE.md. The file loads every session, so every line costs you.

## Do This Now

1. Type `/setup-coach` (or run the interview above, 30 minutes, one section at a time)
2. Make sure the correction rule is in your Rules section
3. Start working. The file improves itself from here.

Done is better than perfect. A rough CLAUDE.md today beats a perfect one you never write.
