Reset 1.9.0 gives every saved Codex account a home of its own.

- **Saved accounts stop expiring behind your back.** A saved account used to be a copy of a sign-in
  that also lived elsewhere, and OpenAI rotates refresh tokens, so whichever copy refreshed second
  died. Each saved account now has its own private Codex home under Reset's Application Support
  folder, created by its own browser sign-in, and the Codex CLI keeps its tokens fresh in place.
  Reset never refreshes or writes tokens itself.
- **What changes for you.** Adding or saving an account opens a separate browser sign-in for that
  account. Accounts you already saved migrate on their next successful check. An account marked
  "Needs sign-in" recovers with Sign in again, which now performs a fresh sign-in instead of
  reusing the dead copy. Make current works as before: the account's file is promoted into
  ~/.codex through the validated, rollback-safe switch.
- The design follows CodexBar's managed accounts (MIT), credited in the third-party notices.

Reset requires an Apple-silicon Mac running macOS 26 or newer. Existing installs update through
the built-in updater.
