# Community post: GTA 6 Clipper for Windows (copy-paste)

**Title:** GTA 6 Clipper for WINDOWS: free Claude Code skills (finished + live)

Here are both GTA 6 clipper skills from the video. This is the Windows version (Windows 10/11). Mac version: https://github.com/vossashtonai/gta6-clipper

**1. Open Claude Code and paste this:**

```text
Install the GTA 6 Clipper for Windows from https://github.com/vossashtonai/gta6-clipper-windows.
Clone the repo to a temporary folder, then copy BOTH folders inside its skills/ folder
(gta6-clipper and gta6-live-clipper) into my Claude skills folder (%USERPROFILE%\.claude\skills\)
so they sit side by side.
Then run: powershell -NoProfile -ExecutionPolicy Bypass -File "%USERPROFILE%\.claude\skills\gta6-clipper\scripts\setup.ps1"
(use a 10 minute timeout, the first run downloads about 800 MB).
Tell me what it installed and whether it says READY. Then remind me to restart Claude Code.
```

**2. Restart Claude Code, then say one of these:**

- clip this stream [paste link]
- find me today's biggest GTA 6 streams and clip them
- live clip [paste link of a stream that's live right now]

Your clips land in a folder called GTA6-Clips in your user folder (C:\\Users\\you\\GTA6-Clips), each with a caption and hashtags ready to post.

**No Claude subscription?** The README on GitHub shows how to run it free with Ollama.

Drop your first clip in the comments
