# Notes

Durable memory for this stack, kept in git so it is reviewed like code.

Write here what would otherwise have to be rediscovered: how this system fits
together, what a past change turned out to cost, which approaches were tried and
abandoned and why.

Two rules keep it worth reading.

**Facts about the past, not about the code.** "The migration in #412 needed a
backfill nobody expected" stays true forever. "AuthService lives in pkg/auth"
is true until someone moves it, and a memory that quietly goes wrong is worse
than no memory.

**Nothing that git already answers.** Who changed what, when, and in which
order is in the history. Notes are for the reasoning that is not.
