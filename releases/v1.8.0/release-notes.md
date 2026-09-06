Reset 1.8.0 is the first public build.

- **Reset News notifications.** When Tibo announces a Codex reset, or one lands, Reset shows a
  macOS notification with the headline and the post. It is on by default; turn it off under
  Settings → Usage rail. Permission is requested the first time a notification is due.
- **A public update channel.** Downloads come from <https://nextreset.app/download>, and the app
  updates itself from `https://releases.nextreset.app/appcast.xml`.

Reset requires an Apple-silicon Mac running macOS 26 or newer. Verify the download with
`shasum -a 256 -c Reset-v1.8.0-macOS-arm64.zip.sha256` before opening it.
