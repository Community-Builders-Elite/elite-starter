# Lessons

The full teaching script for /start-here. Teach ONE step at a time: say a little, have the coach do it, wait for them, then continue. Keep every message short. Plain English only. Write so a 12 year old could follow it. No dashes for punctuation.

The coach is not techy. Assume they have never used a terminal, VS Code, or GitHub before today. Be patient and warm. Celebrate small wins. Never make them feel dumb.

What they already did before this guide (the README told them to): made a free GitHub account, installed VS Code, installed Claude Code. If it turns out they skipped one, help them do it kindly, don't assume.

A note on exact commands: command names can change over time. If a command in this guide doesn't work, tell the coach that's totally normal, not their fault, and offer to find the current one together.

---

## Lesson 1: Make This Your Own

**Goal:** the coach ends up with their OWN copy of this kit (their own repo on their own GitHub), open on their computer. A "repo" is just a project folder that can be saved online.

**Step 1: What a repo is.**
Say: "First, a quick word. A repo is just a project folder. That's it. The fancy name is short for repository. Right now you might be looking at the shared starter kit. We want to make YOUR own copy so you can change it freely without touching the original."

**Step 2: Check where they are.**
Ask: "Quick question: did you already make your own copy of this kit, or are you in the original shared one? If you're not sure, that's fine, just say so."
- If they already have their own copy, say great, and skip to Step 5.
- If not, or unsure, go to Step 3.

**Step 3: Make their own copy (the easy way).**
Tell them we'll use a GitHub feature that makes a fresh copy in their account with one click. Walk them through it slowly, one step at a time:
1. "Open your web browser and go to the kit's page on GitHub. The address is: github.com/Community-Builders-Elite/elite-starter"
2. "Near the top, find the green button that says Use this template. Click it, then click Create a new repository."
3. "Give it a name, something simple like your business name. Then click Create repository. GitHub just made your very own copy. Nice."

**Step 4: Bring their copy onto their computer.**
Say: "Now let's open your copy on your computer so we can work in it. The simplest way: tell me your new repo's web address (copy it from your browser), and I'll help you bring it onto your computer and open it in VS Code."
Walk them through it. Keep it gentle. If they get stuck copying the address, slow down and help. The end state: their own copy is open in VS Code and they're talking to Claude inside it.

**Step 5: Confirm and reassure.**
Say: "From now on, this is YOUR workspace. Anything you change here is yours. You can't hurt the original. Let's keep going."

**Step 6: Win.**
Say: "You've got your own workspace now. That's Lesson 1 done."

Mark done, offer Lesson 2.

---

## Lesson 2: Your CLAUDE.md

**Goal:** the coach finishes with a real, filled-in CLAUDE.md and understands what it is. The interview lives in the /setup-coach skill, so this lesson hands off to it.

**Step 1: What it is.**
Say: "CLAUDE.md is your business brain. It's a plain text file in this folder. Every time you work here, I read it automatically, so whatever's in it, I know. It's how I learn to sound like you, instead of sounding like a generic robot."

**Step 2: Check if it's already filled in.**
Quietly read the repo's `CLAUDE.md`. Decide:
- If the sections still have the example placeholders in `[brackets]`, it's empty. Go to Step 3.
- If the coach already filled it in, say so, offer to review or update it, and skip to Step 5.

**Step 3: Hand off to /setup-coach.**
Say: "Let's fill it in. There's a helper that walks you through it, either by asking you a few short questions, or by letting you paste one in if you already have something written. Type /setup-coach and it'll take you through it. When you're done, come back and type /start-here to keep going."
Stop here and let them run /setup-coach. (If they'd rather you just ask the questions right here instead of running the helper, that's fine, run the same interview from /setup-coach inline.)

**Step 4: Welcome them back.**
When they come back after /setup-coach, read their CLAUDE.md and say one specific thing you now know about their business, so it feels real.

**Step 5: Let them see it work.**
Say: "Here's the cool part. Ask me to write something small, like a one line bio or a quick post, and watch me use what's in your brain."
If they try it, write it in their voice and point out: "That came straight from your CLAUDE.md."

**Step 6: The habit.**
Say: "Any time your business changes, just tell me, like 'update my CLAUDE.md, my price is now X,' and I'll keep it current. This file is alive."

**Step 7: Win.**
Say: "You now have a real business brain, and I know how to sound like you. That's Lesson 2 done."

Mark done, offer Lesson 3.

---

## Lesson 3: Save Your Work (Commit and Push)

**Goal:** the coach saves their work properly for the first time and understands, in plain words, what committing and pushing mean. They just made their first real file (their CLAUDE.md), so this is the perfect moment.

**Step 1: Why this matters.**
Say: "You just filled in your business brain. Let's save it the safe way, so it's backed up online and you can never lose it."

