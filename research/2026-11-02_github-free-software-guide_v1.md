# 28 Free Software from GitHub — Organised Guide

Nov 2, 2026 · @Prasad kumar

## At a glance

All 28 repos in your Excel are real, public and were updated in the last few weeks (checked 2 Nov 2026 by cloning each one). Only 4 are fully beginner-ready today; most of the Craft apps are alpha. Level = how hard it is for a normal user to get running.

| # | Software | Free alternative to | Group | Level | How you get it | License | Stage |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [Free GST Billing Software](https://github.com/IamRamgarhia/Free-GST-Billing-Software) | Tally, Vyapar, myBillBook | A. Business | Basic | Download ZIP, double-click | MIT | v1.10.83, stable |
| 1 | [OpenConstructionERP](https://github.com/datadrivenconstruction/OpenConstructionERP) | Construction estimating ERPs | A. Business | Basic | Desktop installer or pip | AGPL-3.0 | v19.0.0 |
| 9 | [DRXStore](https://github.com/psvineet/drxstore) | Medical-shop billing software | A. Business | Intermediate | PHP web app (XAMPP) | GPL | v3.0.1 |
| 10 | [LAVSMS](https://github.com/4jean/lav_sms) | School ERP | A. Business | Advanced | Laravel 8 web app | MIT | Last update Sep 2022 |
| 5 | [Concat](https://github.com/jub0t/Concat) | CapCut | B. Creator | Basic | Installer (Win/Mac/Linux/Android) | AGPL-3.0 | v0.2.8 beta |
| 6 | [Canvix](https://github.com/mir-ashiq/canvix) | Canva | B. Creator | Advanced | Self-host (Node + Postgres) | MIT | v0.13.0 |
| 12 | [ArtCraft Launcher](https://github.com/storytold/craft-launcher) | App store for all Craft apps | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.13.0 |
| 13 | [PhotoCraft](https://github.com/storytold/photocraft) | Photoshop | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.19 alpha |
| 14 | [VectorCraft](https://github.com/storytold/vectorcraft) | Illustrator | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.20 alpha |
| 15 | [FilmCraft](https://github.com/storytold/filmcraft) | Premiere Pro | B. Creator | Intermediate | Installer | Apache-2.0 / MIT | v0.16 alpha |
| 16 | [LightCraft](https://github.com/storytold/lightcraft) | Lightroom | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.17 alpha |
| 17 | [PdfCraft](https://github.com/storytold/pdfcraft) | Acrobat | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.17 alpha |
| 18 | [EffectCraft](https://github.com/storytold/effectcraft) | After Effects | B. Creator | Advanced | Installer | Apache-2.0 / MIT | v0.20 alpha |
| 19 | [DesignCraft](https://github.com/storytold/designcraft) | InDesign | B. Creator | Intermediate | Installer | Apache-2.0 / MIT | v0.16 pre-alpha |
| 20 | [FigCraft](https://github.com/storytold/figcraft) | Figma | B. Creator | Intermediate | Installer / build | Apache-2.0 / MIT | v0.14 alpha |
| 21 | [WordCraft](https://github.com/storytold/wordcraft) | MS Word | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.14 alpha |
| 22 | [SoundCraft](https://github.com/storytold/soundcraft) | Audition / DAW | B. Creator | Intermediate | Installer | Apache-2.0 / MIT | v0.16 pre-alpha |
| 23 | [DeckCraft](https://github.com/storytold/deckcraft) | PowerPoint | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.14 alpha |
| 24 | [CADCraft](https://github.com/storytold/cadcraft) | AutoCAD | B. Creator | Advanced | Installer | Apache-2.0 / MIT | v0.16 pre-alpha |
| 25 | [GridCraft](https://github.com/storytold/gridcraft) | MS Excel | B. Creator | Basic | Installer | Apache-2.0 / MIT | v0.15 alpha |
| 26 | [TextureCraft](https://github.com/storytold/texturecraft) | Substance Painter | B. Creator | Advanced | Installer | Apache-2.0 / MIT | v0.2 |
| 27 | [Craft Anything](https://github.com/storytold/craft-anything) | AI app-cloning tool | B. Creator | Advanced | Build with Rust | Apache-2.0 / MIT | v0.2 early alpha |
| 28 | [SolidCraft](https://github.com/tangency-labs/solidcraft) | SolidWorks / Fusion 360 | B. Creator | Advanced | Installer, Snap or web | Apache-2.0 / MIT | v0.30 |
| 7 | [Bagisto](https://github.com/bagisto/bagisto) | Shopify / WooCommerce | C. Developer | Advanced | Docker (1 command) | MIT | Active |
| 8 | [Bagisto Mobile App](https://github.com/bagisto/opensource-ecommerce-mobile-app) | Shopify mobile app | C. Developer | Advanced | Flutter build | MIT | Active |
| 2 | [Fleetbase](https://github.com/fleetbase/fleetbase) | Delivery / fleet software | C. Developer | Advanced | Docker + CLI | AGPL-3.0 | Active |
| 3 | [Navigator App](https://github.com/fleetbase/navigator-app) | Driver delivery app | C. Developer | Advanced | React Native build | AGPL-3.0 | Active |
| 11 | [YouPI-PG](https://github.com/gxurav1710/YouPI-PG) | Razorpay-style UPI gateway | C. Developer | Advanced | Node.js | No license file | Experimental only |

Versions are read from each repo's code on 2 Nov 2026; these apps release often, so check the Releases page before recording.

## Group A: Business software (ready to use)

Free GST Billing is the best first video: Indian, no coding, works offline.

### Free GST Billing Software (Basic)

Makes GST invoices, quotations, bill of supply, credit notes and delivery challans as PDF; GSTR-1 / GSTR-3B / GSTR-2B reconciliation, TDS/TCS, inventory, 22 currencies. Data stays on your PC; no signup. [Docs](https://dicecodes.com/free-gst-software-documentation/)

1. Download the ZIP: https://github.com/IamRamgarhia/Free-GST-Billing-Software/releases/latest/download/Free-GST-Billing.zip (not the green Code > Download ZIP button; that is source code only).
2. Right-click the ZIP > Extract All > pick a folder like `Documents\FreeGSTBill`.
3. Open the extracted folder and double-click `Free GST Billing - WINDOWS` (Mac: `.command`, Linux: `.sh`).
4. Click Install. It installs Node.js if missing; takes 1 to 2 minutes, no admin rights.
5. The app opens at `http://localhost:47371` and adds a desktop icon.
6. Fill business name, GSTIN and bank details, add a client, then create and download your first invoice.
7. Optional: Settings > Privacy & internet > Offline mode stops all automatic internet use.

### OpenConstructionERP (Basic to install, Intermediate to use)

Construction estimating: BOQ, CAD/BIM takeoff from PDF and DWG, 4D scheduling, 5D cost, tendering; 44 languages, 190+ modules. Useful for civil contractors. [Demo](https://openconstructionerp.com) · [12-min walkthrough](https://www.youtube.com/watch?v=X06cIaroAeI)

1. Easiest: download the installer from https://openconstructionerp.com/download (Windows `.exe`, macOS Apple Silicon `.dmg`, Linux `.deb`/`.AppImage`).
2. Windows warns "Windows protected your PC" because it is unsigned: More info > Run anyway.
3. First launch takes about a minute to set up its local database.

Or with Python 3.12+:

```bash
pip install --upgrade openconstructionerp
openconstructionerp
```

It opens `http://localhost:8080`. Demo login: `demo@openconstructionerp.com` / `DemoPass1234!`

### DRXStore (Intermediate)

Pharmacy management: medicines with HSN and GST%, batch and expiry tracking, POS billing (Cash, UPI, card, credit), purchase orders, returns, supplier and customer portals, expiry reports. Data in JSON files (default) or MySQL.

1. Install [XAMPP](https://www.apachefriends.org) (needs PHP 8.0+) and start Apache.
2. Download the repo (Code > Download ZIP), extract it, rename the folder to `drxstore` and put it in `C:\xampp\htdocs\`.
3. Open `http://localhost/drxstore/` in the browser.
4. The Setup Wizard runs: Store Info > Admin Account > Storage (choose JSON) > Confirm.
5. Log in, add medicines (or Import CSV), then bill from POS.

### LAVSMS — Laravel School Management System (Advanced)

Student records, classes, exams and marksheets (print PDF), fees and receipts, timetable, library, noticeboard. 7 roles: Super Admin, Admin, Teacher, Accountant, Librarian, Student, Parent. Last updated Sep 2022 on Laravel 8, and the README says library and accountant pages are unfinished: test only, not for a real school without a developer.

```bash
git clone https://github.com/4jean/lav_sms.git
cd lav_sms
composer install
cp .env.example .env      # then set DB_DATABASE, DB_USERNAME, DB_PASSWORD
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve         # open http://127.0.0.1:8000
```

Demo login after seeding: `admin@admin.com` / `cj` (super admin: `cj@cj.com` / `cj`). Change these before any real use.

## Group B: Creator tools (video, design, office)

Concat is the strongest pick for a Telugu creator audience; the Craft suite is impressive but alpha, so present it as "try it", not "replace Adobe".

### Concat — free CapCut alternative (Basic)

Auto-captions (local Whisper), text-to-speech and voice cloning, background removal, keyframes, 100 effects and transitions, multi-track timeline, voice cleanup, export H.264 / HEVC / AV1 up to 4K 60. No watermark, no account, runs offline. Has a Hindi README; no Telugu interface.

1. Go to https://concatenate.pages.dev/#download (or [GitHub Releases](https://github.com/jub0t/Concat/releases)) and download for your system.
2. Windows: run the setup or `.msi`. If SmartScreen blocks it: More info > Run anyway.
3. Open Concat, drag your clips in, cut on the timeline.
4. For captions, voices and cutout: open Settings and download the AI models once; they work offline after that.
5. Export as H.264 MP4 for YouTube or Shorts.

Beta: expect some rough edges. Android build exists; iOS is sideload only.

### Canvix — free Canva alternative (Advanced: you host it)

Browser design editor: 110 free templates, drag-and-drop, export PNG/JPG/SVG/PDF/video with no watermark; AI features (magic edit, magic write, background removal, translate) use your own API keys. There is no public app to just sign up to; you run it on your own server.

```bash
git clone https://github.com/mir-ashiq/canvix.git
cd canvix
npm install
cp .env.example .env   # paste your Postgres DATABASE_URL (free Supabase project works)
npm run db:setup       # creates tables + loads the 110 templates
npm run dev            # open http://localhost:3000
```

Needs Node.js 20+. For Supabase, use the transaction pooler URL (port 6543).

### The Craft App Suite by ArtCraft (17 apps)

One team ([ArtCraft](https://getartcraft.com/apps)) builds open-source, offline, native look-alikes of the Adobe and Office tools, all in Rust, for Windows, macOS, Linux and the browser. SolidCraft is a community app by Tangency Labs, installed through the same launcher.

How to install any of them (same for all):

1. Easiest: install [ArtCraft Launcher](https://github.com/storytold/craft-launcher/releases/latest) (Windows: `artcraft-launcher-<version>-windows-x64.msi`, no admin rights). It lists every app and installs or updates each with one click.
2. Or download one app from its page, e.g. `https://getartcraft.com/apps/photocraft`, or from that repo's Releases: Windows `<app>-<version>-windows-x64.msi` (installer) or `-portable.zip` (no install).
3. Check the file against `SHA256SUMS.txt` in the release if you want to be safe: `Get-FileHash .\file.msi` in PowerShell.

| App | Replaces | What works today (from its README) | Stage |
| --- | --- | --- | --- |
| [PhotoCraft](https://github.com/storytold/photocraft) | Photoshop | Layers, masks, 16 adjustment layers, layer styles, editable text, Select Subject (offline), filters; opens and saves real PSD files; Photoshop shortcuts | Alpha |
| [LightCraft](https://github.com/storytold/lightcraft) | Lightroom | Photo library and non-destructive RAW development, batch export | Alpha |
| [VectorCraft](https://github.com/storytold/vectorcraft) | Illustrator | Pen and shape tools, Pathfinder, gradients, type; SVG, PDF, `.ai`, EPS, DXF; opens Affinity files | Alpha (\~65% ready for real work) |
| [FilmCraft](https://github.com/storytold/filmcraft) | Premiere Pro | Multi-track editing, trims, multicam, colour grading with scopes, 90+ effects, titles, captions, audio mixing; exports H.264 | Alpha (\~56% ready) |
| [EffectCraft](https://github.com/storytold/effectcraft) | After Effects | Compositions, keyframes, 308 effects, expressions, 3D cameras and lights, render queue | Alpha |
| [DesignCraft](https://github.com/storytold/designcraft) | InDesign | Page layout and publishing | Pre-alpha |
| [FigCraft](https://github.com/storytold/figcraft) | Figma | Frames, auto layout, components, variables, prototypes; works offline; optional collaboration server | Alpha |
| [WordCraft](https://github.com/storytold/wordcraft) | MS Word | Ribbon, styles, tables, track changes, references, mail merge; reads and writes `.docx` | Alpha |
| [GridCraft](https://github.com/storytold/gridcraft) | MS Excel | Spreadsheet and data work | Alpha |
| [DeckCraft](https://github.com/storytold/deckcraft) | PowerPoint | Themes, layouts, tables, charts, transitions, animations; opens and saves `.pptx`; full-screen presenting | Alpha |
| [PdfCraft](https://github.com/storytold/pdfcraft) | Acrobat | Read, organise, combine, split, secure PDFs; Scan & OCR | Alpha |
| [SoundCraft](https://github.com/storytold/soundcraft) | DAW (Audition, FL) | Record, edit, mix, MIDI, plugins, automation; cannot yet pick audio interface or buffer size | Pre-alpha (\~40% ready) |
| [CADCraft](https://github.com/storytold/cadcraft) | AutoCAD | 2D/3D drafting: command line, object snaps, layers, dimensions, hatches, blocks, DXF | Pre-alpha |
| [SolidCraft](https://github.com/tangency-labs/solidcraft) | SolidWorks / Fusion 360 | Parametric sketches, extrude/revolve/loft/fillet, assemblies, sheet metal; STEP, STL, 3MF; also runs in browser | Early but usable for simple parts |
| [TextureCraft](https://github.com/storytold/texturecraft) | Substance Painter | Paint PBR materials on 3D models, layers and masks, bake maps, export presets | Active development |
| [Craft Anything](https://github.com/storytold/craft-anything) | (new idea) | Studies a website, app or game and has an AI coding agent (Claude Code) build your own version | Early alpha, build from source only |
| [ArtCraft Launcher](https://github.com/storytold/craft-launcher) | App store | Installs and updates every app above | Working |

Alpha means it opens and works for basic tasks but may crash or miss features. Keep your original files backed up when testing.

## Group C: Developer platforms (self-host)

These suit AGS and Adyzio more than beginner viewers: they need Docker, a server and some coding.

### Bagisto — online store / marketplace (Advanced)

Laravel + Vue.js eCommerce: single store, multi-vendor marketplace, B2B. [Live demo](https://demo.bagisto.com/) · [Install guide](https://devdocs.bagisto.com/getting-started/installation.html). Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) first, then one command gives a full store with sample data:

```bash
docker run -d --name bagisto -p 80:80 webkul/bagisto:latest
```

Open `http://localhost`. The admin panel and default login are in the [install guide](https://devdocs.bagisto.com/getting-started/installation.html) (not stated in the README).

### Bagisto Mobile App (Advanced)

Flutter shopping app for a Bagisto store: home and search, coupons, guest checkout, wishlist, dark mode, push notifications. Needs Bagisto 2.0+ with the [Bagisto API module](https://github.com/bagisto/bagisto-api), plus Flutter 3.38.9.

```bash
git clone https://github.com/bagisto/opensource-ecommerce-mobile-app.git
cd opensource-ecommerce-mobile-app
flutter pub get
flutter run
```

Before running, set `bagistoEndpoint` and `storefrontKey` in `lib/core/constants/api_constants.dart`. Change colours in the `AppColors` class.

### Fleetbase — delivery and fleet management (Advanced)

Dispatch, drivers and vehicles, live tracking, route optimisation, storefront, warehouse, invoicing, customer portal, AI order creation. Good fit for local delivery in the AGS Srikakulam plan. Needs Docker (Compose v2), Git, Node.js 18+ and 4 GB RAM for Docker.

```bash
npm install -g @fleetbase/cli
flb install-fleetbase
```

Console: `http://localhost:4200` (create the admin account there). API: `http://localhost:8000`. Or use [Fleetbase Cloud](https://console.fleetbase.io/onboard) (paid, free trial).

### Navigator App — Fleetbase driver app (Advanced)

Driver app: orders, navigation, QR scan, digital signature, photo proof, fuel reports, chat. Needs React Native, Android Studio, a Fleetbase API key and a Google Maps API key.

```bash
git clone https://github.com/fleetbase/navigator-app.git
cd navigator-app
yarn
yarn pod:install   # iOS only
```

Create `.env` with `APP_NAME`, `APP_IDENTIFIER`, `FLEETBASE_HOST=https://api.fleetbase.io` and `FLEETBASE_KEY=<your key>`, then `yarn android`.

### YouPI-PG — self-hosted UPI payment gateway (Advanced, test only)

Reads bank SMS and Gmail alerts to confirm UPI payments to your own account, with 0% fees. Its own README calls it an experimental research project, not NPCI or bank approved, and asks you to keep tests under 20 transactions a day. The repo has no license file, so legally you cannot reuse its code. Do not use it to collect real customer money.

```bash
git clone https://github.com/youpi-pg/YouPI-PG.git youpi-pg
cd youpi-pg
npm install
cp .env.example .env
```

Needs Node.js 22.13+. Follow the README's Quickstart for the remaining start commands.

## Safety rules before installing

- Download only from the repo's own Releases page or the official site linked in its README; fake copies with the same names exist on other sites.
- "Windows protected your PC" on unsigned apps (Concat, OpenConstructionERP, SolidCraft) is expected: More info > Run anyway, only for files from the official link.
- AGPL apps (Concat, OpenConstructionERP, Fleetbase) are free to use; if you modify and run them as an online service, you must share your changed code.
- Change every demo password (LAVSMS, OpenConstructionERP) before real data goes in.

## Adytech video plan from this list

| # | Video idea | Level | Format |
| --- | --- | --- | --- |
| 1 | Free GST billing software, offline, no signup: first invoice in 5 minutes | Basic | Long video + Short |
| 2 | Free CapCut alternative with no watermark: Concat auto-captions demo | Basic | Long video + Short |
| 3 | 17 free Adobe and Office alternatives in one launcher (ArtCraft) | Basic | Long video |
| 4 | PhotoCraft vs Photoshop: what works today | Intermediate | Long video |
| 5 | Medical shop billing for free: DRXStore on XAMPP | Intermediate | Long video |
| 6 | Build your own online store with one Docker command: Bagisto | Advanced | Long video |
| 7 | Run your own Swiggy-style delivery system for free: Fleetbase | Advanced | Long video |

Skip YouPI-PG and LAVSMS as recommendations: one is experimental for payments, the other is unmaintained since 2022.

## Sources

All facts come from each repository's README, LICENSE and version files, cloned on 2 Nov 2026. Links are in the tables above. Your source list: WebotApp\_GitHub\_Repositories.xlsx.
