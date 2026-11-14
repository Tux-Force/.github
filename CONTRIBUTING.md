# Contributing to Tux-Force

Thanks for helping! This guide applies to all Tux-Force repositories unless a repository says otherwise.

## Ground rules

- **Legal only.** Tux-Force runs games your account is entitled to. Contributions that bypass licenses, DRM or
  entitlement checks are not accepted.
- **No Microsoft code.** Do not contribute code copied from Microsoft products, SDK headers with incompatible licenses,
  leaked sources or decompiled binaries. Work from public documentation, protocol observation and testing.
- **Credit upstream.** xTux, xgameruntime and wine are soft forks. Keep license headers and attributions intact.

## AI-assisted contributions

AI tools are welcome here. We use them ourselves and think they help a small community build a large ecosystem.

1. **A human is responsible.** You must understand, test and be able to explain every change you submit, no matter
   who or what wrote it.
2. **Disclose it.** Say in the pull request when AI tools helped (for example a `Co-Authored-By` trailer or a note in
   the description). Undisclosed AI-generated contributions may be closed.
3. **Same bar as any code.** Reviews, tests and style rules apply unchanged. "The AI wrote it" is not a reason to
   merge.
4. **Mind upstream rules.** When a change goes to an upstream project (Wine, xodus-gaming, ...), that project's rules
   apply. Some, like Wine, require clean-room work and may not accept AI-assisted or reverse-engineering-informed code.
   Check before you port a Tux-Force change upstream.
5. **Protect secrets.** Never paste tokens, logs with account data or personal information into AI tools or issues.

## Branches and pull requests

- `tux-force` is the default branch of each fork and holds our integrated state.
- Upstream branches (`main`, `legacy-c`, `bleeding-edge`, ...) mirror upstream and are only synced.
- Changes meant for upstream start from the upstream branch so they can be proposed there unchanged.
- Code, comments and documentation are written in English.

## Reporting problems

Open an issue with the game, your distribution, GPU and driver, and the relevant part of the log. Remove tokens and
personal data from logs first.
