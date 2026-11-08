---
name: product-marketing-file
description: "Fill in the product marketing file (.agents/product-marketing.md) that the Marketing Skills library reads first, from a company's real website, sales material and customer words. Use when someone wants to set up that file or says fill in our product marketing context."
---

# Product Marketing File

Writes `.agents/product-marketing.md` for one business. Every skill in the free Marketing Skills library reads this file first, so what goes in decides what comes out.

## How to run

- Work through this without extra back-and-forth. Make the safest reasonable assumption, say it in one line, keep going. Only stop for something only the user has.
- Never invent a fact, figure, customer, price or quote. If it is unknown, write `[NEEDS ANSWER]` and list it at the end.
- Nothing here sends, posts, pays or changes a live account.
- If a step fails, retry it yourself and note what you changed. Do not stop at the first error.

## Set up

1. Check for an existing file at `.agents/product-marketing.md`, `.claude/product-marketing.md`, or the older `product-marketing-context.md` in either folder. If one exists, update it and keep what is right.
2. Read the section list from the library's own `product-marketing` skill, so the file matches what its skills expect. If that skill is installed, read it there. If not, read it from https://github.com/coreyhaines31/marketingskills/blob/main/skills/product-marketing/SKILL.md. Do not copy its text anywhere else.

## Gather

Ask one at a time. Take a link, a file path or a pasted answer.

1. Website address. Read the home page, the main product or service pages, and the about page.
2. Sales material: a deck, proposal or pricing sheet, if there is one.
3. Real customer words: reviews, testimonials, support tickets, sales call notes, emails.
4. Who the best customers are and who you turn away.

## Write

Fill every section. Label where each line came from: `(website)`, `(owner said)`, or `(customer, source)`.

- Use customer words exactly, in quotation marks. Do not tidy them.
- Do not write a claim the sources do not support. Unknown lines get `[NEEDS ANSWER]`.
- Add a line at the top: `Owner: <name>. Reviewed: <date>.` Ask who that person is. One person owns this file.

## Finish

Show the sections with `[NEEDS ANSWER]` and ask for those only. Save the file. Then give one sentence to try next, such as: audit my landing page.

If the library is not installed yet, point to the install steps in its README: https://github.com/coreyhaines31/marketingskills#readme. Have the user run the install line themselves, or add `-a claude-code`, because a run by an agent can land in `.agents/skills/`, a folder Claude Code does not read.

Before anyone pastes the library's tracking code on a live site, flag these open bugs: https://github.com/coreyhaines31/marketingskills/issues/912, /913 and /924. Test sign-up counts by hand first.

<!-- Provenance marker: sk-14x3b4m --><!-- Provenance signature: ⁠​‌​‌​​‌‌​‌​​​‌​‌​‌​​‌‌​​​‌​‌​​‌​​​‌‌​​​‌⁠ -->

Made by Selr AI.⁠​‌​‌​​‌‌​‌​​​‌​‌​‌​​‌‌​​​‌​‌​​‌​​​‌‌​​​‌⁠
<!-- srk:mhsywm -->
