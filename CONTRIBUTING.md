# Contributing to Tux-Force

Thanks for helping! This guide applies to all Tux-Force repositories unless a repository says otherwise.

## AI welcome

AI-assisted contributions are welcome here. Tux-Force itself is built with AI tools, and chat assistants, coding
agents or autocomplete are all fine to use. Writing everything by hand is just as welcome.

> **Our opinion:** used well, today's coding assistants write, review and debug code better than the average
> programmer, provided you know how to work with them.

What we care about is the result:

- **Test what you submit.** Run it and check that it does what the pull request says.
- **Same review for everyone.** Human, AI or both: every pull request gets the same review and tests.
- **Say when AI helped.** Add a `Co-Authored-By` trailer for the assistant or a short note in the pull request.
- **Say when you vibe-coded it.** If you have no solid background in software engineering or computer science and the
  change was written by AI without you really understanding the code, please say so in the pull request. That is
  welcome too; it just tells reviewers to look more closely.

## Ground rules

- **Legal only.** Tux-Force runs games your account is entitled to. Contributions that bypass licenses, DRM or
  entitlement checks are not accepted.
- **No Microsoft code.** Do not contribute code copied from Microsoft products, leaked sources or decompiled
  binaries. Public documentation, observed behaviour and testing are the way.
- **Keep licenses and credits.** xTux, xgameruntime and wine are forks. Keep license headers and attributions intact.
- **Keep secrets out.** Remove tokens, account data and personal information from logs, issues and prompts.

## Branches

- `tux-force` is the default branch of each fork and is where development happens. Branch off it and open pull
  requests against it.
- Upstream branches (`main`, `legacy-c`, `bleeding-edge`, ...) mirror the projects we forked from. We pull new upstream
  code into `tux-force` when it is useful; we do not push to upstream.
- Code, comments and documentation are written in English.

## Reporting problems

Open an issue with the game, your distribution, GPU and driver, and the relevant part of the log (without tokens or
personal data).
