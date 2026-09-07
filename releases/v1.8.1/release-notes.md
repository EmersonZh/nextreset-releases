Reset 1.8.1 stops asking for your Keychain.

- **No Keychain prompt at launch, none in the background.** Reset now learns which Claude account
  is signed in from Claude Code's own local config, and its background checks never open the
  macOS Keychain dialog.
- **Prompts only when you ask.** Connecting Claude Code, saving or switching an account, and turning
  on Fast sync explain what Reset is about to read before macOS asks. Choose Always Allow and it
  stays quiet until Claude Code renews its sign-in, which the Claude pane then reports with a
  Reconnect button.
- **Your choice, in Settings → Sync → Keychain prompts:** Only when I ask (default) or Never.

Reset requires an Apple-silicon Mac running macOS 26 or newer. Existing installs update through
the built-in updater.
