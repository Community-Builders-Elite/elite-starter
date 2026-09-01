# Classroom Copy: "Every Confusing Word, Explained"

Paste-ready for the Skool classroom. Goes in the **🧠 Basics** section of Claude Code 101.

Everything below the line is the lesson text, written in plain paragraphs and bold labels so it pastes cleanly anywhere.

NOTE: Skool DOES support real headings, bold, bullets, and inline code. The live version of this lesson uses them. This file is the plain-text backup, so if you rebuild the lesson, promote the ALL-CAPS labels to real headings. Bold the lines marked with ** when you paste, or let Skool's editor handle it.

Suggested lesson title: **Every Confusing Word, Explained**

Suggested resource link on the lesson: the web version, so people can search it.

================================================================

You are going to hit words you do not know. Repo. MCP. Commit. Token. Nobody is born knowing these, and none of them are as complicated as they sound.

This is the list. You do not read it front to back. You come here when a word trips you up, read the few lines, and get back to work.

Two faster options, if you would rather not scroll:

**Ask Claude directly.** Type /explain and the word. Like /explain repo or /explain mcp. You get a short answer and you carry on with what you were doing. You do not lose your place.

**Use the searchable version.** Link is on this lesson. Type a word, it filters instantly. Works on your phone.

---

**THE BIG PICTURE**

**Claude**

The AI that does the writing and thinking. It is made by a company called Anthropic.

There is more than one way to use it. You can use it on a website, or on your computer through Claude Code. Both of those are Claude. They are the same AI, you are just reaching it a different way.

**Claude.ai**

The website. You open a browser, go to claude.ai, and chat in a box. Good for quick questions and thinking out loud.

It cannot open or change the files on your computer. Anything you want it to work on, you paste in yourself. Anything it writes, you copy back out.

**Claude Code**

Claude, running on your own computer, able to read and write your actual files.

That is the whole difference and it is a big one. On the website you copy and paste. In Claude Code, Claude opens your files, reads your offer, checks your voice notes, writes a new file, and saves it. You never copy and paste anything.

This is what you will be using. All your business files sit in one folder, and Claude Code works inside that folder with you.

**Terminal** (also called the command line, console, or shell)

A way of operating your computer by typing instead of clicking.

Normally you use your computer by pointing at things. You double-click a folder to open it, you drag a file to move it. The terminal does the same jobs, but you type the instruction as a line of text and press Enter. Open a folder, move a file, start a program. Same computer, same files, different way of giving the order.

It is a plain window with a blinking cursor and no icons, which is why it looks so serious. All it is doing is waiting for you to type a line and press Enter.

Every computer has one built in. It is not something you installed and not something for programmers only. It has always been there, most people just never open it.

Why you care: some programs have no buttons to click, so typing their name is the only way to start them. Claude Code is one of those. You type claude and press Enter, and the conversation begins.

**IDE**

A program for working on a whole folder of files at once. The letters stand for Integrated Development Environment, which is a mouthful for "everything you need in one window."

Word opens one document at a time. An IDE opens your entire project: a list of every file down the left side, whichever file you are reading in the middle, and a terminal along the bottom. You click between files without hunting through folders, and you never leave the window to run something.

"Integrated" is the point. Editing, browsing your files, and typing commands used to be three separate programs. An IDE puts them together.

**VS Code**

The specific IDE we use. Free, made by Microsoft, runs on Mac and Windows.

Careful: "Visual Studio" and "Visual Studio Code" are two different products. You want Visual Studio Code. People also write it VSCode or VS Code.

Other IDEs exist (Cursor, Windsurf, JetBrains, Zed) and they all do roughly the same job. You do not need to shop around. VS Code is fine and it is what our guides assume.

---

**YOUR FILES AND FOLDERS**

**Repo** (short for repository)

A project folder that keeps a record of its own history.

