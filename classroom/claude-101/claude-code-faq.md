# Claude Code Cheat Sheet and FAQ

The plain-English answer to "wait, what IS that?"

You do not read this front to back. You come here when a word shows up that you do not know, find it, read the three lines, and get back to work. Nothing here assumes you have ever written code.

**Two parts:**
- **Part 1: The Glossary.** Every word you will hear, defined plainly.
- **Part 2: The FAQ.** Every "why is this happening to me" moment.

**Related:**
- Want it taught step by step instead of looked up? The 7-day course: `classroom/first-7-days/`
- Setting up your business brain -> `classroom/claude-101/how-to-create-your-claude-md.md`
- Or just ask Claude. Type `/explain [word]`, or say "what does that mean?" any time.

---

# Part 1: The Glossary

Each entry follows the same shape: what it is, why you care, what you actually do about it.

---

## The Big Picture

### Claude
The AI that does the writing and thinking. It is made by a company called Anthropic.

There is more than one way to use it. You can use it on a website, or on your computer through Claude Code. Both of those are Claude. They are the same AI, you are just reaching it a different way.

**Why you care:** You will hear "Claude" used for all of it, so it helps to know the word covers the AI itself, not one particular app.

**What you do:** Nothing. This is just the name of the thing you are working with.

---

### Claude.ai
The website. You open a browser, go to claude.ai, and chat in a box. Great for questions, drafting, thinking out loud.

**Why you care:** It is useful, but it cannot open or change the files on your computer. Anything you want it to work on, you have to paste in yourself, and anything it writes, you have to copy back out.

**What you do:** Use it for quick questions. Use Claude Code for actual work on your business.

---

### Claude Code
Claude, running on your own computer, with the ability to read and write your actual files.

That is the entire difference and it is a big one. On the website, you copy and paste things in and out. In Claude Code, Claude opens your files, reads your offer, checks your voice notes, writes a new file, and saves it. You never copy and paste anything.

**Why you care:** This is what you will be using. All your business files sit in one folder, and Claude Code works inside that folder with you.

**What you do:** Open your folder, type `claude`, and start talking.

---

### Terminal (also: command line, console, shell)
A way of operating your computer by typing instead of clicking.

Normally you use your computer by pointing at things: you double-click a folder to open it, drag a file to move it. The terminal does the same jobs, but you type the instruction as a line of text and press Enter. Open a folder, move a file, start a program. Same computer, same files, different way of giving the order.

It is a plain window with a blinking cursor and no icons, which is why it looks so serious. All it is doing is waiting for you to type a line and press Enter.

Every computer has one built in. It is not something you installed and not something for programmers only. It has always been there, most people just never open it.

**Why you care:** Some programs have no buttons to click, so typing their name is the only way to start them. Claude Code is one of those. You type `claude` and press Enter, and the conversation begins.

**What you do:** Type `claude`, then talk in normal English. That is almost all you will ever use the terminal for.

---

### IDE
A program for working on a whole folder of files at once. The letters stand for Integrated Development Environment, which is a mouthful for "everything you need in one window."

Word opens one document at a time. An IDE opens your entire project: a list of every file down the left side, whichever file you are reading in the middle, and a terminal along the bottom. You click between files without hunting through folders, and you never leave the window to run something.

"Integrated" is the whole point. Editing, browsing your files, and typing commands used to be three separate programs. An IDE puts them together.

**Why you care:** It is where you work. Your files on the left, your conversation with Claude on the right, and you can see what Claude changes as it happens.

**What you do:** Open your repo in it every time you sit down to work.

---

### VS Code (Visual Studio Code)
The specific IDE we use. Free, made by Microsoft, runs on Mac and Windows.

Careful: "Visual Studio" and "Visual Studio Code" are two different products. You want **Visual Studio Code**. Also called VSCode or just VS Code.

**Why you care:** It is the recommended home for your work, and Claude Code has an extension that runs right inside it.

**What you do:** Download from code.visualstudio.com. Open your repo folder in it. Work there.

**Other IDEs people use:** Cursor (VS Code with more AI baked in), Windsurf, JetBrains, Zed, Sublime Text. They all do roughly the same job. You do not need to shop around. VS Code is fine and it is what our guides assume.

