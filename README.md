# BotBuilders AI CMO

A marketing department in one plugin. Ask in plain English and the right specialist skill picks
itself up: strategy, paid media, SEO, GEO, copywriting, earned and shared media, conversion work,
and reporting. There are no commands to learn.

## Install

```bash
claude plugin marketplace add BotBuilders/ai-cmo
claude plugin install ai-cmo@ai-cmo
```

That is it. The shared **AI Skills** connection installs automatically alongside it — you do not
add a second marketplace for it. Restart Claude Code, and the first time the connection is used
you will be asked to sign in in your browser and approve access.

## Use it

Just ask:

- "We need more leads and I don't know where to start."
- "Build me a Meta campaign for the webinar, fifty dollars a day."
- "Why are we invisible in ChatGPT when we rank first on Google?"
- "Write the five-email sequence for the launch."

Or type **/ai-cmo** to point it at the library explicitly.

## Good to know

- **It drafts; you approve.** It never launches an ad, spends money, publishes, sends, pitches a
  journalist, or posts on its own.
- **It will not invent a fact about your business.** No made-up metrics, testimonials, reviews,
  journalists, or follower counts. Where something is missing it names the gap.
- **If the library looks empty,** your account is not switched on for AI CMO yet. That is a
  billing question — support@botbuilders.com.

## Buying another product later

One more `claude plugin install`. The skills connection is shared, so you do not sign in again.

## Uninstall

```bash
claude plugin uninstall ai-cmo@ai-cmo
claude plugin prune -y          # removes the shared connection once nothing needs it
claude plugin marketplace remove ai-cmo
```

`prune` is a separate step on purpose — uninstalling a product never rips the shared connection
out from under another product you still have.

## Requirements

Claude Code 2.1.247 or newer.
