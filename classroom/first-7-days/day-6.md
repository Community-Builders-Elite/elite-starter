# Day 6: Connect a Tool You Use

So far, Claude has been working inside your repo. Today we open it up to the rest of your world.

## Why connect anything

Claude can do a lot just by talking with you. But it gets dramatically more useful when you connect it to tools you already use every day. Once connected, it can actually do things in those tools, not just talk about them. Read your calendar. Pull up your notes. Help with your email. The work happens where you already work.

## The three ways to connect, in plain English

There are three ways to hook Claude up to a tool. You don't need to memorize these, but it helps to know they exist so nothing feels mysterious.

An MCP is a ready-made connector. Think of it like an app you plug in that teaches Claude how to use a specific tool. The good: it's usually the easiest, often just a click and a login. The catch: a tool only works this way if someone has already built a connector for it.

An API is a direct doorway between two apps. You connect it by giving Claude a secret key from that app. The good: tons of tools offer one, so it works even when there's no ready-made connector. The catch: you have to find and paste in a key, which is one extra step.

A CLI is a tool you run by typing its name. The good: very powerful, and Claude can run these for you so you barely touch them. The catch: it usually has to be installed first.

That's it. Connecting a tool is normal, and there's more than one way to do it.

## The one safety rule you must know

When you connect a tool with a key, that key gets stored in a file called .env in your folder. Think of it as your private keychain. Claude reads from it so it can use your tools.

Here's the rule, and it matters: your .env file holds secret keys, like passwords. Never paste it into a public chat, never share it, never post it online. It's already set up to stay private on your computer. If you're ever unsure whether something is safe to share, ask Claude first. Better to ask than to leak a key.

## What you'll connect today

You'll connect ONE tool, something you actually use. In the lesson, Claude will ask what tools you rely on most: email, calendar, notes, scheduling, design, wherever you keep your data. Then it'll help you connect one that's genuinely useful.

If you're not sure where to start, a great first pick is Google Workspace. It's easy to connect, and it lets Claude work with your Gmail, Calendar, Drive, and Docs. Very handy.

If a step needs a login or a key you don't have on hand, that's fine. You can pause and finish later. The goal is one real connection, or at least one attempt you understand.

## Your action in Claude Code

Open your repo, start Claude, and say:

> "Let's do Day 6."

Claude will ask what you use, then walk you through connecting one tool, one small step at a time.

## Your win for today

You connected a real tool, and you know how to keep your keys safe. Claude can now reach into something you already use.

One day left. Tomorrow we make sure you get all of this without wasting money.