---

## Your Files and Folders

### Repo (repository)
A project folder that keeps a record of its own history.

It is an ordinary folder on your computer. You can open it in Finder or File Explorer and see the files sitting there. What makes it a repo is one hidden extra: a record of every version of every file it has ever held, kept inside the folder itself. That is what lets you back it up online and roll anything back later.

So: a folder, plus a memory of everything that has happened inside it.

**Why you care:** Your business repo is where everything lives. Your offer, your voice, your content, your skills. And because it remembers every version, nothing you do to it is permanent.

**What you do:** You work inside yours. You cannot break anyone else's.

---

### Remote (and the two names, `origin` and `upstream`)
A **remote** is a nickname for a web address where a copy of your files lives.

Your files sit in a folder on your computer. Git lets you save nicknames for places online, so you type a short word instead of a long address every time. That is all a remote is.

You have two, and each has one job:

- **`origin`** is **your** repo. Where your work gets backed up. Things go **out** to it when you save.
- **`upstream`** is **Ron's** repo. Where updates come from. Things come **in** from it when you pull.

The names are just convention, chosen decades ago. "Origin" means your own main copy. "Upstream" means the thing you copied from, further up the river.

**Why you care:** if an error message mentions `origin` or `upstream`, it is telling you which of those two it had trouble reaching.

**What you do:** nothing. Say "save my work" and `/pull-master-updates`, and the right one gets used automatically.

---

### Local vs Remote
**Local** means on your computer, right now. **Remote** means the copy stored online at GitHub.

Same as a document on your laptop versus the copy in Google Drive. Two copies of the same thing, in two places, and you want them matching.

**Why you care:** Almost every confusing Git moment is the two being out of sync. You changed something locally and did not send it up. Or someone changed something up there and you have not pulled it down.

**What you do:** Save your work often, which pushes local up to remote. Then they match.

---

### Clone
Downloading a copy of a repo from GitHub onto your computer for the first time.

**Why you care:** It is how you get your repo the first time. You do it once per computer.

**What you do:** In GitHub Desktop, File > Clone Repository, pick yours.

---

### Fork / Template Copy
Making your own copy of someone else's repo, so you can change it freely without touching the original.

**Why you care:** Your business repo started as a copy of the starter kit. That is why you can edit anything and never break the original.

**What you do:** You already did this at setup. You will not do it again.

---

### CLAUDE.md
A file at the top of your repo that describes your business: who you help, what you sell, how you sound, and any rules you want followed. People call it your "business brain."

Claude reads it automatically at the start of every conversation, so you never have to explain your business again.

**Why you care:** It is the most important file you own. Fill it in well and Claude gets things right the first time. Leave it thin and you will spend every conversation correcting it.

**What you do:** Fill it in early, then add to it whenever something becomes permanently true.

---

### Memory
Long-term preferences about how you like to work, saved across all conversations. Things like "always keep my emails short" or "my brand colors are navy and gold."

**Why you care:** Different from CLAUDE.md. CLAUDE.md is facts about your business. Memory is preferences about how you work.

**What you do:** Say "remember that I always want X." Do not use it for this week's to-do list, that belongs in PROJECTS.md.

---

### PROJECTS.md
The list of what you are working on right now. In progress, coming up, done.

**Why you care:** When you ask "what am I working on?", Claude reads this first.

**What you do:** Say "add this to my projects." Claude keeps it tidy.

---

