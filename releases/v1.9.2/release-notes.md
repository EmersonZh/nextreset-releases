Reset 1.9.2 stops asking you to reconnect Claude Code.

- **Claude Code stays connected.** Claude Code rewrites its sign-in every time it renews it, and
  Reset used to ask you to reconnect after each renewal. Once you have connected, Reset now
  follows the renewal on its own, without a macOS dialog. Settings → Sync → Follow Claude Code
  sign-in renewals turns this off.
- The Reconnect notice appears only when Fast sync is on and Reset has no current Claude numbers.
- **Reset's data now lives under Reset's own name**, in `~/Library/Application Support/Reset`, with
  its Keychain items under `app.nextreset.Reset.authblob`. Accounts, history, the Claude status
  line and the widget move over automatically the first time the new version opens.

Reset requires an Apple-silicon Mac running macOS 26 or newer. Existing installs update through
the built-in updater.