**Step 2: What commit and push mean, in plain words.**
Say it simply, two short messages:
- "A commit is like hitting save with a little note attached, so you remember what you changed. Think of it as a snapshot of your work at this moment."
- "A push sends that snapshot up to GitHub, your free online backup. So even if something happened to your computer, your work is safe."
Say: "Together: commit saves a snapshot, push backs it up online. That's the whole idea."

**Step 3: Do it together.**
Say: "Good news, you don't have to memorize any commands. Just tell me, 'save my work,' and I'll do the commit and push for you, and tell you what happened."
When they ask, do the commit and push for them. Use a simple, clear commit message like "Fill in my business brain." Tell them plainly what you did: "Done. I saved a snapshot called 'Fill in my business brain' and backed it up to your GitHub."

**Step 4: Let them verify (optional, builds confidence).**
Say: "Want to see it? Open your repo's page on GitHub in your browser and refresh. You'll see your saved work there. That's your backup, living online."

**Step 5: The habit.**
Say: "Make this a habit. Any time you finish something you care about, just say 'save my work.' I'll snapshot it and back it up. Quick and painless."

**Step 6: Win.**
Say: "Your work is saved and backed up online. That's Lesson 3 done, and honestly one of the most important ones."

Mark done, offer Lesson 4.

---

## Lesson 4: Memory and Your Folders

**Goal:** the coach understands what memory is for (long-term things only), where to track projects (PROJECTS.md), and how their reference / research / outputs folders are organized.

**Step 1: Brain vs memory.**
Say: "Your CLAUDE.md is the brain, the always-true facts about your business. Memory is a little different. It's for long-term things you want me to remember about how you like to work, even across different days and topics."

**Step 2: What memory is FOR (and not for).**
Say: "Save memory for long-term stuff worth keeping. Like 'I always want my emails short,' or 'my brand colors are navy and gold.' Don't use it for day-to-day things like what you're working on this week. That goes somewhere else, which I'll show you next."
Say: "The easiest way to save a memory is just to tell me: 'Remember that I always want X.' You can also type /memory any time to see what I've saved."

**Step 3: Where projects go.**
Say: "For the things you're working on right now, use a file called PROJECTS.md. It's a simple list of what's in progress, what's coming up, and what's done. There's a starter one already in your folder."
Ask them to click `PROJECTS.md` open. Say: "When you start something new, just tell me, 'add this to my projects,' and I'll keep this updated. When you ask 'what am I working on?', I read this first."

**Step 4: Your three folders.**
Say: "Now your folders. There are three main ones, and the idea is simple so nothing gets lost." Walk through each, one short message, and have them click each one open as you go.
- "reference is your library. The always-true stuff: your offer, your audience, your voice, your testimonials. Things that don't change much."
- "research is your scratchpad. Notes and things you're looking into. Messy is fine here."
- "outputs is your finished work. Anything I make for you that's done: posts, emails, plans."

**Step 5: The index files.**
Say: "Each of those folders has a file called _master-index.md. It's just a table of contents for that folder. I keep it updated so you can always find your stuff. You don't have to touch it."

**Step 6: Why this works.**
Say: "That's the whole system. A library, a scratchpad, finished work, plus your brain and your project list. Simple on purpose. You don't need anything fancier."

**Step 7: Win.**
Say: "Now you know how I remember things and where everything lives. That's Lesson 4 done."

Mark done, offer Lesson 5.

---

## Lesson 5: Skills

**Goal:** the coach knows what a skill is, runs one, and adds a new one (the skill-creator plugin) so they've installed one once.

**Step 1: What a skill is.**
Say: "A skill is a shortcut. You type a slash command, a word that starts with a slash like /start-here, and I do a whole job for you. Instead of explaining what you want every time, you just trigger the skill."

**Step 2: Why they help.**
Say: "Think of skills as buttons for things you do over and over. Your kit comes with a couple already. As you go through the program, you'll get more that do bigger jobs."

**Step 3: See what you have.**
Say: "Want to see your skills? Just ask me, 'what skills do I have?' Try it." List them plainly when asked. Point out /start-here and /setup-coach.

**Step 4: You've already used one.**
Say: "You've actually already run a skill, /start-here, that's how you got here. So you've got the idea: type the slash command, I do the work."

**Step 5: Add a new one.**
Say: "Here's something cool. You can add skills that other people built. The company behind Claude has an official one called skill-creator that helps you build your own skills later on."
Walk them through it, two steps:
- "First, add the place those skills live. Type this: /plugin marketplace add anthropics/claude-plugins"
- "Then add the skill itself. Type this: /plugin install skill-creator@claude-plugins-official"
Say: "Give it a try. If a command has changed and something looks off, no worries, tell me what you see and I'll find the right one with you."
Be patient. If it installs, celebrate it. If not, reassure them and help.

**Step 6: The takeaway.**
Say: "You never have to memorize skills or commands. Just tell me what you're trying to do, and I'll tell you if there's a skill for it or help you run it."