It is an ordinary folder on your computer. You can open it in Finder or File Explorer and see the files sitting there. What makes it a repo is one hidden extra: a record of every version of every file it has ever held, kept inside the folder itself. That is what lets you back it up online and roll anything back later.

So: a folder, plus a memory of everything that has happened inside it.

Your business repo is where everything lives. Your offer, your voice, your content, your skills. And because it remembers every version, nothing you do to it is permanent.

**Local and Remote**

Local means on your computer, right now. Remote means the copy stored online at GitHub.

Same as a document on your laptop versus the copy in Google Drive. Two copies of the same thing, in two places, and you want them matching.

**CLAUDE.md**

A file at the top of your repo that describes your business: who you help, what you sell, how you sound, and any rules you want followed. People call it your "business brain."

Claude reads it automatically at the start of every conversation, so you never have to explain your business again.

It is the most important file you own. Fill it in well and Claude gets things right the first time. Leave it thin and you will spend every conversation correcting it.

**Memory**

Long-term preferences about how you like to work, saved across all conversations. Things like "always keep my emails short" or "my brand colors are navy and gold."

Different from CLAUDE.md. CLAUDE.md is facts about your business. Memory is preferences about how you work.

**PROJECTS.md**

The list of what you are working on right now. In progress, coming up, done. When you ask "what am I working on?", Claude reads this first.

**Your three folders**

reference holds things that stay true: your offer, your audience, your voice, your testimonials.

research holds notes and ideas you are still working out. It is fine for this one to be messy.

outputs holds finished work: posts, emails, plans. Things ready to go out.

Every file has an obvious home, so nothing gets lost. Let Claude file things, it knows the rules.

**The .env file**

The file where your secret keys are stored, so Claude can use the tools you have connected.

These keys work like passwords. Never paste your .env into a public chat, never share it, never post it online. The file is already set up to stay private on your computer. If you are ever unsure whether something is safe to share, ask Claude before you send it.

**Folders that start with a dot**

Folders like .claude and .git, and files like .env. The dot means "hide this from casual view."

They are not broken or junk. .claude holds your skills, .git holds your history, .env holds your keys. Leave them alone unless Claude is working in them, and never delete .git, that erases your entire history.

---

**SAVING AND BACKING UP**

**Git**

The system that tracks every change to your files, forever, and keeps your computer in sync with the cloud.

Think of the version history in Google Docs, where you can scroll back and see what the document looked like last Tuesday. Git is that, for your whole folder.

You can go back to any earlier version of any file, all the way back to your first day. Say "save my work" and Claude handles it.

**GitHub**

The website where your backup lives. Google Drive for repos, except it remembers every version. If your laptop dies, your business is still there.

**Commit**

Saving a snapshot of what changed. It creates a point you can come back to later if you need to.

Important: a commit is local only. It has not gone to GitHub yet. That is the second half.

**Push**

Uploading your commits to GitHub. The second half of saving, and the part that actually protects you.

When you say "save my work," Claude does both halves together.

**Pull and Fetch**

Downloading changes from GitHub to your computer. Fetch checks whether anything is new. Pull actually brings it down.

**Merge conflict**

Git found two different versions of the same lines and does not know which to keep. It looks alarming. It is not. Nothing is lost, Git just needs a decision.

Tell Claude "I have a merge conflict, help me fix it." Do not try to hand-edit the strange arrow marks yourself.

---

**CONNECTING CLAUDE TO OTHER TOOLS**

By default Claude only works inside your folder. Connecting a tool lets it reach into things you already use, like your email or your calendar, and actually do things there instead of just talking about them.

There are three ways in. You do not have to choose between them, that is Claude's job. This is just so none of the three words feel mysterious.

**MCP**

A ready-made connector that teaches Claude how to use a specific tool.

Every tool works differently, so on its own Claude would have to be taught each one: what it can do, what to ask for, how to read the answer. An MCP is that teaching, already written by someone else and packaged up. You switch it on and Claude knows how to use Gmail, or Airtable, or Notion.

