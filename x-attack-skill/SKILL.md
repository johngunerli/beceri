---
name: X-attack-skill
description: Use when John gets a mean tweet or reply on X and wants a witty roast reply drafted; reads the sender's public replies and recent posts, then drafts for his approval only.
---
# X-attack-skill

Goal: draft a witty roast reply to someone who sent John a mean tweet or reply. Draft only. Never post.

## Steps
1. Load the `x-api-mcp-guide` skill and follow it.
2. Get the mean post (link, id, or text from John) and the sender's handle.
3. Read the sender's profile, their recent public posts, and their recent public replies with the X read tools. Pull 15 to 30 items.
4. Find material: hypocrisy, bad takes, contradictions, repeated tics, typos in a tweet about grammar, ratio-bait habits, self-owns. Base roasts only on what they publicly posted.
5. Write 3 reply options, each under 280 characters, in John's terse style: short, dry, no em dashes (use commas or colons), no hashtags, minimal emoji. Aim at the post or behavior, not the person's identity.
6. Show John the 3 options plus the one-line reason each lands. Ask which to use or what to tweak.
7. When John picks one, hold it as a draft with the X plugin's `create_posts` (reply.in_reply_to_tweet_id set to the mean post). If `create_posts` is not listed, use `x-drafts` `draft_post`. It posts only when John explicitly says to post.

## Hard rules
- Never auto-post, reply, like, follow, block, or DM. Draft for approval only.
- Public posts only. No digging into private info, doxxing, or other accounts.
- Keep it witty. No slurs, threats, harassment campaigns, or content about protected traits, family, or health.
- If the sender is a minor, a protected or private account, or the post is a real threat, skip the roast and tell John.
- If nothing good exists in their history, say so and offer a clean one-liner instead of reaching.
