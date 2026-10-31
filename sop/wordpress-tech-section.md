# SOP – AIH tech section (adithyainfohub.com/tech-ai/) · Level: Basic

**What exists (checked 31 Oct 2026):** /tech/ redirects to the hub page /tech-ai/ "Tech & AI: Best Free AI Tools, Apps & How-To Guides". Category tree Tech & AI → AI Tools, AI Video Generation, AI Productivity, AI for Creators, Websites, How-To, Digital Guides, Productivity. Two tech posts (2 Sep 2026). The hub's "Latest in Tech & AI" block also lists 3 AP & TS Updates posts.

**Rules:** no new plugin, no theme change, no change to existing post URLs, and the normal post-publishing workflow stays the same. Take a Hostinger backup first.

## W01 – fix the "Latest in Tech & AI" block
1. Posts → All Posts → open each of these: Aadhaar update history, bank KYC, voter ID download (7 Sep 2026).
2. In the Categories box, see whether **Tech & AI** (or one of its sub-categories) is ticked.
   - If ticked by mistake: untick it and **Update**. The URL does not change (AIH post URLs are flat slugs).
   - If not ticked: the hub block itself is pulling all recent posts. Edit the hub page, select the block, and set its query to the Tech & AI category only. Tell Claude the block name if unsure.
3. Reload /tech-ai/ and confirm only tech posts show.

## W02 – add sub-categories
Posts → Categories → Add New Category, parent **Tech & AI**:
| Name | Slug |
| --- | --- |
| PC Tips | pc-tips |
| Mobile Tips | mobile-tips |
| Online Safety | online-safety |

## W03 – add level tags
Posts → Tags → Add New: `level-basic` (name "Basic"), `level-intermediate` ("Intermediate"), `level-advanced` ("Advanced"). Also `telugu` for Telugu posts if not already present.

## W04 – hub page blocks
Edit /tech-ai/ and add, near the top:
1. **Watch on YouTube** – channel link (after the channel exists).
2. **Start here by level** – three buttons linking /tag/level-basic/, /tag/level-intermediate/, /tag/level-advanced/.
3. **Topics** – links to the sub-category archives (AI Tools, PC Tips, Mobile Tips, Online Safety, How-To).
4. **Join for new guides** – WhatsApp channel and Telegram buttons.
Claude writes the text for these blocks in English and Telugu on request.

## W05 – redirects
Rank Math → Redirections: confirm the /tech/ → /tech-ai/ redirect is listed and active. Do not add new redirects for existing posts.

## For every new tech post
- Category: Tech & AI → the right sub-category; tag: level; `telugu` for Telugu posts.
- Video embed near the top; English and Telugu posts link to each other.
- "Checked on <date>" line in the summary box.
- Own screenshots only, with alt text.
