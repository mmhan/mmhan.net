---
date: 2025-12-31
categories: [Career, Review]
slug: 2025-recap
---

# 2025 in Review: The Year I Refactored Myself

The year 2025 began with a roadmap. It ended as a journey I never anticipated: a deep dive into burnout, technical debt, and the profound realization that chasing speed doesn't always lead to impact.

<!-- more -->

## The Grind and the Cracks

The first quarter was a blur of activity. I led a heroic effort to refactor our prototypical product, **AI Interview**, from a bowl of spaghetti into something resembling an actual architecture. Or at least, lasagna—structured layers you could reason about.

That refactoring enabled the team to scale features with incredible speed. In no time, we were juggling multiple languages, custom client features, and primitive debugging tools. The `ai-interview` project scaled from a handful of test runs to nearly 250,000 interviews conducted over the year.

I was focused on output, on demonstrating the productivity I thought was expected. We were riding the momentum of delivering features for a big Keynote, but our "code complete" standard had become the default. The architecture, now groaning under the weight of new features, started to resemble a Jenga tower where every new block was a feature request and every weekly release was a prayer. As I noted in a reflection, "We are now accruing technical debt at a rate that exceeds our ability to pay it down."

By April, I started seeing the system as that Jenga tower wobbling. The relentless pace culminated in what my journal from that time clinically refers to as an "unscheduled, high-priority emotional unloading session." It was a critical turning point. The unsustainable pace wasn't just a technical problem; it was a personal one.

## A Shift in Philosophy

That period of exhaustion forced a necessary re-evaluation. I took my time, which included reading Cal Newport's **"Slow Productivity"**—the engineering equivalent of being told to "turn it off and on again," but for your entire professional life.

In my notes, I asked the question that had been forming for months: **"How do we redefine 'good work' to prioritize quality and sustainable engineering practices over raw output?"**

This wasn't just navel-gazing; I started patching the ship's hull. I focused on production stability by formalizing our incident response process. I hardened our deployment pipeline with automated quality gates to act as a safety net. Most importantly, I championed a cultural shift in our code reviews, pushing us beyond the classic "LGTM" on a 2000-line PR and towards asking the terrifying question: "Will the person who has to touch this in six months (probably me) hate us for it?"

These weren't flashy features, but they were acts of **architectural leadership** that made our entire team more effective. (At least, I hope it was.) This shift was about moving from just building things to building a better way to build things.

## The Breakthrough: `interview-graph`

This new philosophy culminated in a project I had brewed for a couple of months. Finally, during my December holidays, I was supposed to be off work. Instead, I found myself in a state of flow so deep I forgot what day it was, prototyping a new, **graph-based architecture** for the state machine of the interview process. The project, which I called **`interview-graph`**, was the manifestation of everything I'd learned. It was a direct response to the brittleness and complexity of our monolith.

My `git log` from that week tells a story of obsession (12 commits on Christmas Day is not a cry for help, it's a feature). Over eight days, I built a fully functional prototype with a two-agent architecture, **`LangSmith`** tracing, and a **`Pipecat`**-powered voice bot. The core technical spike was complete in three days. The rest, I admit, was over-building. As I wrote in my self-analysis: "The spike was done. I just didn't stop when it did."

But this prototype was more than a technical exercise. It was a clear, viable vision for our future. A blueprint for a skyscraper, not the skyscraper itself. It still needs to be validated, accepted, and battle-tested to scale to 10x our current volume, but it demonstrates a path to higher velocity, greater reliability, and a more maintainable system. It was the most significant "force multiplier" I could offer.

Crucially, I stopped myself from shooting for the moon, leaving space for the team to contribute and — learning from April — to prevent myself from burning out once more.

## The Unseen Foundation

None of this happens in a vacuum. This professional journey was supported by the constants in my personal life: the discipline of regular badminton sessions, which provided both a vital mental reset and a persistent shoulder injury to remind me of my own mortal fragility, and the grounding influence of a stable, supportive family life.

## Looking Ahead

2025 began with a set of ambitious goals. It ended with something far more valuable: a clear, battle-tested vision for my role as a technical leader. The `interview-graph` project isn't just a piece of code; it's the opening argument for a new chapter.

My goal for 2026 is to bring that vision to life: to lead the charge in building a more resilient, sustainable, and truly impactful engineering culture.

And maybe, just maybe, take my actual holidays this time.