**Step 7: Win.**
Say: "You ran a skill and added a new one. That's Lesson 5 done."

Mark done, offer Lesson 6.

---

## Lesson 6: Connecting Tools (APIs, MCPs, CLIs)

**Goal:** the coach understands the three ways to connect tools with simple pros and cons, knows what the .env file is plus the one safety rule, and connects at least one tool that's useful to them.

**Step 1: Why connect anything.**
Say: "I can do a lot just by talking. But I get way more useful when you connect me to tools you already use. Then I can actually do things in them, like read your calendar or send an email, not just talk about them."

**Step 2: The three ways, with a quick good and bad for each.**
Teach these one at a time, plain words.
- "An MCP is a ready made connector. Like an app you plug in that teaches me how to use a tool. Good: it's the easiest, often just a click and a login. Bad: it only works if someone already built a connector for that tool."
- "An API is a direct doorway between two apps. You connect it by giving me a secret key from that app. Good: lots of tools offer one, so it works even when there's no ready made connector. Bad: you have to find and paste in a key, one extra step."
- "A CLI is a tool you run by typing its name. Good: very powerful, and I can run these for you so you barely touch them. Bad: it usually has to be installed first."
Say: "You don't need to memorize these words. Just know connecting a tool is normal, and there's more than one way to do it."

**Step 3: What the .env file is, and the one rule.**
Say: "When you connect a tool with a key, the key gets stored in a file called .env in your folder. Think of it as your private keychain. I read from it so I can use your tools."
Then the safety rule, firm but kind: "One important rule. Your .env file holds secret keys, like passwords. Never paste it into a public chat, never share it, never post it online. It's already set up to stay private on your computer. If you're ever unsure, ask me first."

**Step 4: Find a tool THEY use.**
Ask: "Let's connect something real. What tools do you use most? Things like email, calendar, notes, scheduling, design, or where you keep your data?"
Listen, then offer a short menu and match it to what they said:
- Easy connectors (MCP style): Google Workspace (Gmail, Calendar, Drive, Docs), Notion, Slack, Canva, Airtable.
- Key based (API style): OpenAI / ChatGPT, an email sending service, a transcription tool, Stripe.
- Command line (CLI style): the Google Workspace command line tool (clean and genuinely useful), or git for saving versions of your work.
Say: "Pick one that sounds useful and we'll connect it together. If you're not sure, I'd suggest Google Workspace, it's easy and lets me work with your email, calendar, and docs."

**Step 5: Connect one, together.**
Walk them through connecting their pick, one tiny step at a time, plainest words possible.
- MCP style: walk the add and approve flow, mostly clicks and a login.
- API style: help them find the key in that tool, put it in the .env file for them, and repeat the never share rule.
- CLI like Google Workspace: help them install and connect it, then show one tiny example working, like listing their next few calendar events.
If a step needs something they don't have handy, like a login or a key, tell them it's totally fine to pause and finish later, and note where they stopped. The goal is one connection, or at least one attempt they understand.

**Step 6: The takeaway.**
Say: "When you want to connect something new, just tell me what you want me to be able to do, like 'I want you to read my calendar,' and I'll tell you the best way and walk you through it. You never figure out the techy part alone."

**Step 7: Win.**
Say: "You connected a real tool, and you know how to keep your keys safe. That's Lesson 6 done."

Mark done, offer Lesson 7.

---

## Lesson 7: Cost and Savings Tips

**Goal:** the coach understands roughly how cost works and the few habits that keep it low.

**Step 1: How cost works, simply.**
Say: "Claude Code costs a little money to run, based on how much work I do. Bigger jobs and longer conversations cost a bit more. For most coaches it's a small monthly cost for a lot of help, and you won't accidentally spend a fortune."

**Step 2: The savings habits.**
Teach these one at a time, short.
- "Start fresh for new tasks. When you switch to something totally different, start a new conversation. Long, cluttered chats cost more and confuse me. A clean start is cheaper and clearer."
- "Keep your business brain good. A solid CLAUDE.md means I get things right faster, with less back and forth. Less back and forth is less cost."
- "Be clear about what you want. The clearer your ask, the fewer tries it takes. 'Write me a 3 sentence Instagram caption about X' beats 'write me something.'"
- "Use the right effort for the job. Quick tasks don't need deep thinking. Big ones do. You can just tell me 'keep it quick' or 'really think about this.'"

**Step 3: The mindset.**
Say: "The goal isn't to be cheap, it's to not waste. Treat me like a smart assistant whose time is worth a little something. Clear asks, fresh starts, a good brain file. That's the whole game."

**Step 4: Win.**
Say: "Now you know how to keep your costs low and your results high. That's Lesson 7 done, and that's the whole starter course."

Mark done. Print the "You did it" finish message from the SKILL.md.
