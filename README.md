# Hey, I’m Tommy 👋

I’m interested in building small tools that solve the annoying parts of bigger projects. My current projects come from modded Minecraft: checking downloads, tracking modpack changes and planning materials for builds.

I want each tool to do one job clearly, explain its limits and be easy to try. These are early projects, and useful feedback is what will shape the next releases.

### Find the tool you need

| If you want to… | Start here | Get it |
| :--- | :--- | :--- |
| Find identical mod JARs and damaged archives | **[JarCheck](https://github.com/MrTommyyyy/JarCheck)** — desktop window or terminal, scan progress, clipboard results, subfolder scans and JSON reports | [Latest release](https://github.com/MrTommyyyy/JarCheck/releases/latest) |
| See what changed between two mod folders | **[ModpackCompare](https://github.com/MrTommyyyy/ModpackCompare)** — saved snapshots or live-folder verification; exports a protected difference report | [Latest release](https://github.com/MrTommyyyy/ModpackCompare/releases/latest) |
| Work out blocks, stacks and shulker space before building | **[BuildBudget](https://github.com/MrTommyyyy/BuildBudget)** — rectangles, grid circles, rings, vertical walls and closed hollow boxes | [Latest release](https://github.com/MrTommyyyy/BuildBudget/releases/latest) |

**All three run offline and have automated tests.** No account or API key is needed. Portable Windows x64 downloads bundle Python; separate source ZIPs support Python 3.11+ on Windows, macOS and Linux.

**See the earlier demos:** the previous releases include MP4 videos replaying captured terminal output from real sample runs and tests. They show earlier versions and do not show the desktop interface.

### Start with JarCheck

My main project focuses on accidental duplicate downloads and archive integrity. It checks files outside the game, so there is no loader-specific installation. It does not decide whether mods are compatible or safe.

On Windows, download the `Windows-x64.zip` release asset, extract it and double-click **`JarCheck.exe`**. The desktop window has scan progress, a subfolder checkbox, JSON export and a copy-results button.

To try the synthetic demo from the Python source ZIP:

```sh
python demo.py
```

The [README](https://github.com/MrTommyyyy/JarCheck#readme) explains findings and how to scan your own folder.

### Latest updates

- **JarCheck 0.3.0:** portable desktop and terminal executables, scan progress and clipboard results.
- **ModpackCompare 0.2.0:** verify a folder against a baseline and save differences without replacing the baseline.
- **BuildBudget 0.2.0:** calculate walls without a floor or roof, including spare blocks and storage.

### What I’m focusing on

- **Useful defaults:** read-only scans, clear output and optional JSON for scripts.
- **Reproducible bugs:** small examples and regression tests when something breaks.
- **Straightforward releases:** versioned downloads, practical instructions and honest limits.
- **Better usability:** making findings easier to understand and gathering real desktop feedback.

### Help shape the next release

If a tool helps—or gets in your way—tell me what you were trying to do and what happened. Include the tool version, operating system and a small example where possible. Remove private paths and usernames before sharing reports.

[Report a JarCheck bug](https://github.com/MrTommyyyy/JarCheck/issues/new?template=bug_report.md) · [Suggest a JarCheck feature](https://github.com/MrTommyyyy/JarCheck/issues/new?template=feature_request.md) · [Browse all projects](https://github.com/MrTommyyyy?tab=repositories)
