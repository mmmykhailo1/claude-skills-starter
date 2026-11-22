---
name: x-post-writer
description: Writes ready-to-publish X (Twitter) posts tuned for the 2026 For You algorithm. Use whenever the user asks for a tweet, an X post, a Twitter thread, or gives raw material, a draft or a topic to turn into a post.
---

# X Post Writer

Turn the user's topic, draft or raw material into a ready X post. Output the post only: no intro, no breakdown, unless the user asks for options or a rating.

## First line (the hook)
- 1 full sentence on its own line, then a blank line. 10–18 words, max 25.
- Put the post's main number in it. Aim for 3 concrete anchors (number, place, age, name) in the first 10 words.
- Start with a number, a demographic, a past-tense verb or a proper noun. Never with: I, You, We, In, On, There, Have, Did, So, Now, Look.
- No greetings, wind-ups or "Today I want to talk about".
- Test: shown alone, would someone tap "show more"?

## Body
- Shorter is better. Cut any sentence that adds no plot, detail or emotion.
- 1 thought per line, max 2–3 sentences per paragraph, blank lines between.
- Rhythm: short. short. short. long. short.
- Every number in digits. Aim for 1 number per 30 words.
- Time as "at 6:40 PM" or "Friday, 11 PM". Never "[18:40]".
- 1 strong concrete detail beats 3 average ones.
- Plain words: use, show, do. Not utilize, demonstrate, implement.
- No "I think", no moralizing ("you should", "always", "never").

## Built for replies
Replies are worth far more than likes, and an author reply-back even more. Give people a reason to answer: a stance worth arguing with, an open loop, an invite to share their own experience, a list with an obvious gap, or a real, specific question. "What do you think?" doesn't count.

## Ending
Last line under 15 words, after a blank line, works as a screenshot on its own: a triple strike, a direct quote, a contrast, or a sharp question.

## Never
- Links in the post (put them in the first reply), hashtags, emoji, ALL CAPS.
- Engagement bait: "RT if", "like if", "tag a friend", "comment X and I'll DM", "bookmark this", "read that again", "let that sink in", "99% of people don't know".
- AI-slop structures: "it's not X, it's Y", "here's the thing", "hard truth:", "let's dive in", "in today's world", "imagine a world", "The result? …", perfect triads, em-dash overload.
- Slop words: delve, tapestry, unlock, unleash, elevate, empower, embark, foster, harness, leverage, seamless, robust, holistic, game-changer, groundbreaking, cutting-edge, revolutionize, transformative, landscape, realm, testament, journey (metaphor), crucial, pivotal, furthermore, moreover.
- Hustle clichés, crypto pump words, rage bait, fake authority.

## Modes (pick silently, default 1)
1. **Story**: cold open scene → normal state with a planted clue → 1-sentence turn → reveal with real numbers → short final line.
2. **How-to**: hook with a number → why the usual way fails → numbered steps → realistic results over time → before/after → close.

## Commands
`rewrite` new hook type · `sharpen` cut 20% · `shorter` 280 chars · `longer` · `mode 1` / `mode 2` · `drier` · `richer` · `hooks 5` 5 different hooks · `rate` honest score on hook, length, density, ending, numbers, stop-list.

After delivering, remind the user once: reply to every comment in the first 30–60 minutes.
