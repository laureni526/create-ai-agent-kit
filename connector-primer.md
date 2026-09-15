# Connecting a Real Tool — One-Page Primer

An agent contract gives an agent your knowledge and its boundaries. A
connector gives it your tools. Without one, it can only ever tell you
what to do. With one, it can actually do it — read the real email, see
the real calendar, take the real action.

That's a bigger step than writing the contract, and it deserves one
question before you take it: **not "can it reach this tool," but
"what should it never do without asking me first."**

## Calendar is a core source, not an example

Commitments live in meetings as much as in email. If your agent only
reads your inbox, it will miss half of what it's supposed to track —
the promise made on a call, the deadline set in a meeting invite.
Connect both from the start.

## Why draft-only is the right default

Today's demo could draft a reply. It couldn't send one. That wasn't a
limitation we ran out of time to fix — it's the right default for
handing an agent a real inbox. You are always the last check before
anything leaves your name. As you build trust with a given task, you
decide when — or whether — to loosen that.

The same logic applies past email:

-   A calendar connection can *propose* a meeting time before it
    *books* one.
-   A drive connection can *draft* a document before it *shares* one.
-   A project-tracker connection can *suggest* a status update before
    it *posts* one.

## Write the scope boundary into the contract

Before connecting anything, fill in Section 6 of `agent-contract.md` —
how many days of email history, how many days back and forward on the
calendar, and any folder or label to restrict to. A bounded agent
produces something you can actually check; an agent pointed at
everything doesn't. Set that boundary in the tool itself where it
allows it (many connectors let you scope permissions to read-only,
draft-only, or specific folders/labels); where it doesn't, hold the
line by habit until you've tested the agent enough to trust it
further.

## Where to find connector settings

-   **Claude:** Settings → Connectors. Connect an app (Gmail, Google
    Drive, Calendar, and others), then grant it to a specific
    conversation or Project. Permission scope is set per connector.
-   **ChatGPT:** Settings → Connectors (or, inside a chat, the "+" /
    tools menu depending on plan). Supports both first-party app
    connectors and MCP connectors for custom or third-party tools.
-   **Gemini:** Extensions (in the Gemini app) for first-party Google
    Workspace access — Gmail, Drive, Calendar, Docs. Workspace users
    get the deepest native reach here of the three tools, since it's
    Google's own ecosystem.

## One habit worth building

The first few times you use a new connection, read every draft before
you act on it — even ones that look obviously right. You're not just
checking that one output. You're building your own sense of where the
agent's judgment can be trusted and where it can't yet. That's what
"loosening the guardrail" actually means in practice: not turning it
off, but learning exactly how far it's earned.
