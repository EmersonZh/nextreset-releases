# Reset releases

Signed, notarized builds of **Reset**, the macOS app that watches your Codex and Claude Code
usage limits from the edge of the screen and marks the ring when Tibo posts a Reset Surprise.

- Website: <https://nextreset.app>
- Download the latest build: <https://nextreset.app/download>
- Every release below carries the zip, its SHA-256 checksum, and the release notes.

Verify a download before opening it:

```sh
shasum -a 256 -c ./*.zip.sha256
```

Reset requires an Apple-silicon Mac running macOS 26 or newer. The app updates itself through
its built-in updater, which reads the Sparkle feed published from this repository's `gh-pages`
branch. The application source is maintained privately for now.

Reset is an independent project. It is not affiliated with, endorsed by, or sponsored by OpenAI
or Anthropic. Codex, ChatGPT, Claude and Claude Code are trademarks of their respective owners.

© 2026 Emerson Zhang
