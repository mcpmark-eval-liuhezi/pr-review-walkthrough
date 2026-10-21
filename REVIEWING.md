# Reviewing pull requests on this team

This is the short guide for anyone asked to review a change. It covers how we leave feedback and what we expect from each other.

## Comment on the exact line you mean

Leave your comments as **inline comments on the exact lines of the diff you are talking about**. A remark like "this loop is quadratic" is only useful if it is pinned to the loop in question, so anchor every piece of feedback to the specific changed line it refers to.

Avoid dumping all of your feedback into one comment at the bottom of the "Files changed" tab. The author should be able to open a comment and immediately see which line it is about, and anyone reading the pull request later should find the discussion next to the code it discussed.

## The basics

1. Read the pull request description before opening the diff.
2. Skim the tests before the implementation.
3. Ask questions rather than give orders.
4. Anything that touches auth or payments needs a second reviewer.

## Review etiquette

A pull request is a conversation about someone else's work, and the tone of that conversation matters as much as the content. Assume the author had reasons for what they wrote; if something looks odd, ask what the constraint was before assuming it is a mistake. Prefer questions over imperatives — "would it be simpler to reuse the existing helper?" invites a reply, while "reuse the helper" reads as an instruction and shuts the discussion down.

Keep the feedback about the change, never the person, and acknowledge the parts you thought were good so the author knows what to keep doing. If you disagree after a couple of exchanges, say so plainly and take the discussion to a call or a synchronous channel rather than stretching a comment thread, and record the outcome back on the pull request so the decision survives. Finally, if you are too busy to review properly, say so and pass it on quickly — a rushed review two days late is less useful than an honest "not this week" within the hour.
