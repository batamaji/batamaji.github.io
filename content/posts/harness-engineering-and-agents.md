+++
title = 'Harness engineering and AI agents'
date = 2026-10-21T12:00:00+03:00
tags = ['agents', 'harness', 'security']
+++

A first post to say what this blog is about.

Most of my time goes into harness engineering: the scaffolding around a model
that decides what it can see, what it can run, and when it stops. The model is
rarely the bottleneck — the harness is. Tool design, context budgets, retries,
sandboxing, and knowing which step to hand back to a human.

The other half is security research. The two overlap more than people expect:
an agent with shell access is an attack surface, and a harness is a trust
boundary like any other.

## What to expect here

- Notes on building and debugging agent harnesses
- Bugs and vulnerabilities I run into, where I can write them up
- Small tools and projects, with the reasoning behind them

Short posts, written as I go.