Easiest option when it exists. Only works if someone already built a connector for that tool.

**API**

A way for one program to talk directly to another, without a human clicking anything.

When you use Gmail, you click buttons on a web page. An API is the same Gmail, minus the web page: a set of requests another program can send to read your mail or send a message. Most serious tools have one, because that is how apps connect to each other.

You get in by giving Claude a key, which is what proves the request is really coming from you.

**API key**

The secret password for an API. A long string of random characters. Treat it exactly like a password, because anyone who gets it can use your account and spend your money.

**CLI**

A program with no windows or buttons. You run it by typing its name in the terminal.

Most programs you know have a screen you look at. A CLI has none. You type its name plus what you want it to do, press Enter, and it does the job and prints the result as text. The letters stand for Command Line Interface, meaning the command line is the interface. There is nothing else to it.

This sounds primitive, and for a person it often is. But it is ideal for Claude, because typing a line of text is exactly what Claude can do.

**So which one do I use?**

You do not choose. Tell Claude what tool you want to connect and it picks whichever way works for that tool, then walks you through it. Naming the tool is your whole job.

---

**WORKING WITH CLAUDE**

**Skill**

A saved set of instructions. You write down how a job should be done once, and after that you type one short command and Claude follows those steps.

Instead of explaining what you want every time, you run the skill and it already knows. Anything you do repeatedly can become a skill.

**Slash command**

The way you trigger a skill. A word starting with a slash, like /explain. Type just / to see a menu of everything you have.

**Agent** (also called a subagent)

A helper Claude sends off to do one focused job on its own, then report back.

It works separately from your main conversation, so it does not clutter up your thread, and several can run at the same time. Also cheaper, because a simple job can go to a smaller, cheaper model.

**Model**

There are several versions of Claude, and you pick which one does the work. They are not different products, they are the same idea built at different sizes.

Bigger models reason better and hold more of a hard problem in view at once. They also run slower and cost more. Smaller models are quicker and much cheaper, and on simple jobs they are just as good, because a simple job does not need deep reasoning.

Opus is the largest. Hard thinking, important writing, anything customer-facing where being wrong costs you.

Sonnet is the middle. Most everyday content, especially when you are following a pattern that already works.

Haiku is the smallest. Mechanical jobs with a clear spec: formatting, pulling numbers, moving files.

There is a full lesson on this and on cost, because picking the right one is the biggest lever you have.

**Context window**

The amount of text Claude can look at while answering you.

Claude does not remember your conversation the way a person does. Every time you send a message, it re-reads the entire conversation from the start, plus any files it has opened, and answers based on all of that. The context window is the cap on how much text it can take in at once.

So a conversation does not build up in Claude's memory, it builds up as a pile of text that gets re-read every single time. Once that pile hits the cap, the oldest parts drop off, which is why a Claude that was sharp an hour ago starts losing the thread.

This is also why a fresh conversation fixes so many problems. You are not resetting its mood, you are handing it a short pile to read instead of a long one.

**Token**

The unit of measurement for text. Roughly three quarters of a word, so 100 tokens is about 75 words.

Claude does not read letters or words, it reads tokens. Everything gets counted in them: your message, the files it opens, the whole conversation so far, and its answer back.

**Prompt**

What you type. Your ask.

This is the single biggest lever on quality. "Write me a three-sentence Instagram caption about morning routines" gets a great answer first try. "Write me something" makes Claude guess.

**Hallucination**

When Claude states something confidently that is not true. It is real and it happens, especially with numbers, dates, quotes, and names.

Check anything factual before it goes public. A good CLAUDE.md and real source files in your reference folder cut this down a lot, because Claude reads instead of guessing.

**Permissions**

Claude asking before it does something, like running a command or editing a file. Nothing happens to your files without you approving it first.

If something is routine and you trust it, you can approve it permanently and it stops asking.

---

That is the vocabulary. You do not need to memorize any of it.

When something confuses you, type /explain and the word, and get back to building.
