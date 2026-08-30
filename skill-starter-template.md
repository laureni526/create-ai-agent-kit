# Skill Starter Template

*A blank skeleton for packaging one real piece of your own knowledge
into something an agent can actually use. Copy this file, fill in the
blanks with your answers from `worksheet.md`, and hand the finished
copy to your agent tool of choice — see "Where this goes" below.*

Fill in every bracket. Delete nothing — an empty section is a gap you
haven't decided on yet, not one you don't need.

---

## Name

> [What do you'd call this if you were naming it for a colleague, not a computer — e.g. "How I review a lesson before it ships," not "Skill_1"]

## What it's for

> [One sentence. The specific task from worksheet.md Question 2 — not "help with my job."]

## What it should know

> [The actual criteria, steps, or judgment calls you use — written the way you'd explain them out loud to a new hire, not as generic best practice. If you find yourself writing something that could apply to any team's process, it's not specific enough yet.]

1.  ___
2.  ___
3.  ___

## What it should never do

> [Your answer to worksheet.md Question 4, restated as a rule the skill itself carries. This is not optional boilerplate — this is the line that made today's demo trustworthy.]

> ___

## What "done" looks like

> [How would you — not the agent — know the output was actually good? One or two concrete signs, not a vague "sounds right."]

> ___

---

## Where this goes

The container is different in every tool, but the four sections above
map the same way everywhere:

-   **Claude:** build this as a Skill — Name and "What it's for" become
    the skill's description; "What it should know," "What it should
    never do," and "What 'done' looks like" become its instructions.
-   **ChatGPT:** build this as a Project's custom instructions, or a
    Custom GPT — same four sections, same order. Skills available to Business, Enterprise, Healthcare, and Edu accounts.
-   **Gemini:** build this as a Gem. Gems cap around 4,000 characters
    of instructions, so if your "What it should know" section runs
    long, keep the specific judgment calls and cut the general
    preamble first — the specifics are what make it a skill instead of
    generic advice.

Once it's built, don't re-paste this file into every conversation.
That's the whole point — see `README.md`'s note on invoking a skill
versus re-explaining it every time.
