# Product Vision Document

## Product Name

Personal Finance System

## Vision

Create an investment decision-support platform that allows individuals to understand the consequences of their financial decisions without requiring them to become experts in quantitative finance.

The application transforms complex financial analysis into clear, intuitive visualisations and recommendations while allowing users to explore the underlying reasoning at a level of complexity appropriate to them.

---

## Problem Statement

Modern investors have access to increasingly complex financial products, strategies, and information sources, but the tools available to them often fail in one of two ways:

1. They oversimplify investing into basic returns, rankings, and generic advice.
2. They expose users to complex financial concepts without translating them into meaningful decisions.

Investors need a way to answer:

> Given my goals, my current strategy, and current market conditions, what are the consequences of my possible decisions?

The goal is not simply to predict markets or generate trades.

The goal is to improve the quality of financial decisions.

---

## Target User

The primary user is an engaged independent investor.

They are not:

- a complete beginner who wants a simple savings product,
- a professional trader requiring institutional tools,
- a quantitative researcher building models from scratch.

They are someone who:

- manages their own investments,
- has developed an investment strategy or philosophy,
- wants to make informed decisions,
- understands that complexity exists but does not want complexity to be the interface.

Examples:

**Conservative investor**

A person managing retirement savings who wants:

- stable growth,
- income generation,
- controlled risk,
- confidence that their strategy remains appropriate.

**Growth investor**

A person willing to accept more volatility who wants:

- exposure to growth opportunities,
- controlled speculative allocation,
- understanding of risk/reward trade-offs,
- evidence-based strategy adjustments.

---

## Core Product Principle

### Complexity should be available, but never required.

The application should support users with different levels of financial knowledge.

A user may choose:

- a simple dividend-focused strategy,
- a balanced portfolio,
- a growth strategy,
- a higher-risk strategy with speculative allocation,
- a dynamically adjusted strategy.

Regardless of the complexity of the underlying strategy, the initial experience should remain simple and intuitive.

---

## Primary User Experience

### The Saturday Morning Dashboard

The default experience should answer three questions:

---

### 1. Where am I heading?

A clear visualisation of the user's projected financial trajectory.

The user should be able to understand:

- expected outcomes,
- possible ranges of outcomes,
- downside scenarios,
- effects of contributions,
- effects of changing strategy.

The goal is not to provide a single predicted future.

The goal is to show possible futures.

---

### 2. Should I change anything?

A recommendation panel that evaluates whether action is required.

Possible outcomes:

- Continue current strategy.
- Rebalance portfolio.
- Consider alternative allocation.
- Review a specific investment.
- No action recommended.

The system should value avoiding unnecessary changes.

---

### 3. What should I be thinking about?

A longer-term planning view.

Examples:

- Are current contributions sufficient?
- Is the current risk level aligned with goals?
- Are there opportunities to improve?
- Has the user's situation changed?

---

## Decision Presentation

The application should present decisions in an intuitive format.

For example:

Instead of:

```
Foreign exchange impact: -2.4%
```

Present:

```
"Moving this investment internationally reduces expected returns due to currency costs.
The expected improvement does not currently justify the change."
```

The complexity remains available, but it is not the first interaction.

---

## Explanation Layers

Every recommendation should be explainable.

The user should be able to move from:

### Layer 1 — Decision

> "Consider rebalancing your portfolio."

↓

### Layer 2 — Reason

> "Your current allocation has become more concentrated in one sector."

↓

### Layer 3 — Analysis

> "This increases portfolio volatility by approximately X under historical scenarios."

↓

### Layer 4 — Methodology

> "This conclusion was generated using these assumptions and models."

---

## Success Criteria

The application is successful if users:

- understand their investment strategy better,
- make fewer impulsive decisions,
- understand the consequences of changes before making them,
- feel confident that recommendations are justified,
- can choose their desired level of financial complexity.

Success is not defined solely by investment returns.

A recommendation to make no change is considered a successful outcome when it is the correct decision.

---

## Product Philosophy

The application should act as a bridge between:

- simple consumer investing tools,
- and professional quantitative analysis.

It should provide the feeling of having access to a financial analyst while maintaining transparency and user control.

The user should never need to understand every mathematical model behind a recommendation, but every recommendation should be understandable by someone who wants to investigate further.
