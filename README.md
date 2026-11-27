# Alibre Design on Linux: Progress

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/ai-made-human-reviewed--dark.svg">
  <img alt="Made by AI / LLM – Human Reviewed" src="assets/ai-made-human-reviewed--light.svg" height="30">
</picture>

A public progress report on running the Windows version of
[Alibre Design](https://www.alibre.com/) on Linux through [Wine](https://www.winehq.org/).

![Alibre Design's 3D viewport showing a spur gear, rendered on Linux through Wine](assets/gear-viewport.jpg)

**Read the report:** <https://alibredesigncommunityprojects.github.io/Alibre-Design-Under-Wine-Progress/>

## Recorded sessions

Development and testing recordings: the [Alibre on Linux playlist](https://www.youtube.com/playlist?list=PLWC4Xgzw8aMs) on YouTube.

| Setup | Session |
|---|---|
| WSL, Ubuntu 24 on Windows 11 | [Part modeling](https://www.youtube.com/watch?v=Pz1MZffQkME) |
| WSL, Ubuntu 24 on Windows 11 | [Sheet metal](https://www.youtube.com/watch?v=QfC7qfxbwQw) |
| WSL, Ubuntu 24 on Windows 11 | [Assembly](https://www.youtube.com/watch?v=PfRrPUX1fnQ) |
| Ubuntu 24.04.5 LTS VM | [First run in the VM](https://www.youtube.com/watch?v=17NofpYCi0Q) |
| Ubuntu 24.04.5 LTS VM | [VM session 2](https://www.youtube.com/watch?v=C6yHX2yflec) |
| Ubuntu 24.04.5 LTS VM | [Space frame assembly performance test](https://www.youtube.com/watch?v=Bqs4fVs5dUc) |

## Status at a glance

| Area | Progress |
|---|---|
| Installation and license activation | 100% |
| User interface | 95% |
| Part modeling and 3D view | 85% |
| Automation and file conversion | 95% |
| Server deployment | 90% |
| Add-ons | 60% |
| Drawings, printing and other workspaces | 20% |
| Packaging for others | 10% |

### Apple Silicon Macs

| Setup | Desktop app | Headless automation | State |
|---|---|---|---|
| Ubuntu 26.04 Arm VM in Parallels, Rosetta for Linux | works | works | working; test kit passed with no failures |
| macOS directly (McSoda 11.0 + Apple D3DMetal) | not usable: blank 3D view, slow, some dialogs hang | works, same results as Linux | cause of the blank view found; desktop work on hold |

Screenshots of both Mac setups are on the report page, in the Apple Silicon Macs section.

Percentages are estimates, not measured test coverage. Last updated November 27, 2026.

## AI attribution

This report was made with AI/LLM tools and reviewed by a human: the text, page design and
code were generated with AI assistance, then directed, reviewed and corrected by the
maintainer. See the [organization's AI/LLM attribution policy](https://github.com/AlibreDesignCommunityProjects)
for what the badge means.

## Disclaimer

An independent community project. Not affiliated with, endorsed by, or supported by
Alibre, LLC or the WineHQ project. Alibre Design is a trademark of its owner. Each user
needs their own Alibre Design license and installs it from the official installer.
