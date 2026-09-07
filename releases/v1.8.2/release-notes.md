Reset 1.8.2 closes the last gap in the Keychain work.

- **No Keychain dialog at launch, for real this time.** 1.8.1 marked its background Keychain
  queries as non-interactive with the modern API, which macOS's login keychain ignores, so the
  "Reset wants to use your confidential information" dialog could still appear at launch. Every
  Keychain call now runs behind the switch that keychain actually honours: off for launch and
  background work, on only while an explained, user-initiated read is running.

Reset requires an Apple-silicon Mac running macOS 26 or newer. Existing installs update through
the built-in updater.
