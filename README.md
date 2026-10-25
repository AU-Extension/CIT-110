# CIT 110 Computer Operating Systems: course interactives

Interactive simulations for CIT 110 at Atlantis University, School of Information Technology. Each week has two self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The Moodle description blocks link to these pages through GitHub Pages.

Live site: https://au-extension.github.io/CIT-110/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| week1 | What an operating system does, and your virtual lab | os-layers-explorer.html | os-fit-challenge.html |
| week2 | Installing operating systems | boot-sequence-animator.html | partition-planner-challenge.html |
| week3 | Windows essentials | windows-admin-tools-map.html | which-tool-challenge.html |
| week4 | Linux essentials | linux-terminal-explorer.html | chmod-permissions-challenge.html |
| week5 | Processes, memory, and storage | process-memory-visualizer.html | slow-pc-diagnosis-challenge.html |
| week6 | Users, security, and permissions | ntfs-permission-calculator.html | hardening-challenge.html |
| week7 | Scripting and automation with AI | pipeline-visualizer.html | safe-or-dangerous-challenge.html |
| week8 | Troubleshooting, recovery, and final project | troubleshooting-flowchart.html | help-desk-ticket-challenge.html |

## Publishing

1. Upload the contents of this folder to the `main` branch of `AU-Extension/CIT-110` (keep the `week1` to `week8` folders at the root).
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Each page is then live at `https://au-extension.github.io/CIT-110/weekN/<file>.html`.

Every page loads the AU logo from `AU-Extension/items` and GSAP and fonts from public CDNs, and still works if GSAP fails to load. No build step is needed.
