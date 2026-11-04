# Adytech – change log

Every change, newest first, in plain English. Nothing is deleted; old versions stay in git history and in Drive.

---

## 4 Nov 2026 – v0.2.0: storage and versioning system (three places)

- **Why:** Adithya asked that all Adytech data – past chats, future chats, plans, documents, apps, repos – be kept in three places (PC folder, Google Drive, GitHub), with every version clearly stored and easy to follow.
- **New:** `docs/STORAGE-AND-VERSIONING.md` – the three places, version numbers (vMAJOR.MINOR.PATCH), the update routine, no-delete rule, file naming, folder layout, how to find old versions.
- **New:** `VERSION` (0.2.0). Versions are marked by commits titled `vX.Y.Z: …` (v0.1.0 = commit fde3053). Pushing git tags is blocked from Claude's cloud session; the command to add them from the PC is in `docs/STORAGE-AND-VERSIONING.md` §7.
- **New:** `chats/CHAT-LOG.md` – the 31 Oct and 2 Nov chats and this one, with links and where their output is stored.
- **New:** `research/2026-11-02_github-free-software-guide_v1.md` – copy of the 2 Nov Claude Doc "28 Free Software from GitHub — Organised Guide" (previously only in Claude), plus `research/README.md`.
- **New:** `apps/README.md`, `archive/README.md` (empty folders ready for use).
- **Changed:** `README.md` – before: no storage section; now: links to the new files and a "Where everything is kept" table. `CLAUDE.md` – before: 4 standing rules; now: rule 5 (three places, one layout) and the new folders in Layout. `docs/DECISIONS.md` – new decided row for 4 Nov.
- **Local folder:** first full copy written to `D:\ABD Innovations\Adygeeks` + `_versions/Adytech_v0.2.0_2026-11-04.zip`. The 9 starter folders made earlier today (00_Planning … 99_Assets, README only) are left in place, waiting for Adithya's OK to move them to `archive`.
- **Drive:** new folder "Adytech (Adygeeks) – Project" in 06 Tech and AI Services, with `Versions › v0.2.0 – 2026-11-04` (Google Doc/Sheet copies of every file) and an index doc. Earlier Drive docs unchanged.
- **Removed:** nothing.

---

## 31 Oct 2026 – Implementation plan v1 and production kit (first commit)

- **Before:** the repo was empty.
- **New:** `docs/IMPLEMENTATION-PLAN.md` (phases and gates Nov 2026 – Dec 2027, week-by-week set-up, weekly production system, website integration, income, YouTube thresholds checked 31 Oct 2026, tools, numbers, risks).
- **New:** `docs/DECISIONS.md` (decided items and D1–D7 waiting for Adithya).
- **New:** `content/topic-bank.md` (72 topics), `content/series-plan.md` (8 series), `content/calendar-first-12-weeks.md` (12 Dec 2026 – 27 Feb 2027).
- **New:** 8 templates in `templates/`, 4 SOPs in `sop/`, `tracker/content-tracker.csv`, `episodes/README.md`, `README.md`, `CLAUDE.md`.
- **Checked on 31 Oct 2026:** YouTube Partner Program thresholds (YouTube Help); adithyainfohub.com/tech/ redirects to /tech-ai/ (2 tech posts; 3 non-tech posts in its "Latest" block); all 23 GitHub repos named in the topic bank exist.
- **Drive (06 Tech and AI Services):** new docs [Adytech – Implementation Plan v1 (31 Oct 2026)](https://docs.google.com/document/d/18-42EMviYrX1-6QlboVN_W_8IqsklYu4O6a-8-cLHXk), [Adytech – Content kit v1](https://docs.google.com/document/d/16yYiIhG2xh1VfyVOkwwnfcknYopyiTJL63LVaO2-Ng8) and [Adytech – project status and plan (31 Oct 2026 v2)](https://docs.google.com/document/d/1frWXey-4A9LiTeKqZSmL5QWsoY-xh-KlBrx_eFCF8D0); new [Drive index v5](https://docs.google.com/document/d/1i_eOrJQr-b9FJXta50qfk9nf7PGyScQUBt2B2POPC8g). The v1 status doc and index v4 stay unchanged.
- **ABD-Innovations:** `projects/ADYTECH.md` and `CHANGELOG.md` updated (commit ea61ea5).
- **Removed:** nothing.
