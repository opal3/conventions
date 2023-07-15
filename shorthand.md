# Shorthand

This pages explains what the emojis used in code-review comments and Slack mean.
They are shorthand for common situations.

## In code review comments

### 💬 - debug code...

Debug/commented-out code needs removing/uncommenting

### 👻, 🕵🏾, 🐼 - pedantry...

Minor/pedantic point - short hand for:

> "I know this is deeply pedantic but..."

For comments so pedantic you're almost embarrassed to write them, wrap in `<sup>` tags.

> 🐼<sup>"Direct Debit" should be title-case.</sup>

"Panda-ntic" if you will.

### 👀 - please look at this...

Please eyeball this change/commit/code:

> 👀 Hey @team, is this change OK? I'm not that familiar with `$domain_concept`

### ♻️ - same as above...

Same explanation as above (a.k.a. ditto).

### 🐂, 🐃 - out-of-scope, but...

Yak-shaving code review comments, as in:

> I know this is out of scope for this PR request but...

or something like:

> I know you only renamed the file but I'm going to comment on all the green lines in the diff that you didn't write...

### 🚗 - passing through

For a "drive-by" comment:

> I’m just passing through and I haven't done a full review but noticed that...

### 🙌 - praise

For highlighting something positive in the pull request

> 🙌 Nice catch!

### ❓ - question

When you have a potential concern but are not quite sure if it's relevant or not

> ❓ Is this condition possible in the real world?

### 🤔 - suggestion

Use when you want to propose improvements to the current subject

> 🤔 I think you should consider moving this to the domain layer

### 🍷🧀 - tasting notes

Used to indicate that a self-review provides additional context and commentary
on the changes. Possibly including a recommendation for how to review it (like
the tasting notes on a fancy bottle of wine or fine cheese)