### The Three Folders
**reference/** holds things that stay true: your offer, your audience, your voice, your testimonials.

**research/** holds notes and ideas you are still working out. It is fine for this one to be messy.

**outputs/** holds finished work: posts, emails, plans. Things ready to go out.

**Why you care:** Every file has an obvious home, so nothing gets lost.

**What you do:** Let Claude file things. It knows the rules.

---

### _master-index.md
A table of contents that sits in each folder, listing what is in there and why.

**Why you care:** It is how Claude finds things fast instead of digging through every file.

**What you do:** Nothing. Claude keeps it updated.

---

### .md (Markdown)
A plain text file that supports simple formatting. A `#` makes a heading, `**bold**` makes bold.

**Why you care:** Nearly every file in your repo is one. They open anywhere and will still work in twenty years.

**What you do:** Nothing special. Just text.

---

### The .env file
The file where your secret keys are stored, so Claude can use the tools you have connected.

**Why you care:** These keys work like passwords. **Never paste your .env into a public chat, never share it, never post it online.** The file is already set up to stay private on your computer.

**What you do:** Let Claude write to it. If you are ever unsure whether something is safe to share, ask Claude before you send it.

---

### Hidden folders (the ones starting with a dot)
Folders like `.claude`, `.git`, and files like `.env`. The dot means "hide this from casual view."

**Why you care:** They are not broken or junk. `.claude` holds your skills. `.git` holds your history. `.env` holds your keys.

**What you do:** Leave them alone unless Claude is working in them. Never delete `.git`, that erases your entire history.

---

## Saving and Backing Up

### Git
The system that tracks every change to your files, forever, and keeps your computer in sync with the cloud.

Think of the version history in Google Docs, where you can scroll back and see what the document looked like last Tuesday. Git is that, for your whole folder.

**Why you care:** You can go back to any earlier version of any file, all the way back to your first day.

**What you do:** Say "save my work." Claude handles the rest.

---

### GitHub
The website where your backup lives. Google Drive for repos, except it remembers every version.

**Why you care:** If your laptop dies, your business is still there.

**What you do:** Make an account, then mostly forget about it.

---

### GitHub Desktop
An app with buttons that does Git things, so you do not have to type Git commands.

**Why you care:** It makes the scary parts clickable. Good for seeing what changed before you save.

**What you do:** Use it for cloning and for eyeballing changes. Or skip it and just tell Claude "save my work."

---

### Commit
Saving a snapshot of what changed. It creates a point you can come back to later if you need to.

Important: a commit is **local only**. It has not gone to GitHub yet.

**Why you care:** It is half the save. Without the second half, your backup is not updated.

**What you do:** Say "save my work" and Claude commits and pushes together.

---

### Push
Uploading your commits to GitHub. The second half of saving.

**Why you care:** This is the part that actually protects you. Commit without push means the only copy is still on your laptop.

**What you do:** Included when you say "save my work."

---

### Pull / Fetch
Downloading changes from GitHub to your computer. **Fetch** checks whether anything is new. **Pull** actually brings it down.

**Why you care:** If you work on two computers, or if updates get pushed to your repo, this is how you get them.

**What you do:** Say "check for updates" or click Fetch origin in GitHub Desktop.

---

### Branch
A separate line of work, so you can try something without touching your main files.

**Why you care:** Mostly you will not need this. Developers use branches heavily. You have one repo, one line of work.

**What you do:** Stay on `master` (or `main`) unless there is a real reason not to.

---

### Merge conflict
Git found two different versions of the same lines and does not know which to keep. Usually happens when the same file changed in two places.

**Why you care:** It looks alarming. It is not. Nothing is lost, Git just needs a decision.

**What you do:** Tell Claude "I have a merge conflict, help me fix it." Do not try to hand-edit the weird `<<<<<<<` marks.

---

## Connecting Claude to Other Tools

By default Claude only works inside your folder. Connecting a tool lets it reach into things you already use, like your email or your calendar, and actually do things there instead of just talking about them.

There are three ways in. You do not have to choose between them, that is Claude's job. This is just so none of the three words feel mysterious when you see them.

---

### MCP
A ready-made connector that teaches Claude how to use a specific tool.

Every tool works differently, so on its own Claude would have to be taught each one: what it can do, what to ask for, how to read the answer. An MCP is that teaching, already written by someone else and packaged up. You switch it on and Claude knows how to use Gmail, or Airtable, or Notion.

Underneath it is usually still an API (below). The difference is that somebody already did the wiring for you.

**The good:** Usually the easiest. Often just a click and a login.
**The catch:** Only works if someone already built a connector for that tool.

**Why you care:** It is the fastest way to let Claude work in Gmail, Airtable, Notion, and similar.

**What you do:** Tell Claude which tool you want connected and let it walk you through it.

*(MCP stands for Model Context Protocol. You will never need to know that.)*

---

### API
A way for one program to talk directly to another, without a human clicking anything.

When you use Gmail, you click buttons on a web page. An API is the same Gmail, minus the web page: a set of requests another program can send to read your mail or send a message. Most serious tools have one, because that is how apps connect to each other.

You get in by giving Claude a key, which is what proves the request is really coming from you.

Nearly every serious tool offers one. Nobody has to build a connector first, but you do have to go get the key yourself.

**The good:** Tons of tools offer one, so it works even when no ready-made connector exists.
**The catch:** You have to find and paste in a key, which is one extra step.

**Why you care:** When there is no MCP for a tool, this is usually the way in.

**What you do:** Find the key in that tool's settings, hand it to Claude, and it goes safely into your `.env`.

---

### API key
The secret password for an API. A long string of random characters.

**Why you care:** Anyone who gets it can use your account and spend your money.

**What you do:** Treat it like a password. Paste it to Claude so it can store it in `.env`, and never post it anywhere public.

---

### CLI
A program with no windows or buttons. You run it by typing its name in the terminal.

Most programs you know have a screen you look at. A CLI has none. You type its name plus what you want it to do, press Enter, and it does the job and prints the result as text. Stands for Command Line Interface, meaning the command line *is* the interface. There is nothing else to it.

This sounds primitive, and for a person it often is. But it is ideal for Claude, because typing a line of text is exactly what Claude can do.

**The good:** Very powerful, and Claude runs these for you so you barely touch them.
**The catch:** Usually has to be installed first.

**Why you care:** Some of the best tools only come as a CLI. Claude Code is itself a CLI.

**What you do:** Let Claude install and run them.

---

### So which one do I use?
You do not choose. You tell Claude what tool you want to connect, and it picks whichever way works for that tool and walks you through it.

---

## Working With Claude

### Skill
A saved set of instructions. You write down how a job should be done once, and after that you type one short command and Claude follows those steps.

Instead of explaining what you want every time, you run the skill and it already knows.

**Why you care:** Anything you do repeatedly can become a skill, which saves you from re-explaining it forever.

**What you do:** Type `/` to see what you have. Build new ones by describing what you want.

---

### Slash command
The way you trigger a skill. A word starting with a slash, like `/start-here`.

**Why you care:** Typing `/` shows you a menu of everything available.

**What you do:** Type `/` and look. That is the fastest way to learn what you own.

---

### Agent (subagent)
A helper Claude sends off to do one focused job on its own, then report back.

It works separately from your main conversation, so it does not clutter up your thread, and several can run at the same time.

**Why you care:** They work in the background and can run several at once. Also cheaper, because a simple job can go to a smaller, cheaper model.

**What you do:** Nothing usually. Claude decides. You can also say "have a subagent do this."

---

### Model
There are several versions of Claude, and you pick which one does the work. They are not different products, they are the same idea built at different sizes.

Bigger models reason better and hold more of a hard problem in view at once. They also run slower and cost more. Smaller models are quicker and much cheaper, and on simple jobs they are just as good, because a simple job does not need deep reasoning.

Here is the ladder, most advanced and most expensive at the top:

**Fable** is the most advanced and the most expensive. About twice the price of Opus. Save it for the hardest thinking you do: a quarterly or annual plan, designing your offer from scratch, untangling something genuinely broken. If being wrong would be expensive, this is the one.

**Opus** is next, and about five times the price of the model below it. This is your workhorse for anything that matters: sales copy, your offer doc, a webinar or VSL script, YouTube scripts, planning, working through a decision.

**Sonnet** is the middle, about twice the price of the model below it. Use it for most everyday content, especially when you are following a pattern that already works: community posts, reels from a brief, emails against a proven template, editing and tightening, routine research.

**Haiku** is the smallest and cheapest. Mechanical work with a clear spec and low downside: formatting, moving or renaming files, pulling numbers, updating a list, tagging, simple lookups.

The mistake runs both ways. Put Fable or Opus on a filing job and you have paid many times over for a result Haiku would have nailed. Put Haiku on your sales page and you get sales-page-shaped writing that does not sell, so you wasted the whole attempt.

**Why you care:** This is the single biggest lever you have on what Claude Code costs you.

**What you do:** Type `/model` to switch. If you are unsure, ask "which model should I be on for this?" and say what you are about to do.

---

### Context window
The amount of text Claude can look at while answering you.

Claude does not remember your conversation the way a person does. Every time you send a message, it re-reads the entire conversation from the start, plus any files it has opened, and answers based on all of that. The context window is the cap on how much text it can take in at once.

So a conversation does not build up in Claude's memory, it builds up as a pile of text that gets re-read every single time. Once that pile hits the cap, the oldest parts drop off, which is why a Claude that was sharp an hour ago starts losing the thread.

This is also why a fresh conversation fixes so many problems. You are not resetting its mood, you are handing it a short pile to read instead of a long one.

**Why you care:** Long conversations cost more and get worse, because Claude is carrying everything you have ever said in that thread.

**What you do:** Start a new conversation when you switch to a genuinely different task. Cheaper and sharper.

---

### Token
The unit of measurement for text. Roughly three quarters of a word, so 100 tokens is about 75 words.

Claude does not read letters or words, it reads tokens. Everything gets counted in them: your message, the files it opens, the whole conversation so far, and its answer back.

**Why you care:** Tokens are what your usage limit is spent on, and what an API bill is calculated from. When people say a long conversation "costs more," this is the thing being counted.

**What you do:** Nothing directly. Start fresh for new tasks and be specific in your asks, and the token count takes care of itself.

---

### Prompt
What you type. Your ask.

**Why you care:** The single biggest lever on quality. "Write me a three-sentence Instagram caption about morning routines" gets a great answer first try. "Write me something" makes Claude guess.

**What you do:** Be specific. Say what it is, who it is for, how long, and what it should do.

---

### Hallucination
When Claude states something confidently that is not true.

**Why you care:** It is real and it happens. Especially with numbers, dates, quotes, and names.

**What you do:** Check anything factual before it goes public. A good CLAUDE.md and real source files in `reference/` cut this down enormously, because Claude reads instead of guessing.

---

### Permissions
Claude asking before it does something, like running a command or editing a file.

**Why you care:** Nothing happens to your files without you approving it first.

**What you do:** Read the prompt, approve if it makes sense. You can allow routine things permanently once you trust them.

---

# Part 2: FAQ

---

### What is the actual difference between Claude and Claude Code?
It is the same AI either way. The difference is what it can reach.

On the claude.ai website, you chat in a box and copy things in and out by hand. Claude Code runs on your computer and opens your files directly, so it can read your offer and write a finished post without you pasting anything.

For running your business, you want Claude Code.

---

### Do I need to know how to code?
No. You describe what you want in plain English. That is the whole interface. The people getting the most out of this are coaches and consultants, not developers.

---

### Which do I open first, VS Code or the terminal?
Open VS Code, open your repo folder, then open the terminal inside VS Code and type `claude`. One window, everything in it.

---

### What do I type to start?
`claude` in the terminal. Then talk normally. Type `/` any time to see your available skills.

---

### Am I going to break something?
Almost certainly not, and almost nothing is permanent. Git keeps a snapshot of every version you have ever saved, so you can go back. Claude asks permission before doing anything real.

The one genuine rule: do not delete the `.git` folder, that is your history.

---

### Claude says it cannot find a file
Nearly always one of two things. Either you started Claude from the wrong folder, or the file is somewhere other than where you think.

Just ask: "which folder am I in?" or "find the file with my offer in it." Claude will look.

---

### I told Claude to save my work. Is it actually backed up?
Saving is two steps: commit (snapshot on your computer) and push (upload to GitHub). When you say "save my work," Claude does both.

To be sure, ask "is everything pushed?" Or open GitHub Desktop and look for "Push origin" still waiting.

---

### What are `origin` and `upstream`?
Two nicknames for two web addresses. `origin` is your repo, where your work backs up. `upstream` is Ron's repo, where updates come from.

One goes out (your work), one comes in (Ron's updates). You never type either name yourself.

---

### My push failed
Usually because GitHub has changes you do not have yet. Pull first, then push.

Say "pull the latest and then save my work." If it turns into a merge conflict, say so and Claude will walk you through it.

---

### What is the difference between CLAUDE.md, memory, and PROJECTS.md?
- **CLAUDE.md** = facts about your business that are always true. Who you help, what you sell, how you sound.
- **Memory** = how you like to work. "Keep my emails short."
- **PROJECTS.md** = what you are working on right now.

Rule of thumb: permanent business truth goes in CLAUDE.md, working preferences go in memory, this week's work goes in PROJECTS.md.

---

### Why does Claude keep asking permission?
So you can see what it wants to do before it does it. If something is routine and you trust it, you can approve it permanently and it will stop asking.

---

### How much does this cost, and how does my subscription fit in?
You pay a flat monthly subscription (Pro or Max), and Claude Code is included in it. You are not billed per message, and there is no meter running that can surprise you with a bill.

What you have instead is a **usage limit**. Your plan gives you a certain amount of work in a rolling window, and if you use it all, Claude pauses and tells you when it resets. It stops. It does not start charging you.

So the real question is not "how much am I spending," it is "how much can I get done before I hit the limit." Everything below is about making your allowance go further.

**The model you pick is the biggest factor.** Heavier models eat your allowance several times faster than lighter ones. An hour on Opus doing work Sonnet could handle burns through your day for no extra quality.

**The other three habits:**

- **Start a new conversation for a new task.** Claude re-reads the whole conversation every time you send a message, so a long thread costs more with every turn, even if your question is short.
- **Keep your CLAUDE.md good.** When Claude already knows your business, it gets things right the first time instead of after four corrections. Four corrections cost four times as much as one good answer.
- **Be specific.** "Write me a three-sentence Instagram caption about morning routines" gets a usable answer immediately. "Write me something" gets a guess, then a rewrite, then another rewrite.

That last one is worth more than the other two combined.

**If you are on the API instead of a subscription** (most members are not, and you would know if you were), then you genuinely are billed per word, and all of the above matters more, not less.

**The mindset:** the goal is not to be cheap, it is not to waste. Match the model to the job, start fresh when you switch tasks, and ask clearly.

---

### When should I start a new conversation?
When you switch to a genuinely different task. Long conversations carry everything before them, which costs more and makes Claude less sharp. Staying in one thread all day is the most common expensive mistake.

---

### Which model should I use?
Opus for hard thinking and important writing. Sonnet for everyday content against a pattern you have already established. Haiku for mechanical jobs.

If you are unsure, just ask "which model should I be on for this?"

---

### Claude gave me something wrong or made something up
It happens, mostly with numbers, dates, names, and quotes. Two fixes:

Short term: tell it what is wrong and ask it to redo it. Be specific about what was wrong.

Long term: get the real information into a file in `reference/`, then tell Claude to read that file. It stops guessing when it has a source.

---

### The output does not sound like me
Your voice file is probably thin, or Claude did not read it. Ask "read my voice file first, then rewrite this."

The real fix is feeding it more of your actual words. Real posts you wrote, real transcripts. Examples beat descriptions every time.

---

### What is a skill and should I build my own?
A skill is a saved set of steps you trigger with a slash command. Yes, build your own, that is where the leverage is. You do not write code, you describe what you want.

One thing that matters a lot: give it as much detail as you possibly can. Step by step, as if training a new assistant on exactly how you do the task. The better the description, the better the skill.

---

### How do I connect Claude to Gmail, Airtable, or a tool I use?
Tell Claude which tool. It will pick the right connection method (MCP, API, or CLI) and walk you through it.

If you want a first one to try, Google Workspace is a good pick. Easy to connect, and it opens up Gmail, Calendar, Drive, and Docs all at once.

---

### Is it safe to paste an API key to Claude?
Yes, in Claude Code. It stores keys in your `.env` file, which stays private on your machine.

What is **not** safe: posting your `.env` or a key into a public chat, a screenshot, a Skool post, or anywhere online. If you are unsure whether something is safe to share, ask Claude before you send it.

---

### Something in my setup is broken
Describe exactly what you typed and exactly what came back. That combination is almost always enough for Claude to solve it.

If it is a Windows install problem ("claude is not recognized", or an error about scripts being disabled), say so, those two have known fixes.

---

### I forgot what I can do
Type `/` to see your skills. Or just ask Claude "what can you help me with in this repo?"
