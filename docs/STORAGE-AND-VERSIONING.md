# Storage and versioning – how every Adytech file is kept

Level: Basic (no coding needed to follow this)
Started: 4 Nov 2026 (v0.2.0)

## 1. The three places

Everything for Adytech (plans, documents, scripts, guides, research, apps, code, tracker) is kept in **all three places**, with the same folder layout.

| # | Place | Link / path | What it is best for |
| --- | --- | --- | --- |
| 1 | **GitHub (master copy)** | [github.com/MrAdithya26/Adytech](https://github.com/MrAdithya26/Adytech) | Full history: every change, who/when/why, any old version can be opened |
| 2 | **Local folder (your PC)** | `D:\ABD Innovations\Adygeeks` | Working offline, recording, opening files quickly |
| 3 | **Google Drive** | ABD INNOVATIONS › 06 Tech and AI Services › **Adytech (Adygeeks) – Project** | Reading on phone, sharing with the team, big media files |

GitHub is the **master**. If the three ever disagree, the GitHub version wins; the other two are copies of it.

## 2. Version numbers

Every saved update gets a version number `vMAJOR.MINOR.PATCH`, e.g. `v0.2.0`.

| Part | Goes up when… | Example |
| --- | --- | --- |
| MAJOR | A new phase starts or the whole plan is rewritten | `v1.0.0` = channel goes public |
| MINOR | Something new is added: a new document, guide, episode, app, research | `v0.3.0` = first script pack added |
| PATCH | A small fix to something that already exists: typo, link, date, number | `v0.3.1` = corrected a price |

- The current version is in the file [`VERSION`](../VERSION) at the top of the repo.
- Each version is a **git tag** on GitHub (open *Tags* or *Releases* on the repo page to see all of them).
- Before 1.0.0 = set-up and pilot phase. `v1.0.0` is reserved for the first public video.

### Version history so far
| Version | Date | What |
| --- | --- | --- |
| v0.1.0 | 31 Oct 2026 | Implementation plan v1 and production kit (commits 84a5e4e, fde3053) |
| v0.2.0 | 4 Nov 2026 | Storage and versioning system, chat log, 2 Nov GitHub software guide, local folder and Drive mirror |

(New rows are added here and in `CHANGELOG.md` with every version.)

## 3. What happens on every update (the routine)

Claude follows these steps every time something is created or changed in this project:

1. **GitHub:** save the file in the right folder → add a line to `CHANGELOG.md` (before / now / removed / why) → bump `VERSION` → one commit → tag `vX.Y.Z` → push.
2. **Local folder:** copy the changed files to `D:\ABD Innovations\Adygeeks\` (same paths), and save a full snapshot zip in `D:\ABD Innovations\Adygeeks\_versions\Adytech_vX.Y.Z_YYYY-MM-DD.zip`.
3. **Google Drive:** in *Adytech (Adygeeks) – Project › Versions*, create a new folder `vX.Y.Z – YYYY-MM-DD` with Google Docs/Sheets copies of the new or changed files, and update the Drive index doc as a **new dated copy**.
4. **Chat log:** add one row to `chats/CHAT-LOG.md` for the chat in which the work was done.
5. **Tell Adithya** what changed, the new version number, and the links.

If one place can't be reached (PC off, Drive error), Claude does the other two, says which one was missed, and catches it up in the next chat. The catch-up is logged in the CHANGELOG.

## 4. Nothing is ever deleted

- **GitHub:** only new commits. No force-push, reset, rebase or deleting files. A replaced file stays in history; a dropped file is moved to `archive/` with a CHANGELOG line.
- **Local folder:** nothing deleted; old versions live in `_versions/` zips.
- **Drive:** never deleted or overwritten; each version is a new dated folder. Old versions stay.
- Removing anything needs Adithya's written OK in the chat first.

## 5. File naming

| What | Pattern | Example |
| --- | --- | --- |
| Dated documents (research, reports) | `YYYY-MM-DD_short-name_vN.md` | `research/2026-11-02_github-free-software-guide_v1.md` |
| Living documents (plan, decisions, tracker) | fixed name, history in git | `docs/IMPLEMENTATION-PLAN.md` |
| Episode folders | `episodes/YYYY-MM-DD-TOPICID/` | `episodes/2026-12-12-AI-B-01/` |
| Apps / tools | `apps/<app-name>/` with its own README and version | `apps/thumbnail-maker/` |
| Snapshots (local) | `_versions/Adytech_vX.Y.Z_YYYY-MM-DD.zip` | `_versions/Adytech_v0.2.0_2026-11-04.zip` |

Level (Basic / Intermediate / Advanced) is written at the top of every content file.

## 6. Folder layout (same in all three places)

```
Adytech / Adygeeks
├── README.md               start here
├── VERSION                 current version number
├── CHANGELOG.md            every change, newest first
├── CLAUDE.md               rules Claude follows
├── docs/                   plan, decisions, this file
├── content/                topic bank, series plan, calendar
├── research/               dated research and guides (GitHub repos, tools, launches)
├── templates/              script, Shorts, metadata, thumbnail, blog EN/TE, hands-on, fact-check
├── sop/                    step-by-step checklists
├── tracker/                content-tracker.csv (one row per video)
├── episodes/               one folder per video
├── apps/                   any app, script or tool built for Adytech
├── chats/                  CHAT-LOG.md: every chat, what came out, where it is stored
└── archive/                retired files (never deleted)
```

Large media (video, raw recordings, thumbnail PNGs) go only to Drive and the local folder, not GitHub (GitHub has a file-size limit and is for text and code).

## 7. Where to look for the history of a file

- **Simple:** open `CHANGELOG.md` and search the file name.
- **Exact old wording:** on GitHub open the file → *History* → pick a date → *View file*.
- **A whole old version:** GitHub → *Tags* → `vX.Y.Z` → *Browse files*, or open the zip in `_versions/`, or the Drive folder of that version.
