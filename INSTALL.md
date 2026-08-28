# Installing AI CMO

About two minutes, most of it waiting.

## Before you start

You need Claude Code on your computer. If you don't have it yet, get it at
[claude.com/code](https://claude.com/code) and sign in. If you already have it, make sure it's
up to date — run `claude update`.

## Step 1 — Run two commands

Open your terminal and paste these one at a time:

```
claude plugin marketplace add BotBuilders/ai-cmo
```

```
claude plugin install ai-cmo@ai-cmo
```

The first tells Claude where to find AI CMO. The second installs it.

You should see a line ending in **`(+ 1 dependency: ai-skills)`**. That second piece is the
connection to your skills library — it's supposed to come along automatically, so nothing to do
there.

## Step 2 — Restart Claude Code

Quit it and start it again. Plugins only load at startup.

## Step 3 — Sign in once

The first time AI CMO reaches for your library, a browser window opens asking you to sign in to
BotBuilders and approve access. Do that once per computer and you're done.

## Using it

Just ask, in plain English:

- "We need more leads and I don't know where to start."
- "Build me a Meta campaign for the webinar, fifty dollars a day."
- "Why are we invisible in ChatGPT when we rank first on Google?"
- "Write the five-email sequence for the launch."

There are no commands to memorize. If you'd rather point it at the library directly, type
**`/ai-cmo`**.

## Two things it will never do

- **It won't spend, publish, post, send, or pitch anything.** Everything it makes is a draft you
  look at first.
- **It won't invent a fact about your business.** No made-up numbers, testimonials, reviews, or
  contacts. If something's missing, it tells you what's missing instead of filling it in.

## If something looks wrong

**"It says my library is empty."** Your account isn't switched on for AI CMO yet. That's a billing
thing, not a broken install — email support@botbuilders.com.

**"It's asking me to sign in again."** Normal on a new computer. Also happens if you were signed
out.

**"The install didn't mention `ai-skills`."** Something went sideways. Run
`claude plugin install ai-skills@ai-cmo` and restart.

## Removing it

```
claude plugin uninstall ai-cmo@ai-cmo
claude plugin prune -y
claude plugin marketplace remove ai-cmo
```

The middle command cleans up the shared connection. It's separate on purpose, so removing one
BotBuilders product never breaks another one you're still using.

---

Questions: support@botbuilders.com
