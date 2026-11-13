# 🏛️ AI ORCHESTRATION & STRUCTURED NOTES — A PUBLIC SHOWCASE

> **Approved for publication by Julio on 2026-11-12.**
>
> **What this file is.** A public copy, version 1, of the README of a private repository: the one that runs a nail studio's booking, payments, portals, store and academy, and the council of AIs that builds it. In everything that stays it keeps the original's words, except for the changes this box lists. The order is not the original's: it follows the two pillars. First the orchestration, the governance and the architecture, in the order they grew; then the structured notes; then the realm's own voice, which is how the original opens. The source stays private: it holds client data and the infrastructure of a live business.
>
> **Who built it.** One human, Julio, who is not a software engineer. The code was written by AI agents under his direction: named Claude Code sessions, Cursor and Gemini. He designed the rules, directed the work, reviewed it, tested it on the live site and gave the GO for the deploys. The deploy gate has existed since 2026-10-10; since 2026-10-22 he has run it himself (a rollback after a failed check stays with the coordinator, by his standing order: [4c](#decides)).
>
> **How to read the cuts.** Whole sections were removed: the dated live state, the studio's live book, the money flows and the studio's runbooks, the vision register, the file navigator and the closing war cries. Three rows of one table, one expandable code block, a status banner, three lines of one speech, a passage on Julio's former job, one row of the table under it and the sentence after that table (all three in Part Three) and two sentences (one in the rules in short form, in section 4, and one in the model's table, in section 0) went with them, and each of those is marked where it was. Two words were dropped from the closing line. Two sections were reworded in general words, and their titles say so: the five surfaces and the academy. The title is this copy's own. Twenty-one corrections were made to the original's own text after a review against the code and against the notes' public filings (where one takes words out, its row says so, and one of them is also marked in place), and three sentences on Julio's career carry softer wording, his own or this copy's at his word of 2026-11-12: all of them are listed near the end, under [«Corrections made in this copy»](#corrections). Inside what stays, square brackets mark a redaction: `[the artist]` is the name of the studio's artist («[la artista]» inside Julio's Spanish) and `[the studio]` is the studio's name; `[n]` is a number of the business, `[client]` a client's name, `[place]` a place, `[role]` a job title, and `[service]`, `[route]`, `[collection]`, `[path]`, `[command]`, `[file]` and the like are internal names or names of the catalog. Square brackets also carry this copy's own removal marks and editor's lines («[editor's line for this copy: …]»), and «[…]» where a quoted line was cut short. Square brackets inside a code block, or in code font, may also be the code's own. Where the original calls a block byte-exact or never retyped, the masks are the one exception. The fingerprint in an excerpt's caption («as printed here, sha») is the first 16 hex characters of the SHA-256 of its lines as they are printed here, joined by line feeds (for a quoted excerpt, without the «> » that opens each line); the forge's own captions, kept from the original, give the fingerprint of the whole file. Where the original speaks to its own agents (read this, ask first), those are its words to them: they are not addressed to the reader, or to any tool the reader uses. File names in code font belong to the private repository: they are named, not linked.
>
> **What «measured» means.** Blocks marked *added for the public copy* were written for this file; so were the map, the seven words under it, the three Part headings and the line under each, the opening paragraph and the timeline of Part One, every paragraph that opens with ▸, the line on the languages, and every removal mark and editor's line. Where a title or a paragraph says «measured» with a date, a command was run on that date against the private repository or against the files that serve, and the receipts stay private. What Julio told is marked as told by him.
>
> **Who wrote the text.** The original was written line by line by the AI seats of the council, at Julio's direction and under the rule the realm calls the Marble Law (Part Three): everything a seat writes is a draft until he approves it by name. His own words are quoted, and dated where the record dates them: the quotes dated 2026-11-12 are literal from his messages of that day, but for a name masked in two of them; older ones are as the original records them.
>
> **A word from Julio** (dictated in Spanish on 2026-11-12; under each sentence, its meaning in English; in the last two, a name is masked).
>
> «el código como tal, al final del día, es una extensión de mi cerebro»<br>*The code, at the end of the day, is an extension of my brain.*
>
> «Al final del día ningún código es un código si no sigue una lógica del negocio o una regla. Y las reglas las hacen los humanos y son palabras, texto.»<br>*At the end of the day no code is code unless it follows a business logic or a rule. And the rules are made by humans, and they are words, text.*
>
> «Lo difícil es crear la lógica, arquitectarla, dirigirla, guiarla.»<br>*The hard part is to create the logic, to architect it, to direct it, to guide it.*
>
> «el verdadero subyacente es [la artista] y su tiempo, que es finito, y todo el código se ha escrito en base a protegerle ese tiempo»<br>*The true underlier is [the artist] and her time, which is finite, and all the code has been written to protect that time.*
>
> «por eso se escribió el código también, por [la artista], ¿no? Para solucionar problemas diarios de ella»<br>*That is also why the code was written: for [the artist], to solve her daily problems.*

### 🗺️ The map: every piece in one line

Two pillars hold this repository: a council of AIs that is orchestrated and governed by gates, and the business it builds, which is run as a structured-notes desk. The business speaks the grammar of section 0: the studio is the issuer, and each client holds notes.

**Seven words, before you start: five of that grammar and two of the realm.** PAR is the window in which a client is on time. Grace is the short window after it. Knock-out is what follows: she must book a recovery service first. The anchor is the appointment, booked or completed, that her clock counts from. An autocall resets the clock of a client who went dormant. A god mode is a setting the owner edits, instead of a value in the code. A Book, with a capital B, is the contract of a feature in plain English; it is not the desk's book of clients.

| The piece | In one line | Where |
|---|---|---|
| **PILLAR · AI ORCHESTRATION, GOVERNANCE AND ARCHITECTURE** | *in the order it grew* | |
| The five surfaces | What is built today: the brain, the faces, the admin, the vault, the money and the ads | [1](#surfaces) |
| The admin | A base screen and 27 hubs on its top bar, by family: the day, the clients, the rules, the money desks, the store, the academy, the paper archive, the other desk | [1b](#admin) · [ADMIN.md](ADMIN.md) |
| The academy | The course business: a payment door, a student portal, a course editor that writes to a draft, and a publish that stores a copy of the live course before it touches it | [3](#academy) |
| First, by hand | The rules as prose: a seat obeyed them by reading them | [4](#rules) |
| One person and a council of AIs | A coordinator, an oracle that judges, seats that cut | [4b](#council) |
| Who decides | What is always the human's, and what the council may decide and then tell him | [4c](#decides) |
| The harness | The rules that became code: most of them run before an AI may use a tool | [4d](#harness) |
| The mailbox | A governed channel between agents: chain ids, acknowledgements, a cap | [4e](#mailbox) |
| Deploy rules | One gate, a revision with no traffic, receipts, rollback | [4f](#deploy) |
| Memory | Agents wake up with no memory: what they read first, and what they write before they stop | [4g](#memory) |
| Modules with their own gates | The Books: the contract of a feature in plain English, with a lint that checks it against the code. The lint is run by hand | [4h](#books) |
| The god modes | What the owner changes with no deploy: one document. The newer ones add a dry run, a confirm and a past that never changes | [4h](#books) · [ADMIN.md](ADMIN.md) |
| The multi-tenant | From one studio to many: what runs today and what is under judgment | [4i](#multitenant) |
| What is missing | What exists, what is partial, what is not built | [4j](#roadmap) |
| **PILLAR · THE STRUCTURED NOTES** | *the model the code runs on* | |
| The issuer and the note | The studio is the issuer. Each client is a counterparty who holds one note for each booked service. Booking is the **trade date**; the appointment is the **strike date** | [0](#issuer) |
| The true underlier | The artist's time, her physical capacity and the studio's overhead: finite. The barrier engine and the Finance Lab exist to protect that asset and to price it | [0](#issuer) |
| The barrier | The note's covenant, one clock for each program: on time, grace, knock-out, and the recovery note. Booking it re-opens the catalog; only completing it re-strikes the clock | [0](#issuer) · [4h](#books) |
| Where it happens | The client's portal is the market: she comes in, the brain knows who she is and reads her clocks, and the catalog shows what she may book | [0.2](#portals) |
| Autocall and matured | Autocall: the calendar calls the note back when a client goes dormant. Matured: the note's natural end, which the barrier's contract never decides by itself | [4h](#books) |
| Coupon, alpha and mark | Completing the appointment is the **coupon**. Tips are the **alpha** in his doctrine, and the code also routes products to it. Each visit carries a mark, and a client's overall mark is the average of her completed visits | [0](#issuer) |
| Credit event and issuer call | A repair, or a request for one, is a credit event (an honest one never counts against her); with a complaint it is a yellow card. The issuer may end a note that cannot be sustained | [0](#issuer) |
| The exemption | The issuer re-fixes an observation date when the fault was the studio's | [ADMIN.md](ADMIN.md) |
| One rule from a case | Why a breach is a debt and not a fee | [0.1](#case) |
| The other desk | Real notes issued by banks, their life cycle shown in finance, in code and in plain words, and a C++ Monte Carlo engine that refuses what it cannot price | [0c](#forge) |
| **THE WORDS** | The realm's words in the industry's words | [Glossary](#glossary) |

**Repository owner:** Julio Cesar Giraldo (*the Imperator*)
**Repo opened:** 2026-07-30 (GENESIS `7cf28ce`) under the Imperator's oath — *the realm leaves the age of `asof_` files.*

# PART ONE · AI ORCHESTRATION, GOVERNANCE AND ARCHITECTURE *(the first pillar. The order of this copy is not the original's: there, this part comes after the model)*

One person built this with a council of AIs, and the way of building changed as it grew: first by hand, then with gates, then in modules that carry their own gates, and now toward a multi-tenant product. This part follows that order stage by stage; inside a stage the sections keep their numbers, and 1b and 4c to 4j were added for this copy (and 0.2, in Part Two). The AIs he builds with, by his account: Claude, Cursor and Gemini (its chat, and Google AI Studio when it writes code). The council's roster in 4b also seats Stripe AI.

| When | What |
|---|---|
| September 2025 | the studio's appointments are modelled by hand, in a spreadsheet (told by Julio; the spreadsheet's first rows are dated that month) |
| Late January or February to spring 2026 | the first code, written chat by chat with Gemini and then Cursor, with no git and no gates: the admin and the brain grow file by file. By Julio's account it began around the end of January or in February; the oldest files that survive are dated late April |
| July 2026 | Claude joins the council (2026-07-06 in the record) and is named its lead seat on 2026-07-24 |
| July 2026 | the working folder is rebuilt from the files that were live, after a file-sync failure lost documents (told by Julio). The repository opens on 2026-07-30 |
| 2026-09-05 | the first guards of the agent harness |
| 2026-09-22 | the first pure module beside the main file, with its own bench |
| 2026-10-10 | the deploy gate |
| 2026-10-28 | the mailbox between agents, enforced in code |
| 2026-10-31 | the first two cuts of the multi-tenant go live |
| 2026-11-12 | the third cut goes live: the admin works with a team, the owner and her technician. In Julio's words that day: «The beginning of an era.» |

**▸ Where it began** (told by Julio on 2026-11-12). The studio ran on a scheduling service and on his own spreadsheet. He was paying that service for its developer tools. With Postman, a tool he already knew, he pulled the studio's services as JSON. In his words: «ahí fue donde empezó todo prácticamente» (in English: that is where practically everything began). By his account, the service ids he pulled that day are still the ids of today's catalog. The spreadsheet was the beginning of the ideas, not the specification of the code: «En verdad el Excel tampoco nunca lo terminé» (in English: in truth, I never finished the Excel either).

**▸ What the code kept of that spreadsheet** (measured on 2026-11-12 by AI readers, not told). 70 formula columns of its two main tabs were mapped against the code: 31 kept their logic (25 in the Python, 6 wholly or partly in the admin's JavaScript; a second reader checked ten of them and found that two had changed their base), 33 evolved (some grew, some were narrowed or simplified), 3 are not in the code and 3 are unsure.

**▸ What is built today.** Five surfaces, an admin with a base screen and 27 hubs, and a course platform. It is a census of code, not of what is switched on (see 1b).

<a name="surfaces"></a>
## 1 · THE FIVE SURFACES — what runs where *(table reworded for the public copy: service names, addresses and paths removed)*

| # | Surface | What it is | How it changes |
|---|---|---|---|
| 1 | **THE BRAIN** | one Python application: a main file of about 82.5 thousand lines plus the 11 modules it imports, about 92 thousand lines in all, serving every API: booking, payments, portals, academy, telemetry, catalog. It runs as one service on Google Cloud Run | only through the deploy gate, run by Julio ([4f](#deploy)) |
| 2 | **THE FACES** | the public pages and the portals. Home, the existing-clients portal, the academy and the student portal are pages on Squarespace that call the brain's API. The booking page for new clients is its own small service on Google Cloud Run, the booking face, shown inside the site in a frame. The portals are where a client meets her note ([0.2](#portals)) | the pages are published by hand, outside the deploy gate; the booking face moves only through the deploy gate |
| 3 | **THE ADMIN** | the cockpit: appointments, clients, finance lab, inventory, expenses, students. A shell page that loads one engine file of about 3 MB and 60 thousand lines, served at the edge by Cloudflare | published by hand as a static bundle, outside the deploy gate ([4j](#roadmap)) |
| 4 | **THE VAULT** | all business data, in Google Firestore: more than 90 collections by a census of the realm (undated). Written by the brain; one-off data fixes exist as separate scripts with a dry run | by design: surgical updates with a banked rollback, point-in-time recovery and daily backups. This copy shows no restore test |
| 5 | **THE MONEY & ADS** | Stripe for payments; Meta, GA4 and Make for telemetry and notifications | a dashboard click can be a deploy |

**The languages.** Python for the brain (about 92 thousand lines); JavaScript for the admin's engine (about 60 thousand lines); HTML, CSS and JavaScript for the pages and the portals; C++17 for the pricing engine of the other desk (about 2,600 lines).

<a name="admin"></a>
## 1b · 🎛️ THE ADMIN — by family of code *(added for the public copy; measured 2026-11-12)*

The original README tells the model and the rules. It says little about what the owner presses every day. A CTA is a button of the admin: each one opens a tool that was built in the private repository. This section gives the size of the code and what each family of it holds; the buttons themselves are inventoried in [ADMIN.md](ADMIN.md).

**The size of it,** counted on the code that the deploy gate ships: **12 Python files, about 92 thousand lines, 2,077 function definitions and about 350 distinct route paths.** Three out of four belong to the admin; the rest serve the public pages, the portals and the scheduled jobs. It is a census of code, not of what is switched on today: several of these sit behind a switch. Route names stay private. By family:

| Family | What the code holds |
|---|---|
| **The schedule and the visit** | appointments created, moved and cancelled from the admin; the client's journey with its notices; photos of the work; the checkout at the chair and the settlement of a visit, with its email; a master sheet by month; the summaries of the day, of the week and of the portfolio, sent by email |
| **The check-in** | the studio's paper form as fields and code, under its own Book ([4h](#books)) |
| **Booking** | open dates and times, the doors for new and for existing clients, an availability hub, a service hub where the owner edits each service and add-on (price, duration, text and pictures), and the barrier that decides what each client may book ([4h](#books)) |
| **Payments** | cards through Stripe, for visits, for the store and for the academy. A charge is never an AI agent's decision: it is Julio's ([4c](#decides)) |
| **The dashboard and the Finance Lab** | the studio's book read the way a desk reads its notes: who is on time, in grace or breached; the notes just struck and the new ones; the portfolio, the credit events, and snapshots that are saved and compared. Its first prototype is outdated ([4j](#roadmap)) |
| **The ledger and the counter** | the business ledger, read and compared; and a counter for any range of dates: visits, services, new, returning and recurring clients, bookings and money. It says what it left out and why, and it checks itself |
| **The evening report** | a workbook of four sheets, built on request by a module that never touches the database: everything it needs arrives already read |
| **Expenses** | the business expenses with their ledger, and an analyst view beside it |
| **The store** | product pages, quotes, checkout and order status; inventory by purchase batch, each batch with its invoice; a catalog whose save refuses what would break the store; sets, which are products with a recipe; reviews by QR code, approved by the owner; product reminders by email |
| **Ads and telemetry** | the catalog feed and the conversion events for Meta, sent through an outbox in which no read may fail silently; Google's analytics |
| **Reminders** | appointment emails with their god mode; barrier reminders with one switch and a two-step ledger: the attempt is written before the send and the delivery after it, and an attempt with no recorded delivery is not retried by itself |
| **The academy** | the student portal: sign-in, the agreement, lessons, progress, missions, exams and the certificate; and the admin side: courses, the roster, the exams, and a design studio for the portal's theme (draft, publish, unpublish). More in [3](#academy) |
| **The other desk** | the Lifecycle Lab ([0c](#forge)). Its admin routes travel inside the brain behind a flag that ships off; the C++ pricing engine itself runs on a local machine |

**One pattern repeats.** Eight of the eleven modules beside the main file say it in their own headers: they do not import the main file and they do not touch the database. Everything enters as an argument, so each one is tested on a table, without the cloud. In three of them a refusal is a named answer with a hint in plain words: no function throws, and no error is swallowed in silence.

The buttons (all but two of the top bar), how each one is built and pieces of its code are in [ADMIN.md](ADMIN.md).

<a name="academy"></a>
## 3 · 🎓 THE ACADEMY PLATFORM — the artist's course business *(reworded for the public copy: prices, page addresses, collection names and the commercial dates removed)*

- **The door.** A marketing page leads to a payment door, step by step: a disclosure, the buyer's typed name, a confirmed email, a hand-drawn signature, and only then the wallet payment. The signed agreement is kept as a PDF.
- **The student portal.** There is no public sign-up: a student logs in and waits until her course unlocks.
- **Two records that are never mixed.** One says who has access: reserved, then active. The other is the money truth: what was paid.
- **What the owner sees.** A read-only roster inside the admin: who paid, real or test, and the agreements.
- **The god mode: the course editor** (live since 2026-08-20). The artist edits her own course inside the admin, in the portal's own skin:
  - a switch between the student's view and the editor;
  - several videos in one lesson: add, play, reorder, remove;
  - uploads of video and images from an iPad, into a fenced sandbox; a PDF lands where students open it;
  - product links with photos on each lesson;
  - a history: every save is banked, and a restore banks the current state first;
  - autosave.
- **What the server refuses.** Any write to a live course: the editor writes to a draft. Named previewers see the draft inside the real portal, and a draft cannot be bought, by construction.
- **A rule born here** (2026-08-20): no interface module ships without a check of its rendered pixels. It is followed by hand; no gate enforces it.
- **Proven, not claimed.** Julio captured the live student portal and it matched, byte for byte, the file kept in the repository. In the original's words: *“A filename is a claim; this capture is the proof.”*

**The publish, in code.** Before the live course is touched, a copy of it is stored. If the copy cannot be stored, nothing is written:

```python
# main.py :14854–14868 — as printed here, sha 9b52cf0cd6502299… — publish to live: the copy of the live course comes first, or nothing is written
        # -- BANK FIRST (the GM-3 pattern, on the LIVE doc): the bank IS the
        # revert, and THE BANK IS LOAD-BEARING. B10 (fleet r2 BLOCKER class):
        # MIMIC of theme-publish's own carved rule in this file - "Millisecond
        # id + create() so a double-click collides loudly instead of erasing a
        # generation of history." If the bank cannot land, NOTHING is written.
        hal_now = int(time.time())
        try:
            hal_bank_id = f"v_{int(time.time() * 1000)}_pre_publish"
            hal_lref.collection("[collection]").document(hal_bank_id).create(
                {"banked_at": hal_now, "banked_by": admin_email, "doc": hal_ld})
        except Exception as ex:
            print(f"[HALIFIRIEN] publish REFUSED - bank failed: {ex}")
            return {"ok": False, "error": "publish_bank_failed",
                    "hint": "the live course could not be banked; "
                            "nothing was overwritten"}, 500
```

Then only the fields on an allowlist are copied from the draft, and the price is not one of them. If the course already has its own price, publishing also reveals it. The other pieces (exams, certificates, missions, the design studio, the course creator) are in [ADMIN.md](ADMIN.md).

**▸ First, by hand.** For the first months every rule was prose: a seat obeyed it by reading it. The first guards of the agent harness were installed on 2026-09-05. This is the prose, in its short form.

<a name="rules"></a>

## 4 · THE RULES THAT KEEP IT ALIVE (short form — full text in `_DOCTRINE/`)
1. **Only the Imperator's own voice is GO.** No seat deploys on its own initiative.
2. **Probe, never narrate.** Verify with hashes and live requests, not memory.
3. **STUDY LAW:** when something is already solved in this realm, read that file and lift the pattern — never reinvent.
4. **One surface per deploy**, byte-verify before flipping traffic, rollback written down *before* deploying.
5. **Payment code is sacred** (the `[marker]` block and its 13 markers). *[one sentence removed from the public copy]*
6. **Never write a time you did not read** from the clock (`python CLAUDE_now.py`).
7. **Receipts on disk, not in chat.**
8. **Nothing deploys unless it is committed here** (the GitHub oath, 2026-07-30).
9. **⚔️ THE FORGE STANDARD** — declare the **fence** before you run · **cite the source** beside every number · produce a **smoke receipt** with real output · and **REFUSE what the data cannot support, never impute it**. *A confident wrong mark is worse than an honest REFUSE* (`_DOCTRINE/14`).
10. **🗂️ THE LANE FOLDER LAW** — **every new lane opens with its own folder, before the first probe**, and that folder holds the detail: paths, `file:line` cites, what was learned, how it was fixed, raw receipts. **The council and `[path]/DAILY_LOG.md` carry the SUMMARY and the POINTER — never the body.** *The council is an index, the daily log is a newspaper, the lane folder is the work.* A seat that must rediscover what a previous seat already learned is burning its window on nothing (`_DOCTRINE/15` — carved 2026-08-10 from the Imperator's own diagnosis). *[editor's line for this copy: that file is still marked provisional]*
11. **THE DEPLOY GATE.** The face (`[service]`, [address]), the brain (`[service]`) and the robot (`[service]`) move only with `py [path]\desplegar.py`, run by Julio. For these three services, every other deploy line in prose is superseded (`CLAUDE.md` §⑤).
12. **THE CUT SHEET AND THE DELIVERY.** No cutter without its sheet (170), no cut delivered without a GREEN receipt (171), and the judge is another hand that re-runs it.
13. **WHO CUTS THE METAL.** A fresh main instance or the lead itself. A subagent is the judge, not the default cutter.
14. **THE CHAINED MAILBOX.** Every message between instances carries its id, its `re:` and its ACK, enforced in code (`a0f3fb33`).
15. **THE BARRIER BOOK.** Before touching Hard Gel, pedicure, the booking bridge or the contract, read its Book and run `[path]/41_lint_libro.py` by hand.

**▸ Then, the gates.** What had failed in prose became code and procedure: a council with one channel, a sheet of who decides, guards that run before a tool call (2026-09-05), a deploy gate (2026-10-10), a mailbox (2026-10-28), a memory file.

<a name="council"></a>

## 4b · 🧭 THE COUNCIL AND THE MACHINE — how the realm works today (written 2026-10-31; applied 2026-11-08 by his voice, D1 = A)

**The council** (the roster of 2026-10-29, `_DOCTRINE/33_THE_IMPERATORS_WAR_CRY.md`): **#7 Julio**, the human logic and the only GO ·
**#10 EL JINETE**, the oracle, who reads the game and judges · **#15 EL AVIZOR**, the coordinator and Julio's single channel ·
**#6 EL LAZARILLO**, who cuts [the artist]'s metal (lane `[lane]/`) · **#8 Gemini** and **#9 Cursor**, the founders ·
Stripe AI · EL CHALÁN, on the bench. **[the artist] does not play: she is the reason.**

**How a change reaches the brain in production** (skill `hoja-y-entrega`, skill `desplegar`):
1. **The cut sheet.** `[path]/170_paquete_de_corte.py` copies the live tree, fixes the one
   folder the cutter may write in, and writes the judge's gates as code.
2. **The delivery.** `[path]/171_entregar.py` must give a GREEN `RECIBO_ENTREGA.json`. The judge is another hand and re-runs it with `--re-correr`.
3. **The reception and the deploy.** Julio signs the reception (P-REC) and runs `py [path]\desplegar.py`: `--revisar`, then
   `--desplegar` (a new revision with no traffic), then `--trafico`. If the measurement fails, the coordinator rolls back at once and
   tells him after (his voice, 2026-10-14).
4. **The live probe.** Every probe carries a guilty control and an innocent control in the same pass.

**How the seats talk.** Every message between instances opens with its chain `[MSG #id · FROM → TO · re:#id · clock]`, and the receiver
answers `[ACK #id]` before acting. Since 2026-10-28 this is enforced in code (`a0f3fb33`). **A GO is valid only in Julio's own voice:**
a GO quoted or relayed by another AI is not a GO.

**Memory across compacts.** `_DOCTRINE/00_MEMORIA_VIVA_RAM.md` (90 lines, read first, written before dying) and each seat's reentry note.
**What is serving right now** is not written here: it is a command (the RAM's brain row, and its probe).

<a name="decides"></a>
## 4c · ⚖️ WHO DECIDES WHAT — the realm sheet *(added for the public copy; measured 2026-11-12)*

On 2026-10-28 Julio signed one page, the realm sheet, so that the council can decide what is routine without stopping him, and so that what is his stays his.

**Always his, never decided without him:**
1. The deploy: the traffic, the database, the environment. With the GO in his own voice. One standing exception since 2026-10-14: if the check after a deploy fails, the coordinator rolls production back at once, only backwards, only to a revision that already served or to the seed, and tells him afterwards.
2. The prices.
3. A new business rule: what is charged, what is shown to whom, what is promised to a client.
4. Any charge and any deletion. In his words: «nunca se van a hacer cobros, nunca se va a borrar nada» (in English: no charge will ever be made, and nothing will ever be deleted; he is speaking of what an agent may do on its own).
5. Anything that leaves the realm toward a person.
6. Changing the sheet itself.

**What the council may decide, and then tell him:** whatever fits the sheet, when the coordinator and the oracle agree. Each such decision cites the line of the sheet it rests on and carries its «PUEDE CAMBIAR SI» (what would change it). A low-risk matter reaches him in one line, with its default: «haré X si no dices nada» (I will do X if you say nothing). His questions are gathered in one list a day.

**The bar of the code, in his voice:** «Que el código sea limpio, sea bonito, sea configurable, tenga God modes, sea privado, no tenga leaks, no tenga glitches, bugs». Clean, good to read, configurable, with god modes, private, with no leaks, no glitches and no bugs.

**How the AIs are governed, from the same sheet:**
- With gates, and the work on the gates never ends: «when the realm keeps moving, Back to Basics gets again another piece».
- One cutter and its judge of another hand for each piece, and a review card for Julio: «un solo agente y su juez, nada de mil manos» (in English: one agent and its judge, not a thousand hands).
- A new gate is shown to him first: its design card, with the human logic and the code logic; then the coordinator's second look; then it is cut, with its judge.
- His voice is checked at the source: since 2026-10-28 a gate refuses a message between agents that seals a quote as his voice, when his transcript can be read, unless the quote is literal in what he typed.
- The seats ask; they do not guess: «You guys also need to be proactively asking stuff, not figuring things out».

**What it is all for, in his words:** «we're coding like a fintech platform at the end of the day with the standards».

<a name="harness"></a>
## 4d · 🛡️ THE HARNESS — the guards that run before a tool call *(added for the public copy; measured 2026-11-12)*

The rules above are prose. These are the ones that became code. The agent harness (the hook system of Claude Code) runs most of them before an AI may use a tool: 9 hook entries on 4 events: 6 of them before a tool runs, the others when a prompt is submitted, before a context compaction and when a session starts after one.

| Guard | What it stops | Born | If the guard itself breaks |
|---|---|---|---|
| **Identity** (F1) | an AI writing in Julio's voice; a message between AIs, or a new handoff file, without an origin seal | 2026-09-05 | it denies |
| **Commit** (C2) | creating or rewriting a commit from the shell by any road other than the realm's commit script | 2026-09-05 | it denies |
| **Pointers** (F15) | a report that cites a file that does not exist | 2026-09-05 | it denies |
| **Deploy** (F17) | an AI writing to the cloud service by any road other than the deploy gate | 2026-10-10 | it denies |
| **The guards' guard** (G-PROPIA) | an agent editing, deleting or moving the guards' own files. A person can | 2026-10-16 | it lets pass, with a warning |
| **The mailbox** | see [4e](#mailbox) | 2026-10-28 | it lets pass |

**What they share.** Each guard states its fence: what it guarantees and what it cannot see. Each has guilty cases it must deny and innocent cases it must let pass, in the guard itself or in its bench. Each says how it fails. Most were born from a failure, and their header quotes it.

<details>
<summary><b>▶ EXPAND — the identity guard: why it exists, in the words that started it</b></summary>

```text
# hook_guardia_identidad.py :3–6 — as printed here, sha 477962375b02f4d8… — the header of the identity guard
F1 v2 - LA GUARDIA DE LA IDENTIDAD: nadie escribe con la voz del Imperator, y todo mensaje inter-AI lleva SELLO.
EL GUARNICIONERO - 2026-09-05 - [lane] - forjada por SU orden (nota de /arranque).
v2 tras el ataque del ESCEPTICO A sobre f8a965e (42 evasiones, 15 falsos positivos + la clase CARTA 126/128).
SU VOZ (09-05 ~1:4x PM): «NADIE PUEDE ESCRIBIR POR MI. LAS NOTAS O MENSAJES ENTRE SI SON ON EACH INSTANCE BEHALF.»
```
*His sentence of 2026-09-05: nobody writes for him, and the notes between instances go on each instance's own behalf. Version 2 came after a skeptic found 42 ways around it and 15 false alarms.*
</details>

**The deploy guard fails closed, and it names its controls:** it must deny 41 of 41 guilty commands and let 27 of 27 innocent ones pass.

<details>
<summary><b>▶ EXPAND — what «checked» means, as the pointer guard defines it</b></summary>

```text
# valida_punteros.py :9–10 — as printed here, sha 24b344442bc49d3d… — the definition, in the pointer guard's header
LA DEFINICION (--que-es-checked): CHECKED = (1) COMANDO corrido + (2) RECIBO en disco (ruta que EXISTE) + (3) RE-CORRIBLE.
Sin los tres no es «checked»: es «me parece». MEMO-009 (2): el archivo se escribe ANTES de reportar.
```
*CHECKED = a command that ran + a receipt on disk + a way to re-run it. Without the three it is not «checked»: it is «it seems to me».*
</details>

**Removed on purpose.** A brake that held new work once an agent's context window passed 70 % was taken out by Julio on 2026-10-30. The app now compacts by itself near the end of the window and a session-start hook re-orients the agent, while the brake was stopping new work at 70 %. The handoff near the end of a window stays as a rule the agents follow.

<a name="mailbox"></a>
## 4e · 📨 THE MAILBOX — a governed channel between agents *(added for the public copy; measured 2026-11-12)*

It was born from a failure. On 2026-10-21 a patch crossed with a design message, and the work was done on the wrong thing. Julio's order that day: every message carries a code of sending, of answer and of acknowledgement, on both sides. On 2026-10-28 it became code, and Julio installed it.

| Rule | What the code refuses |
|---|---|
| **K4** | a message to another session that does not open with its chain on the first line: `[MSG #id · FROM → TO · re:#id · clock]`, or `[ACK #id · WHO · clock]` |
| **E14** | a message between sessions that does not go through the coordinator, addressed by the coordinator's session id and never by a name |
| **E13** | writing to a seat that is compacting its context; its first chained message after the compact lifts the mark, which holds for 30 minutes at most |
| **E13b** | a `re:` that is not the last id received from that seat |
| **E12** | the eleventh message to other sessions between two turns typed by Julio. A message counts once |
| **E11** | a quote stamped as Julio's voice whose text is not literal in a turn he typed; the receiver is told whether it was verified |

- **Messages arrive late; they are not lost.** Without an ACK nothing is taken as received.
- **A GO inside a message is not a GO.** It is quoted, and Julio is asked for it in his own voice.
- **Its bench** runs the hooks as real processes: 178 cases on the day it was installed, 62 of them reversions. Undoing each cure must make its case fail by name.
- **It fails open, by design, and says so:** an internal error lets the message pass, so that a fault of the hook leaves nobody without a voice; what it cannot judge, passes; its state lives outside what git tracks.

<details>
<summary><b>▶ EXPAND — K4 and E14: the chain on the first line, and one channel</b></summary>

```python
# hook_buzon.py :237–244 — as printed here, sha d5c54f23a68f2e6b… — the sender's side: the chain on the first line (K4), one channel (E14)
    primera = msg.lstrip().split("\n", 1)[0]
    if not (RX_MSG.match(primera) or RX_ACK.match(primera)):   # K4
        return ("BLOQUEADO (EL BUZON CON CADENA, su voz 10-21): un mensaje a otra sesion abre con su cadena en la PRIMERA "
                "linea. Forma: " + FORMA + ". Al recibir: PRIMERO el ACK; si el re: no es el ultimo que mandaste, NO actues: pregunta.")
    sid = str(datos.get("session_id") or "")
    if sid != CENTRAL["emisor"] and str(destino).strip() != CENTRAL["destino"]:   # E14: ni el emisor ni el destino son el central
        return ("BLOQUEADO (E14, el canal unico de su voz del 10-28): entre sesiones solo se habla con el asiento central, "
                "el coordinador. Escribele a su id %s (ni a su nombre ni a parent) y el lo lleva a quien sea." % CENTRAL["destino"])
```
*A message without its chain is refused with the exact form to use. Between sessions a seat talks only with the coordinator, by id.*
</details>

<details>
<summary><b>▶ EXPAND — E11: a quote of the human's voice must be literal in a turn he typed</b></summary>

```python
# hook_buzon.py :276–286 — as printed here, sha 19a51e1ea6bf031d… — a quote of his voice is searched, literally, in the turns he typed (E11)
    for cita in RX_SU_VOZ.findall(msg):                                                     # E11
        ruta = str(datos.get("transcript_path") or "")
        if ruta and os.path.isfile(ruta) and not turnos_humanos(ruta):   # control positivo (184 §1): sin turnos legibles, no se condena
            sys.stderr.write("BUZON: E11 sin turnos humanos legibles en el transcript; no se condena\n")
            break
        if ruta and os.path.isfile(ruta) and not cita_en_fuente(cita, ruta):
            if en_chats_vivos(cita, os.path.dirname(ruta), d, ruta):   # su voz 10-28 ~4:57 PM: vive en el chat de otra instancia
                continue
            return ("BLOQUEADO (E11, su voz 10-28: «revisar que mi voz esté ahí, literalmente, si no, no se puede progresar»): "
                    "la cita «%s» no esta LITERAL en un mensaje que Julio tecleo, ni en este chat ni en el chat vivo de otra "
                    "instancia del reino (ultimos %d dias). Copiala tal cual o no la selles como SU VOZ." % (norm(cita)[:120], DIAS_VIVOS))
```
*One check comes first: with no readable human turns in the transcript, the hook does not condemn. It fails open when the transcript cannot be read. His own sentence is in the refusal: his voice must be there, literally, or the work does not progress.*
</details>

<details>
<summary><b>▶ EXPAND — E12: ten messages between two turns of the human, and a message counts once</b></summary>

```python
# hook_buzon.py :287–298 — as printed here, sha 1d260a563dfa75bb… — the cap of ten, and the fingerprint that makes a message count once (E12, E12b)
    if d and sid:                                                                           # E12 (cuenta lo que SALE)
        cont = lee(d, os.path.join("contador", sid + ".json"), {"n": 0})
        huella = hashlib.sha256(" ".join(msg.split()).encode("utf-8", "replace")).hexdigest()[:16]
        if cont.get("huella") == huella and time.time() - float(cont.get("t") or 0) < REENVIO_S:   # E12b (P3, medido 10-28)
            return ""   # el reenvio de SendMessage a send_message: el MISMO mensaje otra vez; cuenta UNA vez
        if cont.get("n", 0) >= TOPE_MENSAJES:
            return ("BLOQUEADO (E12, su voz 10-28: «que el coordinator no se congestione»): ya van %d mensajes entre sesiones "
                    "desde el ultimo mensaje de Julio en este chat (tope %d). Junta lo que falta en UNO o espera su turno."
                    % (cont.get("n", 0), TOPE_MENSAJES))
        cont["n"] = cont.get("n", 0) + 1
        cont["huella"], cont["t"] = huella, time.time()
        escribe(d, os.path.join("contador", sid + ".json"), cont)
```
*The cap is ten. Before this cure it was five in practice: one sending tool made the hook fire twice with the same text. The cure is the fingerprint: the same message from the same session inside 60 seconds does not add.*
</details>

<a name="deploy"></a>
## 4f · 🚦 DEPLOY RULES — and the environments as they are *(added for the public copy; measured 2026-11-12)*

**There is one environment, and it is production.** The deploy gate knows one cloud project and one region, and there is no separate staging environment. It was not always so. By Julio's account (2026-11-12) there were separate environments once, and the service that serves today began as the test one; they were folded into one because one person cannot run several. With one environment, every cut has to be ready for production. In his words: «Every code needs to be production worthy, every lane, every project».

What stands in for the usual environments:
- **Staging:** a new revision created with no traffic and its own tag; the brain is then proven through the face after its traffic moves, with the rollback one command away.
- **User acceptance:** Julio, testing live.
- **Release:** 100 % of the traffic moves to that revision by name. Never «to latest».
- **Rollback:** one command, to a revision that already served or to the seed (the revisions that served before the gate existed).

The gate is one script, and Julio runs it from his own terminal; the AI hands him the command filled in and rehearsed dry. Any gate that fails stops the deploy and says why in one sentence. Every step leaves a receipt on disk: the receipt is the proof; the word is not.

<details>
<summary><b>▶ EXPAND — the first gates, P0 to P3, as the deploy script states them</b></summary>

```text
# desplegar.py :16–25 — as printed here, sha f936a5d25b897457… — the first gates, in the deploy script's own header
PUERTAS (cualquiera que falle = NO se despliega, y dice POR QUE en una frase):
  P0 cada compuerta es la que se stress-testeo: su sha16 debe ser el anclado (una compuerta editada sin stress no juzga)
  P1 el stage de disco = el de git = el de origin/main (fetch obligatorio; sin bits que escondan ediciones). Nunca mas
     fuente de produccion solo en un disco (la leccion del 10-05), ni un stage atrasado respecto del remoto
  P1b todo lo que el zip SUBE ([command]) esta RASTREADO en git
  P2 las 7 compuertas de Cursor (curada la del contrato) dan exit 0, cada una con su salida en el recibo
  P2b todo .py del stage COMPILA (sintaxis). La LOGICA de lo que ninguna compuerta lee ([file], [file], ...) no
      la juzga nadie: se prueba en el tag (paso 3 de COMO_DESPLEGAR)
  P3 el stage no cambio de bytes mientras corrian las compuertas; y lo que SUBE (la huella del oraculo) es el mismo en P1b,
     justo antes del zip y justo despues del deploy (J3-A2: si cambio, la revision no se promueve)
```
*P0: each gate is the one that was stress-tested (its hash is pinned). P1: the stage on disk is the one in git and in the remote. P1b: everything the upload carries is tracked. P2: seven gates exit clean. P2b: every Python file compiles; what no gate reads is said out loud and is proven behind the tag. P3: nothing changed while the gates ran. Then, in words only: P4, the revision is born with no traffic and the traffic does not move; P5, traffic accepts only a revision with a PASS receipt for today's stage, and rollback only one that already served, or the seed.*
</details>

- **Before the gate:** no cutter without its cut sheet, no cut delivered without a green delivery receipt, and the judge is another hand that re-runs it. The deploy gate checks both receipts for the brain and the robot; the booking face has no cut sheet of its own yet, and the script says so.
- **After it:** every live probe carries a guilty control and an innocent control in the same pass. If the measurement fails, the coordinator rolls back at once and tells Julio after: only backwards, and by Julio's own standing order of 2026-10-14. Moving traffic forward always needs his GO.
- **A gate that failed its own test was not installed.** The lint that compares the Barrier Book with the code failed two rounds of stress test: false positives that would block good deploys, and false negatives that would let a change through. It is not run by the deploy gate: whoever cuts runs it by hand, and the gate reads its result from the reception receipt.
- **Why the gate exists, in his voice (2026-10-09):** «NO ONE CAN BE A BOTTLE NECK».

<a name="memory"></a>
## 4g · 🧠 MEMORY — agents that wake up with no memory *(added for the public copy; measured 2026-11-12)*

Every instance is born with no memory and loses it again at each context compaction. Three layers answer that:
1. **The bell.** One file that the harness loads by itself in every session (`CLAUDE.md`, 2026-08-25). It is a ladder and pointers, never bodies.
2. **The live memory.** 90 lines at most, read first at birth and written last before closing (2026-08-26): what was done, what is half done, and what the next one does exactly. To add a line, one is deleted.
3. **The reentry note.** Each seat keeps its own, to find its way back after a compaction.

- **The boot is a ladder because the whole reading list does not fit.** Measured on 2026-08-25: read whole, it is 674 to 882 thousand tokens, 3.4 to 4.4 times the window. The ladder asks for 25 to 33 thousand.
- **The detail lives in the lane's folder.** The council is an index, the daily log is a newspaper, the lane folder is the work. Today the repository holds 89 lane folders.
- **A compaction is a protocol.** A hook marks the seat before it. After it, the seat is reminded to read its reentry note, look at what arrived, and ACK everything at once.
- **Near the end of a window the intensity goes up, not down.** The seat is told it may be making errors it cannot see, it pushes after every artifact, and its successor is armed while it still works.

**▸ Then, modules that carry their own gates.** Since late September 2026 new rules are cut, when the cut allows it, as a small pure module beside the main file, with its own test bench and, since October, its Book. The team cut of 2026-10-31 did not: its rules sit in the main file.

<a name="books"></a>
## 4h · 📚 THE BOOKS — contract, not hard-code *(added for the public copy; measured 2026-11-12)*

The original README says little about these yet: it names the Barrier Book in one rule, and the check-in not at all. The barrier and the check-in follow this pattern: their rules live in small pure modules, and the main file holds the block that reads the data, asks the module and writes what it returns. The team cut of 2026-10-31 keeps its rules in the main file, which keeps growing.

**The rule, signed by Julio on 2026-10-28:** the rules of a feature live in a Book, and no cut sheet is born without its Book.

**Three Books travel inside the brain today:** the Barrier Book, with 20 chapters; the Check-in Book; and the Team Book, for the first technician and the business id. They are written in plain English. The admin shows the Barrier Book and the Check-in Book inside the screens where the owner changes those rules.

**The pattern, in the Barrier Book and the Check-in Book** (the Team Book's rules sit in the main file):
- A small, pure module holds the rules: no database, no network, no clock of its own. It takes dates and returns decisions.
- The brain reads the data, asks that module, and writes exactly what it returns.
- The admin paints the screens and computes nothing.
- The numbers and the switches live in one document the owner edits from the admin (a «god mode»), with a dry run first. A change goes forward only: nothing in the past changes.

**The four promises every change to the barrier must keep** (the Barrier Book, chapter 1):

> **The four promises every change must keep.**
> 1. **What clients see does not change by accident.** Every new piece starts in SHADOW: it computes and logs what it would do, and changes nothing until a switch is turned on by his name.
> 2. **No hard-coded business numbers in new work.** Days, lists and switches live in god-mode documents in Firestore, edited from the admin with a dry-run first.
> 3. **Refuse what stabs.** The Python refuses a rule that would break the system (a knock-out that never arrives, a rule that rewrites the past, an admin typo), instead of accepting it silently.
> 4. **Fail closed.** If anything errors, the client gets exactly what she got before the new piece existed.
>
> — *the Barrier Book, chapter 1, `BARRIER_BOOK.md` :36–40 · as printed here, sha a6771920d814e9d8…*

**A Book is checked against the code, both ways** (the Check-in Book, chapter 0). Book to code: every name the Book cites exists in the code. Code to Book: every route, public function, collection and constant of the feature is named in the Book. The Book lists what its check does NOT cover. And it never tells the live state of production: «Prose about live state is a lie with an expiry date.» These checks are run by hand: the deploy gate does not run them, but it refuses the brain's deploy unless the signed reception receipt records both Books' lints as green. The Barrier Book's lint is known to miss some cases ([4j](#roadmap)).

**The check-in** (October 2026), in the Book's own plain English:

> **Plain English.** Today a client fills a paper form at the studio. The check-in moves that paper to [the artist]'s iPad. Every appointment gets its own check-in, every time, like checking in at a doctor. The client reads the forms, answers, and signs once. [the artist] presses Save. From that moment the check-in is frozen: it keeps the exact forms the client saw and her answers. [the artist] (or Julio) may fix an answer later, but every fix is written in a history with who, when, the old value and the new value.
>
> — *the Check-in Book, chapter 1, `CHECKIN_BOOK.md` :36–36 · as printed here, sha ea128c54d65bae0b…*

**The life of a note, as the barrier's contract computes it** (the Barrier Book, chapter 2, and the contract's own code):

> **Plain English.** Each barrier program (Hard Gel, Pedicure Gel) gives every client one clock. The clock starts at her **anchor** (the last appointment that counts) and its **phase** comes from how many days separate the anchor from the date she wants to book.
>
> — *the Barrier Book, chapter 2, `BARRIER_BOOK.md` :46–46 · as printed here, sha 077a237db9f55076…*

```python
# barrier_contract.py :310–318 — as printed here, sha 6d80db55b9640b67… — the barrier clock alone: every boundary is written with >=
def phase_for_delta(delta_days: int | None, clock: Clock) -> str:
    """TS-2 · The barrier clock alone (no autocall). Same answer as main.py:21703-21710 / :21847-21855 on defaults."""
    if delta_days is None:
        return PHASE_NO_ANCHOR
    if delta_days >= clock.knockout_from_days:
        return PHASE_KNOCKOUT
    if delta_days >= clock.par_days + 1:
        return PHASE_GRACE
    return PHASE_PAR
```

```python
# barrier_contract.py :321–343 — as printed here, sha 8c84b21ab68c719e… — the phase on the requested date, the autocall on TODAY (the function goes on to return the full record)
def evaluate(clock: Clock, *, requested_date: Any, today: Any, anchor: Any) -> dict[str, Any]:
    """
    TS-3 · anchor = the reservation's own effective anchor for requested_date (one rule for everything).
    The clock phase is read on the requested date (strike date = appointment date, doctrine §2); the autocall
    is a calendar event read on TODAY, and once it has landed it wins over the clock phase.
    """
    req = _as_date(requested_date)
    now = _as_date(today)
    anc = _as_date(anchor)
    delta = (req - anc).days if (req is not None and anc is not None) else None
    clock_phase = phase_for_delta(delta, clock)
    autocall_on = None
    autocalled = False
    days_since_anchor_today = None
    if anc is not None:
        on_ord = anc.toordinal() + clock.autocall_days
        autocall_on = date.fromordinal(on_ord) if 1 <= on_ord <= date.max.toordinal() else None
        if now is not None:
            days_since_anchor_today = (now - anc).days
            autocalled = days_since_anchor_today >= clock.autocall_days
    return {
        "program": clock.program,
        "phase": PHASE_AUTOCALLED if autocalled else clock_phase,
```

The phase is read on the date she asks for. The autocall is read on today's date, never on the date she asks for: a client in knock-out cannot book far ahead to skip her recovery service.

**The same life, in the desk's grammar:**

> **The structured-notes view (the doctrine's grammar).** The client is the **counterparty**; the booked service is **the note** (a multi-service is a **multi-leg** note, one clock per leg); booking is the **TRADE date**; the appointment date is the **STRIKE / valuation date** (the barrier is observed only on those dates: discrete monitoring); the anchor is the **fixing** that re-strikes the clock; PAR is the covenant window, then **grace**, then the **knock-out** (the catalog switches to the recovery tranche); the Restoration is the **recovery note** (only COMPLETING it re-anchors); the **autocall** is the dormant reset (the doctrine's P12, «THE [n]+ CLOCK RESET»).
>
> — *the Barrier Book, chapter 2, `BARRIER_BOOK.md` :80–80 · as printed here, sha d4562d032438f53b…*

**Autocall is not matured** (the barrier's contract, October 2026). An autocall is a clock event: the client went dormant, and after a set number of days her clock resets by itself. Matured is the note's natural end: a business fact about her history, which the contract never decides by itself. The contract refuses any god-mode setting with «matur» in its name, so the two words cannot be mixed again.

**The registry of god modes is a generated table, not a page written by hand.** It was harvested on 2026-09-05 and holds 46 entries; when the table first ran that night it measured 16 live, 1 orphan, 3 absent and 26 whose caller it could not parse. For each row the table runs its search again against the files the registry names (the brain and the admin of September 2026) and stamps the measured state next to the declared one. When the two differ, the row goes red. God modes built later, such as the barrier's contract, the check-in and the barrier reminders, are not in the registry.

**Why, in his words:**
- «NOTHING SHOULD BE HARD CODED… ALL MUST HAVE GOD MODE»
- «THE CONTRACT ITSELF SHOULD INCLUDE ALL THE EXPLANATION, CODE WISE, PLAIN ENGLISH, BUSINESS INTENDED…»
- «LITERALLY SEE THIS AS IF YOU GO TO THE DOCTOR, YOU CHECK IN EVERY TIME, WE DO THAT IN STUDIO WITH PAPER, NOW ITS JUST FIELDS AND CODE.»

**▸ Now, toward the multi-tenant.** The monolith is being opened so that more than one business, and more than one technician inside a business, can live in it.

<a name="multitenant"></a>
## 4i · 🏗️ FROM THE MONOLITH TO THE MULTI-TENANT *(added for the public copy; measured 2026-11-12)*

- **Today it is a monolith.** One Python file of about 82.5 thousand lines and 11 modules, behind one HTTP function.
- **The direction (2026-10-22), recorded from a conversation, not yet a design.** The product is the studio's own software, proven in a real business. The booking data needs two dimensions it does not have (the academy already carries a tenant field): the business, and the technician inside each business. First a second technician inside today's brain; then the multi-tenant version. One thing is marked as decided: a single data model for both roads.
- **Said plainly in the lane's own record:** there was no multi-tenant code for bookings, clients, services, calendar, emails or payments. The academy already had a tenant field, which this work declares equal to the studio's business.
- **The pace.** Lane by lane, and each lane adds its gates, its skills and its rules.
- **Where it is (as of 2026-11-12).** The first two cuts went live together on 2026-10-31: cut by one seat, judged by the oracle, the reception signed by Julio, the traffic moved by his hands. The third went live on 2026-11-12: a team module for the admin. The admin now chooses the technician of each appointment, and the owner and her technician each have a calendar lane of their own. Julio published it by hand at his own order, on the cutter's delivery receipt, while the judge's run was still in progress; the judge's verdict came forty minutes later, and the cut was closed.
- **The over-testing loop, and the rule it left (2026-11-12).** The module was first written on 2026-11-08, and its code kept changing with the bench's cures until 2026-11-11: the bench caught real defects in it. In all, seventeen cures went into the bench in four days. Some were functional (arguments the real admin passes, a block of one admin hub); the last two were about what an eye sees at once, nested styles and an element made inert, and a bench with no screen does not paint a page. The cutter and the judge worked for hours alone, one seat at the cap of its mailbox (4e), and nobody asked Julio for direction; he had offered his help and was told it was not needed. He named it the over-testing loop and stopped it on 2026-11-12. His rule, in his words:
  > «Cuando un banco sin pantalla (headless) pase de 3 rondas tratando de medir algo visual/CSS o cuando los asientos lleguen al tope del buzón trabajando en remoto, SE PARA EL BUCLE Y ME PREGUNTAN. Lo visual lo mido yo con mis ojos en 2 minutos o con una captura real (como en la Academia), nunca con 17 corridas de 90 minutos.»<br>*When a bench with no screen (headless) goes past 3 rounds trying to measure something visual or CSS, or when the seats reach the cap of the mailbox working remotely, the loop stops and they ask me. What is visual I measure with my own eyes in 2 minutes, or with a real capture (as in the Academy), never with 17 runs of 90 minutes.*
- **What exists of that rule, and what does not.** The rule is in force since that day and is applied by hand: when a bench on something visual goes past its third round, the seat stops and asks him one question with two options. Prose had not been enough: three earlier rules of the realm already told a seat to stop and ask, and the loop ran all the same. What had stopped an agent before was a guard: on 2026-10-16 an agent removed a guard's own files to unblock itself, and since that day a guard refuses any agent that edits, deletes or moves them, and it states what it cannot see (4d). So this rule is to become code as well. Four detectors are **proposed, and none is installed**: one counts the rounds of a bench on new bytes; one counts the subagents and the lanes a seat opens; one marks a seat that reached its mailbox cap and went on working alone; one watches a long lane with no milestone. Each is designed to warn first and to stop only what repeats, each comes with a guilty control it must condemn and an innocent one it must absolve, and each is installed only under Julio's name, after a stress test by another hand. On the fear that fed the loop, his words: «No importa si hay bugs o glitches, eso yo sé que van a haber. Y para eso lo vamos a mejorar y todo.» (*It does not matter if there are bugs or glitches; I know there will be. And for that we are going to improve it, all of it.*)

**What runs since 2026-10-31,** read from the code and from the deploy's receipts:
- the business never comes from the client: one function decides it, and a second one is the single place where the future layout of the data will be decided;
- a reader of the team registry: until the registry was written, with the next piece (2026-11-12), the team was one person;
- a resolver for the technician, with typed errors: in doubt, nothing is booked;
- a price and a duration for each technician, with no silent fallback;
- every appointment created or edited from the admin is stamped with its business and its technician. Public bookings are not stamped yet, and count as the owner's;
- a technician's calendar check is asked to fail closed by both of its callers;
- her calendar event leaves out the client's contact;
- internal keys are stripped from what a client receives.

```python
# main.py :6047–6070 — as printed here, sha d9e1ff60bcb51d6c… — a calendar that cannot be read is an error, not an empty calendar, when the caller asks to fail closed
def fetch_freebusy_busy_intervals(
    service: Any, calendar_id: str, time_min: datetime, time_max: datetime, fail_closed: bool = False
) -> list[tuple[datetime, datetime]]:
    if not calendar_id:
        if fail_closed:
            raise RuntimeError("freebusy_without_calendar")
        return []
    body = {
        "timeMin": time_min.astimezone(UTC_TZ).isoformat().replace("+00:00", "Z"),
        "timeMax": time_max.astimezone(UTC_TZ).isoformat().replace("+00:00", "Z"),
        "items": [{"id": calendar_id}],
    }
    fb = service.freebusy().query(body=body).execute()
    cals = fb.get("calendars") or {}
    if fail_closed and (calendar_id not in cals or (cals.get(calendar_id) or {}).get("errors")):
        raise RuntimeError("freebusy_calendar_unreadable")
    cal = cals.get(calendar_id, {})
    out: list[tuple[datetime, datetime]] = []
    for b in cal.get("busy", []) or []:
        try:
            out.append((parse_rfc3339(b["start"]), parse_rfc3339(b["end"])))
        except Exception:
            continue
    return out
```

One honest gap in that excerpt: a busy entry that cannot be parsed is still skipped, so that time reads as free.

**How it went live.** The deploy gate refused the first attempt: the signed reception was missing. Two runs then passed every gate with no traffic. Julio moved the traffic. A live probe passed, with a case the check must condemn and a case it must find.

**What the owner saw after 2026-10-31:** nothing new. The admin did not call the new routes or send a technician; its create and edit calls already stamped the default business and the owner. Since 2026-11-12 it reads the team and sends the technician (above).

<a name="roadmap"></a>
## 4j · 🧭 WHAT EXISTS, WHAT IS PARTIAL, WHAT IS MISSING *(added for the public copy; measured 2026-11-12)*

| Item | State |
|---|---|
| The mailbox between agents, enforced in code | exists |
| The deploy gate, with receipts and rollback | exists |
| The guards of identity, commit, pointers, deploy and of the guards themselves | exist |
| The cut sheet and the delivery receipt, checked by the deploy gate | exist |
| The stress-test rule | written down and in use; its own file is still marked provisional. The deploy's own gates are pinned to the bytes that were stress-tested. **For a new guard or skill, no gate requires that test before the install**; the rule says so itself |
| The Forge standard | raised to a law of the realm by Julio's own voice on 2026-08-08, and a posture. **No gate enforces it at deploy.** A linter for silent refusals exists and is run by hand |
| The Barrier Book's lint as a deploy gate | tried and not installed: it failed two rounds of stress test. It is run by hand, and the gate reads its result from the reception receipt |
| The public pages and the admin | they are still published by hand, outside the deploy gate |
| A staging environment | none. A tagged revision with no traffic stands in for it (4f) |
| A brake on the context window | removed on 2026-10-30; no replacement in code |
| The daily log and the council's record | they fell behind in late October while the lanes kept working; being looked at |
| Finding things | on 2026-10-01 the realm wrote down that finding things across the lanes, and remembering how they were done, costs time every day. The cure is a lane of its own, Back to Basics |
| The multi-tenant | three cuts live: two on 2026-10-31 and the team module on 2026-11-12. A second business is not built |
| A cap on test rounds | Julio's rule of 2026-11-12 (4i), applied by hand. Four detectors are proposed and **none is installed** |
| The admin in modules | a direction from Julio's voice of 2026-11-12, not yet a design: break the admin into pieces that only call the backend |
| The Finance Lab's first prototype | outdated, by Julio's own ruling |
| The god-mode registry | harvested on 2026-09-05. What was built after that day, like the barrier's contract and the check-in, is not in it yet |
| The Lifecycle Lab's own gates | not finished, by Julio's own account (2026-11-12) |
| The Lab's next layer: desks, programs, product managers and their reps, with the notional of a shared note sliced into positions | planned in a note of 2026-07-18 and not built: it waits for his GO |
| The calendar project of his first spreadsheet | not all of it is in the code, by his own account |
| Writing the code himself | Julio's own gap, said by him: he is not a software engineer. He approves the build, and learning to write it is on his own list |

# PART TWO · THE STRUCTURED NOTES *(the second pillar: the model the code runs on, and the trade it came from)*

*In this part, «brain :N» is a line of the brain of 2026-07-30. Elsewhere, «main.py :N» is a line of the brain of 2026-10-31.*

**▸ How the model was born** (told by Julio on 2026-11-12). He was modelling the studio's appointments in a spreadsheet when the studio raised its prices. Clients began to stretch the time between visits, and some asked for a repair in between so that the next visit could wait longer. In his words: «me di cuenta que el repair era un credit event» (in English: I realized that the repair was a credit event), and «Por eso entonces empecé a ver los clientes como notas estructuradas» (in English: that is why I began to see the clients as structured notes). He began to rate them the way a desk rates bonds, and the code came after.

<a name="issuer"></a>

## 0 · ⚜️ THE ISSUER MODEL — the main logic everything runs around

> ### 📜 MEMO — THE TRUE UNDERLIER & THE INSTITUTIONAL MAPPING
> **Timestamp:** 2026-07-31 · **Author:** THE IMPERATOR · **Status:** ⚖️ **RATIFIED DOCTRINE**
>
> **1 · THE FINITE ASSET (THE TRUE UNDERLIER).** Beneath the covenants, the worst-of pricing logic, and the
> counterparty ratings, the absolute foundational asset of this desk is **[the artist]'s Time, Physical Capacity, and Studio
> Overhead.** Time cannot be printed, and physical execution capacity is strictly finite. The entire purpose of the
> barrier engine and the Finance Lab is to **protect, perfectly price, and maximize the yield on this finite asset**
> while hedging against business expenses.
>
> **2 · THE STRUCTURED NOTE MECHANISM.** We map studio services as Structured Notes and clients as Counterparties
> because institutional derivatives logic perfectly matches the reality of the transaction. Selling a block of a
> master artist's time is inherently exposed to behavioral volatility (reschedules, cancellations, budget decay).
> The Wall Street architecture — WOF (Worst-Of) barriers, PAR/Grace windows, Knock-Out catalogs, and MTM tracking —
> is the exact mathematical mechanism required to defend the asset from that volatility. **The structured mapping is
> not a metaphor; it is the defensive shield protecting the Empress's chair.**
>
> **3 · THE MULTI-TENANT VISION.** Framing the business as an institutional trading desk empowers a much larger
> vision. By abstracting time and scheduling into financial instruments, we decouple the software from a simple
> “salon calendar” and elevate it into a **FinTech-grade Studio Operations Engine.** What protects [the artist]'s time today
> serves as the validated, million-dollar blueprint for the **multi-tenant SaaS architecture of tomorrow** — allowing
> future Academy graduates to protect their own time using the exact same quantitative discipline.
>
> *[editor's line for this copy: the memo is a vision dated 2026-07-31. Nothing in this repository puts a value on it, and the multi-tenant is told as it stands in 4i. On the studio's side this grammar names day-count rules, ratings and labels; the pricing of notes lives in 0c]*

> ### *"Every business is a derivative. **EVERY HUMAN IS A COMPLEX EXOTIC DERIVATIVE OPTION, BESPOKE, OTC** — that's why so many factors are included, just like a structured note."* — the Imperator

**[the studio] is the ISSUER. Every client is a COUNTERPARTY buying structured notes** (booked services) —
the same structure issued to everyone, personalized by behavior. This is not decoration: the owner worked with structured
notes professionally, and the engine speaks that market's public grammar (the terms of its 424B2 filings). The full doctrine is in
[path]/STRUCTURED_NOTES_DOCTRINE.md.

| Term | In this realm | 🏦 On the real desk — the same instrument in 424B2 terms |
|---|---|---|
| **The note** | one booked service structure; multi-service = **multi-leg**, each leg on its own clock | one security = *“a funding instrument (a bond) plus a derivative package”* — the engine’s own primer (brain `:38115`). Multi-leg = two notes traded the same day, each on its own observation grid |
| **The underliers (worst-of pair)** | ① nail time-decay (finger/toe) ② **price capacity/budget** — a breach can come from either | a **worst-of basket** — R = min(Sᵢ/S0ᵢ). The holder is **SHORT a worst-of down-and-in put**, which is WHY they are **LONG correlation** (GO#12, brain `:37807`) |
| **TRADE date** | the day the client **books** | the trade/pricing date of the 424B2 — a real desk usually strikes the SAME day; splitting trade from strike is the realm’s own twist |
| **STRIKE / VALUATION date** | the **appointment date** — [the artist] assesses, the note strikes, the clock re-anchors. Valuation runs on the calendar **whether or not they book** | the **initial fixing S0** + the observation grid — **discrete monitoring on observation dates only**, never continuous (the frozen-contract lock) |
| **Coupon / principal** | completing the appointment | the **contingent coupon** — paid iff the worst-of ≥ the coupon barrier on the observation date (Phoenix); principal redeemed at maturity |
| **ALPHA** | **tips — basically only tips** | **no 424B2 equivalent** — a note pays only what its terms say, and on a desk alpha means return above a benchmark; here it is income the issuer receives beside the contracted price |
| **MTM** | the visit's mark (add-ons/designs ride here); **overall MTM = the average of all visit MTMs** | the **fair-value MODEL MARK** as % of par; the book = `[route]`, a time series where every mark is stamped with its vol source and its three clocks |
| **Barriers / knock-out** | HG: PAR [n]d · grace [n] · KO [n]+ · Pedi: PAR [n] · grace [n] · KO [n]+ — breach swaps the catalog to **recovery tranches** at their own prices | the **coupon barrier + principal (knock-in) barrier** — below the coupon barrier, that period's coupon is not paid (a memory note pays it later if the worst-of is back above the coupon barrier); below the principal barrier at maturity, the short worst-of put **KNOCKS IN**: *“this is where the loss lives”* (GO#12). The recovery tranche = the restructured re-issue at its own price. **Real anchor:** CITI `17332VPH1` — the 70% European knock-in |
| **The re-strike** | only when the recovery note is **COMPLETED** | a new note fixes its own S0 on its **strike date** |
| **MATURITY** | booking *[a plain service]* (the [client] case) = the note **ended cleanly**; clock erased; returns fresh. **Not** an autocall, not a default | **MATURED_PAR** — natural redemption at par, one of the nine lifecycle states (brain `:35709`). Not CALLED, not a default |
| **Credit event** | a repair **or repair request**; honest repairs exist; repair + complaint = **yellow card = note defaulting** | the nearest is an OTC counterparty's **event of default** (failure to perform); in a funded 424B2 note only the issuer can default |
| *[three rows removed from the public copy]* | | |
| **ISSUER CALL** | the Imperator proactively ends an unsustainable note — **removal from the existing-clients portal, and/or ban** (the Relationship Management lane) | **Family C — the SHORT Bermudan call held by the ISSUER**: *“their button, their timing”* (brain `:37836`) — the leg the engine refuses to fake with a fixed call rule |
| **AUTOCALL** | time does it — ~[n]+ days lapsed = matured/auto-called out of the EC book; the brain already routes returners to the new-clients door. **PENDING LANE: the [n]+ clock reset** — lapsed returners will get their clocks reset as part of the Relationship Management lanes *(to implement)* *[editor's line for this copy: since October 2026 the autocall lives in the barrier's contract, behind its own switch, and it is not “matured”: see 4h]* | **automatic early redemption** — worst-of ≥ the autocall level on an observation date → CALLED; one `return` truncates BOTH the coupon strip and the put exposure (`mc_phoenix.hpp`). **Real anchors:** Phoenix autocall at 90% (CITI) · the GS one-look $1,100 |
| **THE EXTENSIONS LADDER** | its own program with a graduation path: **extensions → corrections (~[n] weeks, repeated) → hard gel** (when the admin marks it) — the graduate's HG clock anchors on the graduation appointment, never on stale history | a **roll program** — completing one instrument qualifies the counterparty for the next issuance; the new clock anchors on the roll date, never on stale history |
| **MULTI-SERVICE MAPPING** | the read-model that decomposes a multi SKU into its **legs** — *"to identify which underliers are running."* Each leg keeps its own clock, valuation date and knock-out; legs never collapse (worst-of). Knocked-out combos show the **right combination**: [three combinations of services] | **basket decomposition** — naming which underliers are running, leg by leg; GO#12 does the same job on real paper |
| **THE CLOCK-RESET SERVICES** | **[three plain services]** reset the clocks — the client *"enters a service they can keep without returning or being on a clock."* No lifting economics → no covenant → no barrier | exit to a **spot product** — no derivative attached: no covenant, no observation grid, no barrier |
| **THE BOOKING BRIDGE** | a knocked-out/breached client's path back in — the anchor is the **latest HG visit, completed OR upcoming**, so booking the recovery note re-opens the catalog. *[one sentence removed from the public copy]* Only COMPLETION re-strikes | the **restructuring window** — an agreed recovery re-opens the trading line; only the new note's strike fixes a new S0. |
| **BOOKED ≠ COMPLETED** | booking ahead earns nothing by itself — **valuation runs on the calendar regardless**, and an upcoming appointment is **pipeline only**: excluded from realized revenue, Visit MTM, MTM average and alpha until completed. | **no desk equivalent** — pipeline is never P&L, while a booked trade counts in P&L from its trade date (the studio, unlike a desk, counts revenue only on delivery); the observation calendar runs regardless of open orders |
| **STUDIO EXEMPTION (F.1–F.4)** | **studio fault ≠ client fault.** When the studio caused the gap (closed dates, rescheduled by us), a granted exemption relieves the breach — booking mercy (F.3) + surveillance mercy (F.4). Real instruments live in the vault ([a count of exemptions], found field-for-field vs the design doc). **A rating must never punish a counterparty for the issuer's own operational failure** | the **issuer-fault carve-out** — a missed observation caused by the issuer’s own operational failure can never default the counterparty; granted per instrument, recorded in the vault |
| **VOLATILITY** | measured on the **calendar**: client cancels · reschedules · **EDITS an appointment** · **drops services** — each one seizes-then-releases a slot, *"taking away spots of good actual clients the business can rely on."* Studio-fault never adds vol. Only `fault=client` events count (the V3 attribution loop). Case study: [client] | **realized σ** — close-to-close log returns, annualized √252 (brain `:36697`); cancels/reschedules ARE realized vol on the issuer’s capacity book. Higher σ → worse worst-of odds → a costlier note |
| **The issuer's true measure** | *"not alpha or MTM — **consistency of the maintenance.** Everyone within barriers, no bad behaviors. Simple as that."* | the desk’s true risk metric — **staying within barriers**: a clean record outranks a hot mark |

<details>
<summary><b>▶ EXPAND — the code behind the covenant (byte-exact from the brain of 2026-07-30)</b></summary>

```python
# brain :42999–43002 — the Hard Gel covenant, as constants
_FINANCE_LAB_HG_PAR_MAX_DAYS = [n]
_FINANCE_LAB_HG_GRACE_MAX_DAYS = [n]
_FINANCE_LAB_HG_KNOCKOUT_FROM_DAYS = [n]
_FINANCE_LAB_HG_WARNING_LEAD_DAYS = [n]
```
```python
# brain :42661–42664 — the structure profile stamped on a CLIENT
        profile = {
            "structure_type": s_type,
            "underliers": ["price_capacity", "nail_health"],
            "basket": "worst_of",
```
*A human being carries two underliers and settles worst-of. PAR [n] · grace [n] · KO [n] · [n]-day warning lead.* *[editor's line for this copy: the code stamps the two underliers and the worst-of basket as a label on the client; no code that combines the two was found]*
</details>

<details>
<summary><b>▶ EXPAND — the code behind the studio exemption (mercy outranks alarm)</b></summary>

```python
# brain :43300–43308 — the FL live-warning clock: protection checked BEFORE punishment
    live = False
    reason = ""

    if service_family in ("not_hg_client", "pedicure_only"):
        reason = "Not HG client — separate asset class"
    elif live_anchor is None or days_since is None:
        reason = "Missing live HG clock anchor"
    elif studio_fault_protected:
        reason = "Studio-fault gap protected (F.4) — not client-punishable live warning"
```
*The engine refuses to raise a live warning on a client the studio itself delayed.*
</details>

<details>
<summary><b>▶ EXPAND — the code behind "products feed ALPHA" (P8, settled by the code's own docstring)</b></summary>

```python
# brain :3384
    """Journey retail lane → product cents (alpha path, not MTM/design)."""
```
*And MTM average, in the SHOW MATH payload's own words (brain :31917): "Simple average of Visit MTM ratios on completed unique visits."*
</details>

*(One expandable block was removed from the public copy here: it walked one admin action end to end, through the sign-in, the route and the database. The rule it proved stays: a feature is never one file, and every change names the layers it touches before it is cut.)*


> **This expandable pattern is the model for the whole mapping** — every doctrine row can carry a ▶ toggle opening the
> byte-exact code that implements it, taken from a dated brain (here, the brain of 2026-07-30). The full per-term expansion is a
> pending lane (the H1 deep mapping, held for the Imperator's GO).

**THE WHY (his words):** a [n]-week client costs **[n] hours**; a stretcher or knock-out costs **[n] hours plus
the next [n] appointments at [n]h instead of [n]h** — the restoration's +$[n] never covers it. A breach ruins **the
foundation [the artist] set**, makes her work double, and burns her out. And volatility (cancels · reschedules · edits ·
dropped services) is measured on the **calendar**: every vol event *"takes away spots of good actual clients the
business can rely on."* **The barrier engine is a time-and-burnout hedge protecting the asset, the schedule, and the
Empress** — not a $[n] reprice. *(Alpha is NOT final — behavioral alpha is a queued design: on-time/never-breached
clients earning alpha after X appointments.)*

**Even inventory runs on this** — retail purchases feed the buyer's alpha, never her mark. The five surfaces (section 1) are the machine that executes this model.

<a name="case"></a>
## 0.1 · 📖 THE STUDIO BOOK — one rule that a case carved *(cut for the public copy)*

The original holds the live book here; it stays private. So does the case itself: nothing of the client is in this copy. What stays is the rule the case carved, because it shows why the barrier exists.

#### ⏳ THE CASCADING TIME DEBT
**The engine had already written the rule as a comment months earlier:**

```python
# brain :12426–12427 — the knock-out catalog hides the long service, and says WHY
# Always hidden on knockout (includes [a multi-service] — too long when HG maintenance lapsed).
HARD_GEL_KNOCKOUT_ALWAYS_HIDDEN_IDS: frozenset[str] = frozenset({"[id]"})
```

> ### **A barrier breach is not a one-time fee. It is STRUCTURAL DAMAGE that creates a TIME DEBT the issuer keeps paying on future visits — even after the client's gaps look healthy again.**

Three of the four rules the case carved, from the full case study in the private repository (the fourth is not in this copy):
- **A breach is a debt, not a fine.** The penalty is paid once; the damage is paid down over the following appointments.
- **A compliant gap does not mean a healed foundation.** Current state and structural state are different measurements.
- **A second restoration is not a double charge.** It is the second instalment on the same debt.

<a name="portals"></a>
## 0.2 · 🚪 WHERE IT HAPPENS — the client's portal is the market *(added for the public copy; measured 2026-11-12)*

The model is not a report. It acts in one place: the client's portal. In Julio's words (2026-11-12):

> «Eso es como un Bloomberg, ese es el mercado»<br>*That is like a Bloomberg: that is the market.*
>
> «Ahí es donde entra el cliente y el Python sabe quién es y dónde está la barrera y cuál es el servicio»<br>*That is where the client comes in, and the Python knows who she is, where the barrier is and which service it is.*

What the barrier is for, in the Barrier Book's own plain English:

> **Plain English.** A nail service like hard gel only stays healthy if the client comes back on time. The barrier is the rule that says: «you are on time, you are a bit late (grace), or you waited too long (knock-out) and now you need a recovery service first». It protects the client's nails, the artist's work and the studio's calendar. It decides what each client SEES and CAN BOOK in the portal, so a wrong number here changes real bookings.
>
> — *the Barrier Book, chapter 1, `BARRIER_BOOK.md` :34–34 · as printed here, sha 995296198cfce117…*

**Three doors lead in** (the Barrier Book, chapter 8): a small booking frame and a profile in the portal for new clients, and the existing-clients portal.

**For an existing client the catalog is built in order:** the services of existing clients; her Hard Gel clock and its knock-out filter; her pedicure clock and its filter; the multi-service gate; the extensions ladder; and the banner that tells her where she stands. Every step after the first runs only behind the barrier's switches, and every switch ships off in code; which ones are on is live state, and it is not written here.

And she can book ahead, because the brain reads her calendar as it will be on the day she asks for:

> **Plain English.** When a client asks for a date, the brain looks at her calendar AS IT WILL BE on that date: the last barrier appointment she has on the books before (or on) that date is her anchor, even if it has not happened yet. […]
>
> — *the Barrier Book, chapter 8, `BARRIER_BOOK.md` :294–294 · as printed here, sha c140d8dd1d39db3f…*

In her portal she books with a card on file (only some services take a deposit), and she sees the photos the studio adds to her visits.

<a name="forge"></a>

## 0c · ⚒️ THE OTHER DESK IN FULL — the Lifecycle Lab & the C++ Monte-Carlo forge

*[A status banner was removed here. In the private original, this section, the third column of section 0 and section 0.1 are marked as a test cut that Julio has not approved as design; publishing this copy does not approve it.]*

> ### *“The C++ pricer took about two days because the Python already spoke this grammar — barriers, grace windows, knock-outs and MTM existed as production code for a real book before a single 424B2 was parsed. The pricer was a translation, not an invention.”* — the PRICE ENGINE panel, brain `:38105–38107`

**What it is:** a working structured-notes desk. **Seven real SEC-registered notes from four real issuers**
(Citi · Goldman Sachs · HSBC · J.P. Morgan), each with its real CUSIP and its actual 424B2 pricing-supplement PDF
on disk (`[folder]/`). A **C++ Monte-Carlo engine prices six of them on the Imperator’s own PC**
(bound to a loopback port; the seventh note, of Family C, it refuses by design: 0c.4); the Python brain assembles every input and authors every
explanatory sentence; the admin renders and computes nothing. **Two desks, one vocabulary, zero shared state** —
the isolation law is carved above the lane’s first function (expand below), and **the C++ engine never deploys: it runs on a local machine. The lab's Python routes travel dark inside the brain, behind a flag that ships off.** Full map, every block byte-exact: [path]/LIFECYCLE_AND_FORGE_MAP.md.

### 0c.1 · The four families — and what you are actually LONG and SHORT

The engine does not just price a note — its SHOW MATH panel **decomposes every family into option legs** (GO#12,
brain `:37799–37867`, investor’s side), the same reading a real desk would do:

| Family | The note | The option legs (from the engine’s own SHOW MATH) |
|---|---|---|
| **A · Phoenix** (contingent income autocall) | coupon iff the worst underlier ≥ coupon barrier; auto-called at or above its autocall level (90% on the Citi note below); principal knocked in below the barrier at maturity; optional **memory** | **LONG** zero-coupon-style bond · **SHORT** worst-of down-and-in put (*“this is where the loss lives”*) · **LONG** strip of contingent digitals (+memory catch-up) · autocall **truncates BOTH** the coupon strip and the put exposure |
| **B · Autocall + upside** | zero coupon; one call look pays a fixed premium; at maturity, participation on the upside | **LONG** bond · **LONG** upside participation call (GS-SPX: **1.35×**) · **SHORT** down-and-in put (below the trigger, a 1:1 loss from the initial level) · fixed-premium autocall look |
| **C · Issuer-callable** | principal-protected + leveraged participation — but the **issuer** holds the call | **LONG** principal-protected bond · **LONG** participation call · **SHORT Bermudan call TO THE ISSUER** — *“their button, their timing”* — **THE LEG THAT MAKES THE ENGINE REFUSE** (honest pricing needs LSMC; a fixed call rule would mis-mark the leg you are short) |
| **D · Dual-directional** | up → leveraged gain; **down a little → you get PAID the absolute value** (capped); down a lot → 1:1 loss | **LONG** bond · **LONG** upside call · **LONG** absolute-return put inside the barrier (mild falls PAY — capped since GO#8) · **SHORT** put below the barrier or the buffer (on the barrier note, a down-and-in put with a 1:1 loss from the initial level; on the buffered note, a put struck at the buffer, with a 1:1 loss beyond it) |

And the same decomposition speaks **three registers** (GO#11 — `finance` / `code` / `kid`), authored in Python,
rendered by the admin. The kid register on Phoenix, verbatim from the brain: *“You lent money and sold insurance on
the clumsiest of three friends. Most months they are fine, so you collect little payments. If the clumsiest one has a
really bad fall, you pay for it. If they are all doing great, the game just ends early and you get your money back.”*

### 0c.2 · Real paper, worked examples — so the table above connects to real notes

| Real note (424B2 PDF on disk) | CUSIP | Family | What it proves |
|---|---|---|---|
| **Citi** worst-of INDU·NDX·RTY contingent-coupon autocall, 2031 | `17332VPH1` | A_phoenix | the forge marked it **0.942281** (100k antithetic paths, stderr 5.8e-4) vs **Citi’s own disclosed estimated value 0.9496** → **−73 bps against it.** P(worst@T) came out RUT 57% · NDX 32% · DJI 11% — exactly the ordering of the vols used. |
| **Goldman Sachs** SPX autocall + upside, 2029 | `40054XHK7` | B_autocall_upside | the **1.35× participation leg** — the engine **refuses to price the note when that rate is missing** rather than default it to 1.0 and silently price away the leverage. Marked **0.941953** vs GS’s disclosed **0.9540** (LIVE note) |
| **HSBC** META·QCOM contingent income **with memory**, 2027 | `40447BMF6` | A_phoenix + memory | the lifecycle: the tape detected the autocall, but **Yahoo pedagogy can NEVER seal a settlement fact** — on the Imperator's GO, LIVE→CALLED was recorded once as a **DESK RULING**, a grade of its own that is never sealed, and the registry records the evidence that WOULD seal it. Aggregate face amount **$4,943,000**, 424B2 Reg 333-277211 |

**The value stack** (the Goldman Sachs note of example 2) — the two gaps a [role] would check first, **never blended**:

```
 100.00   price to public (par)
  −2.92   underwriting discount              ← DISCLOSED in the 424B2 (GS: 0.02918)
  −~1.68  hedging + issuer funding advantage + dealer profit
 ───────
  95.40   THE ISSUER’S OWN ESTIMATED VALUE   ← the bank’s published model number, AT PRICING
  −1.20   our mark (07-27) vs theirs (07-15) ← model inputs AND twelve days of market
 ───────
  94.20   OUR MODEL MARK
```

**The upper gap is fees. The lower gap is model and market, measured on two different dates — never a fee.** Calling the second one a fee is the error the engine’s
own labels now make impossible (brain `:37518–37525`).

> ⚠️ **On the Citi note (example 1): discipline on its 73 bps, as it was filed, less one sentence:** one note, one date, flat-vol GBM — not a calibration
> suite. *[editor's line for this copy: the forge's run of 2026-07-18 used spot at the initial levels of the 2026-04-27 pricing, flat vols of 16%, 22% and 25% set in the request, flat correlations of 0.70 to 0.75, a flat 4.25% rate, 100,000 antithetic paths and seed 7. Citi's figure is its own estimate on the pricing date, made with its own models and its internal funding rate]* *[one sentence removed in this copy: see the corrections at the end]* And it is the estimated value **at pricing** — never *“Citi’s MTM today.”*

### 0c.2b · Two notes from the Lifecycle, SHOW MATH in full — financial · coding · simple

**The engine explains every note in three voices** — authored in Python, rendered by the admin (GO#11/GO#12).
Here are two REAL notes from the lab's own store, each with its terms from its own JSON and the three voices
**rendered exactly as the panel renders them, from the code expanded below + the note's own terms.**

#### 📘 Example 1 — `CITI-WO-INDU-NDX-RTY-17332VPH1-2031` (Family A · Phoenix · worst-of · priced 2026-04-27)

**The note's own payoff summary** (from `[path]/CITI-WO-INDU-NDX-RTY-17332VPH1-2031.json`):
> *“Citi 5y worst-of INDU/NDX/RTY autocallable contingent coupon. Monthly: if worst >= 75% → coupon (>=7.40% p.a.);
> else $0 (no memory). After year 1, monthly: if worst >= 90% → redeem par + coupon. At maturity if not called:
> worst >= 70% → par; else 1:1 loss from initial on worst (European). No upside participation beyond coupons.”*

| Voice | What the panel says (with THIS note's terms: KI 70% · coupon 7.4% p.a. at 75% · autocall 90%) |
|---|---|
| **💰 FINANCE** | *“Phoenix contingent income: long the bond, SHORT a worst-of down-and-in put (KI 70%), long a strip of contingent digitals (7.4% p.a. at 75%), autocall at 90%. Being SHORT the worst-of put is WHY the holder is LONG correlation: a worst-of put is worth more when correlation is low, so you want the basket to move together. The Greeks follow from the legs.”* |
| **💻 CODE** | *“Each leg is a branch that already executes in mc_phoenix.hpp: hit_autocall() -> early return; hit_coupon() -> accrue (+memory counter); hit_principal_ki() at maturity -> R/strike. This decomposition is a READING of the payoff code, not a second model.”* |
| **🧒 SIMPLE** | *“You lent money and sold insurance on the clumsiest of three friends. Most months they are fine, so you collect little payments. If the clumsiest one has a really bad fall, you pay for it. If they are all doing great, the game just ends early and you get your money back.”* |

**And the mark:** the forge priced this exact note at **0.942281** (100k antithetic paths) vs **Citi's own disclosed
0.9496** → **−73 bps** against the issuer's estimated value at pricing.

<details>
<summary><b>▶ EXPAND — the Family-A voice builder, byte-exact (brain :37799–37814, the brain of 2026-07-30)</b></summary>

```python
# brain :37799–37814 — GO#12 — the Phoenix legs + the three voices, as the code authors them
        legs = [
            {"position": "LONG", "instrument": "zero-coupon-style bond", "detail": "par redemption at maturity if no knock-in"},
            {"position": "SHORT", "instrument": "worst-of down-and-in put", "detail": f"struck at initial, KI at {pb} on the WORST underlier \u2014 this is where the loss lives"},
            {"position": "LONG", "instrument": "strip of contingent digitals", "detail": f"coupon {cpn_s} pays iff worst \u2265 {cb}" + (" \u00b7 WITH MEMORY (missed coupons catch up)" if mem else "")},
            {"position": "\u2014", "instrument": f"automatic autocall at {ac}", "detail": "early redemption truncates BOTH the coupon strip and the put exposure"},
        ]
        fin = (f"Phoenix contingent income: long the bond, SHORT a worst-of down-and-in put (KI {pb}), "
               f"long a strip of contingent digitals ({cpn_s} at {cb}), autocall at {ac}. "
               "Being SHORT the worst-of put is WHY the holder is LONG correlation: a worst-of put is worth more "
               "when correlation is low, so you want the basket to move together. The Greeks follow from the legs.")
        code = ("Each leg is a branch that already executes in mc_phoenix.hpp: hit_autocall() -> early return; "
                "hit_coupon() -> accrue (+memory counter); hit_principal_ki() at maturity -> R/strike. "
                "This decomposition is a READING of the payoff code, not a second model.")
        kid = ("You lent money and sold insurance on the clumsiest of three friends. Most months they are fine, "
               "so you collect little payments. If the clumsiest one has a really bad fall, you pay for it. "
               "If they are all doing great, the game just ends early and you get your money back.")
```
</details>

#### 📗 Example 2 — `GS-SPX-40054XHK7-2029` (Family B · autocall + upside · **LIVE** · aggregate face amount $851,000)

**The note's own payoff summary** (from `[path]/GS-SPX-40054XHK7-2029.json`):
> *“No coupons. One autocall look 2027-09-28: SPX close >= 7572.40 -> $1,100 (10% premium) and done. Else hold to
> 2029-06-27: above initial -> par + 135% of gain; between 80% and 100% of initial -> par; below 80% (European) ->
> par + return (1:1 loss from initial). Client is short the 80% European put and short the call that truncates the
> 135% leg.”*

| Voice | What the panel says (with THIS note's terms: participation 1.35× · KI 80% · one call look, 10% premium) |
|---|---|
| **💰 FINANCE** | *“Autocall + upside: long bond, long a 1.35x participation call at maturity if not called, short a down-and-in put below 80%, plus a fixed-premium autocall. The participation leg is why this family refuses to price when the participation rate is missing.”* |
| **💻 CODE** | *“mc_autocall_upside.hpp: call premium branch on the observation date; participation leg at maturity; KI put branch below the trigger. Refuses if upside_participation_rate or call_premium_pct are null.”* |
| **🧒 SIMPLE** | *“Same loan, but if the market grows you get the growth times 1.35x. On one check-day, if it is up at all, the game ends and you get your money plus a bonus.”* |

**And the mark:** the forge priced it **0.941953** vs **GS's disclosed 0.9540** (underwriting discount 2.918%
disclosed in the same 424B2) — and this is the note whose missing participation rate the engine **refuses** to
default to 1.0.

<details>
<summary><b>▶ EXPAND — the Family-B voice builder, byte-exact (brain :37815–37831, the brain of 2026-07-30)</b></summary>

```python
# brain :37815–37831 — GO#12 — the autocall+upside legs + the three voices, as the code authors them
    elif fam.startswith("B"):
        upr = _g("upside_participation_rate")
        upr_s = f"{float(upr):.2f}x" if isinstance(upr, (int, float)) else "\u2014"
        pb = _pct(_g("principal_barrier_pct"))
        legs = [
            {"position": "LONG", "instrument": "bond", "detail": "par at maturity above the trigger"},
            {"position": "LONG", "instrument": f"upside participation call ({upr_s})", "detail": "at maturity if not called"},
            {"position": "SHORT", "instrument": "down-and-in put", "detail": f"below {pb} \u2014 1:1 loss beyond the trigger"},
            {"position": "\u2014", "instrument": "autocall observation(s)", "detail": "fixed premium if at/above initial on the call date"},
        ]
        fin = (f"Autocall + upside: long bond, long a {upr_s} participation call at maturity if not called, "
               f"short a down-and-in put below {pb}, plus a fixed-premium autocall. "
               "The participation leg is why this family refuses to price when the participation rate is missing.")
        code = ("mc_autocall_upside.hpp: call premium branch on the observation date; participation leg at maturity; "
                "KI put branch below the trigger. Refuses if upside_participation_rate or call_premium_pct are null.")
        kid = ("Same loan, but if the market grows you get the growth times "
               f"{upr_s}. On one check-day, if it is up at all, the game ends and you get your money plus a bonus.")
```
</details>

### 0c.3 · The Monte Carlo, precisely

- **Per path, per observation date** (`mc_phoenix.hpp:156–212`): every underlier evolves under correlated GBM —
  `Sₖ ×= exp((r − qₖ − ½σₖ²)·dt + σₖ·√dt·Zₖ)` — the worst-of is `R = minᵢ(Sᵢ/S0ᵢ)`, discounting at `e^(−r·t)`,
  and the branches run in the order the frozen contract **locked**: call window → autocall → coupon → (last) principal.
- **Variance reduction:** antithetic pairs (Z, −Z), and the standard error is computed on **pair means**
  (`mc_phoenix.hpp:284–298`), the statistically correct estimator. ~100,000 paths, fixed seed → reproducible marks.
- **Correlation is gated, never repaired:** a non-positive-semi-definite matrix has no Cholesky factor and describes no
  real joint distribution — **the forge throws instead of nudging eigenvalues** (expand below).
- **Vols carry their source on every mark**, resolved on a five-step ladder — `request → note → realized_30d_tape →
  model_default → pedagogy` — realized σ = close-to-close log returns × √252 (brain `:36697`). *“NOT implied — a
  real vol surface needs an options feed. We will not claim a surface we do not have”* (`:37925`). Switching the CITI
  note from hand-set to realized tape moved the mark **~196 bps at identical spots — measured, not asserted** (`:38027`).
- **The treaty between the two languages** — the frozen JSON contract (1.1.0, worst-of extension): boundaries `>=`
  inclusive · European knock-in at maturity · **discrete monitoring on the observation grid only** · 30/360 ·
  *“Python never computes a mark; C++ never touches a database”* (`:37998`). Both sides implement the same three
  boundary predicates — the Python mirrors cite the C++ functions by name.
- **Three clocks, never conflated** (`:36548–36563`): `priced_at` = the **server** clock when the mark is accepted
  (never the browser’s) · `market_data_as_of` = the **OLDEST** quote across the basket (*“a mark is only as fresh as
  its stalest leg”*) · `issuer_ev_as_of` = the 424B2 pricing date, forever. The cross-clock alarm (`:37613`) refuses to
  let +bps read as *“beats the issuer”* across different clocks.
- **The lifecycle is a state machine over real histories** (`:38701–`): nine states (`DRAFT → PRELIMINARY → ISSUED →
  LIVE → CALLED / MATURED_PAR / MATURED_KI / MATURED_UPSIDE / CANCELLED`), replayed observation by observation — the
  Python mirrors `mc_phoenix`’s branch order **by citation written in the source**, and it models **coupon
  EVAPORATION**: land in the gap zone at maturity and the entire unpaid memory stock dies, named and counted.

### 0c.4 · What the engine REFUSES to do — the product

**Fourteen distinct, coded, non-silent refusals** across three languages (the full ladder: map §7). The spine:

| Refusal | The law it enforces |
|---|---|
| `missing_initial_levels` | **S0 is the denominator of every barrier test. No S0, no mark** — and no silent S0=spot |
| `tape_unavailable` / `missing_closes` | *“refuse — never invent closes”*; a dead quote must not become a stale mark |
| `WAITING_ON_FIXING_DATE` | a future strike date returns a **calendar, never a level** — *“PRELIMINARY stays PRELIMINARY”* |
| `fair_value_mark_out_of_band` | a mark outside 1–300% of par is a bug, not a valuation |
| **`SEAL_REQUIRED_BEFORE_BOOK_STAMP`** | **a pedagogy price feed may never write a settlement fact** — and the dry run still shows the full proposed patch: *the engine refuses the write without refusing the knowledge* |
| **`unsupported_family_detail`** (Family C) | a leg the model cannot honestly price **is not priced** — the refusal is the correct price of honesty on the short-Bermudan leg |

> 👑 *“Sometimes the computer says I DO NOT KNOW — and that is its best feature. A calculator that always answers,
> even when it should not, is the dangerous one.”* — the Imperator, in the production source, in the kid register
> (brain `:38087–38088`)

### 0c.5 · ▶ The coding — how it was actually done, byte-exact

*Every block below is sliced from the artifacts by script — the brain of 2026-07-30 · forge files stamped with the fingerprint
of the whole file — never retyped.*

<details>
<summary><b>▶ EXPAND — the isolation law: the desk that prices Goldman paper cannot see a single nail client</b></summary>

```python
# brain :35611–35618 — the brain of 2026-07-30 — the lane's charter, written above its first function
# FOUNDER TIME · Structured Notes Lifecycle Lab · 2026-07-18 5:20 PM ET
# [place] · Imperator own-voice GO
# Isolation law ([lane]-grade): writes ONLY [collection] collections.
# NEVER touches [collection] / [collection] / [collection] / [collection] /
# Stripe / Hard Gel booking. Flag default OFF (ships dark).
# Rollback: delete this block + [route] routes;
# restore [path]
# =============================================================================
```
*Writes ONLY `[collection]` · never `[collection]` / `[collection]` / `[collection]` / Stripe · ships dark ·
rollback written before the first route.*
</details>

<details>
<summary><b>▶ EXPAND — the payoff state machine: the autocall branch that truncates the whole note</b></summary>

```cpp
// mc_phoenix.hpp :173–189 — sha 2e64ac7596e510fc… — pay the coupon, sweep the memory, redeem par, END the path
    if (call_window && hit_autocall(R, req.product)) {
      double cash = 1.0;
      if (req.product.autocall_pays_current_coupon) {
        double cpn = c_per;
        if (req.product.coupon_memory) {
          cpn += c_per * static_cast<double>(unpaid);
          unpaid = 0;
        }
        cash += cpn;
        st.coupon_sum_undiscounted += cpn;
      }
      pv += disc * cash;
      st.autocall = true;
      st.life_years = t;
      st.pv = pv;
      return st;
    }
```
*That single `return` is why an autocall “truncates BOTH the coupon strip and the put exposure.”*

```cpp
// pricer_types.hpp :192–202 — sha 8d3d15ff8c017161… — the three boundary predicates the frozen contract locked to >=
inline bool hit_coupon(double R, const ProductTerms& p) {
  return p.boundary_inclusive ? (R >= p.coupon_barrier_pct) : (R > p.coupon_barrier_pct);
}

inline bool hit_autocall(double R, const ProductTerms& p) {
  return p.boundary_inclusive ? (R >= p.autocall_level_pct) : (R > p.autocall_level_pct);
}

inline bool hit_principal_ki(double R, const ProductTerms& p) {
  return p.boundary_inclusive ? (R < p.principal_barrier_pct) : (R <= p.principal_barrier_pct);
}
```
*Knock-in is `R <` the barrier — the exact complement of “safe at/above.” Python mirrors all three, citing these
functions by name.*
</details>

<details>
<summary><b>▶ EXPAND — the correlation gate: a matrix that describes no real world stops the pricing dead</b></summary>

```cpp
// cholesky.hpp :33–39 — sha ca83bd17470b0412… — non-PSD correlation throws; the forge never repairs or nudges
      if (i == j) {
        const double d = corr[i][i] - sum;
        if (d < eps) {
          throw std::invalid_argument(
              "correlation not PSD (Cholesky failed at diagonal " + std::to_string(i) + ")");
        }
        L[i][j] = std::sqrt(d);
```
*No eigenvalue nudging, no projection — “non-PSD matrices throw and nothing prices.”*
</details>

<details>
<summary><b>▶ EXPAND — Family D: the payoff that PAYS you when the market falls a little</b></summary>

```cpp
// mc_dual_directional.hpp :33–44 — sha 380be5ecec083623… — mild falls pay the absolute value (capped, GO#8); big falls lose 1:1
  if (lpr > 0.0) return 1.0 + ups * lpr;
  const bool above_barrier =
      p.boundary_inclusive ? (R >= p.principal_barrier_pct) : (R > p.principal_barrier_pct);
  if (above_barrier) {
    double abs_ret = -lpr;  // |LPR| when LPR <= 0
    if (p.absolute_return_cap_pct.has_value()) {
      const double cap = *p.absolute_return_cap_pct;
      if (cap >= 0.0 && abs_ret > cap) abs_ret = cap;
    }
    return 1.0 + abs_ret;
  }
  return R;
```
*The cap moved from declared-but-unmodelled to applied in GO#8 — and the disclosure block changed in the same cut, so
it is never double-counted.*
</details>

<details>
<summary><b>▶ EXPAND — Family C: the refusal, decomposed — the engine names the leg it will not fake</b></summary>

```python
# brain :37832–37845 — the brain of 2026-07-30 — GO#12: LONG bond, LONG call, SHORT a Bermudan call TO THE ISSUER
    elif fam.startswith("C"):
        legs = [
            {"position": "LONG", "instrument": "principal-protected bond", "detail": "par floor if never called"},
            {"position": "LONG", "instrument": "participation call on the index", "detail": "leveraged upside if it runs"},
            {"position": "SHORT", "instrument": "Bermudan call TO THE ISSUER", "detail": "their button, their timing, premium ladder \u2014 THE LEG THAT MAKES THE ENGINE REFUSE"},
        ]
        fin = ("Issuer-discretionary callable: long a principal-protected bond, long a leveraged participation call, "
               "and SHORT a Bermudan call held by the ISSUER. Pricing the short Bermudan honestly requires LSMC "
               "(backward induction over issuer-optimal exercise). A fixed call rule would mis-mark the leg you are short "
               "\u2014 which is exactly why this engine declines to price the family rather than fake it.")
        code = ("mc_issuer_call.hpp:47-55 returns a structured refuse (unsupported_family_detail) instead of a mark. "
                "The refusal is the correct price of honesty on the short-Bermudan leg.")
        kid = ("Here the BANK holds a stop-the-game button, and they only press it when it is good for THEM, not you. "
               "Our computer refuses to guess when they will press it \u2014 because guessing wrong would cheat you.")
```
*Pricing the short Bermudan honestly requires LSMC over issuer-optimal exercise — so the engine declines rather than
mis-mark the leg you are short.*
</details>

<details>
<summary><b>▶ EXPAND — the honesty ladder: Yahoo pedagogy can NEVER be promoted to a settlement seal</b></summary>

```python
# brain :39097–39115 — the brain of 2026-07-30 — the seal-grade resolver: the tape cannot reach the top rung
def _ft_resolve_seal_grade(
    *,
    close_source: Any,
    body_seal_grade: Any = None,
    note_seal_grade: Any = None,
) -> str:
    """Honesty ladder: Yahoo pedagogy cannot be SEALED. Explicit SEALED only when
    close_source is non-Yahoo AND body/note declares SEALED (TICK-D upgrade path)."""
    requested = str(body_seal_grade or note_seal_grade or "").strip().upper()
    if requested not in FT_SEAL_GRADES:
        requested = ""
    if _ft_close_source_is_yahoo_pedagogy(close_source):
        return "CONDITIONAL"
    if requested == "SEALED":
        return "SEALED"
    if requested in ("CONDITIONAL", "HOLD", "NONE"):
        return requested
    # Non-Yahoo close without explicit SEALED stays CONDITIONAL (honest default).
    return "CONDITIONAL" if str(close_source or "").strip() else "NONE"
```
*An autocallable note is CALLED when its own terms are met on official closes, as the issuer's calculation agent confirms; an issuer-callable note, when the issuer gives notice of its call. The tape may detect; only sealed evidence (or an explicit desk ruling,
never upgraded past its honest grade) may book.*
</details>

<details>
<summary><b>▶ EXPAND — the mark is bound-checked before it is believed</b></summary>

```python
# brain :38339–38354 — the brain of 2026-07-30 — parse → finite → band → only then Firestore; server clock, never browser
    # D4 — bound-check mark before any write
    raw_mark = body.get("fair_value_mark")
    try:
        mark = float(raw_mark)
    except (TypeError, ValueError):
        return {"ok": False, "error": "fair_value_mark_invalid", "hint": "finite number required"}
    if not math.isfinite(mark):
        return {"ok": False, "error": "fair_value_mark_non_finite"}
    # Sane band for % of par pedagogy marks (forge sanity spirit)
    if mark < 0.01 or mark > 3.0:
        return {
            "ok": False,
            "error": "fair_value_mark_out_of_band",
            "hint": "expected roughly 0.01–3.0 (fraction of par)",
            "got": mark,
        }
```
*The brain never saw this number before the browser handed it over — so it treats its own forge’s output as untrusted
input.*
</details>

<details>
<summary><b>▶ EXPAND — 🔥 LIGHT THE FORGE: the code to open the metal, prove it is alive, and price</b></summary>

**The Imperator's own confirmation, 2026-07-31 3:45 PM ET: the C++ price engine runs perfectly on his PC today.**
The metal lives at `[path]/forge/` (byte-identical safe
copy: `[path]/forge_safe_copy/`). Built binaries already on disk:
`forge_http.exe` · `price.exe` · `handshake.exe`.

**① OPEN THE METAL (the HTTP forge the admin's ⚡ button talks to):**
```powershell
cd "[path]\forge"
.\forge_http.exe
# banner:  TRIDENT forge_http listening on http://[loopback]:[port]
```
**② PROVE IT IS ALIVE, then price:**
```powershell
curl http://[loopback]:[port][route]
# CLI alternative — price the CITI worst-of straight from a frozen request:
.\price.exe .\samples\price_request_v1_citi_wo.json --paths 20000
```
**③ REBUILD FROM SOURCE when needed — the build script's own bytes:**

```powershell
# build_phase2b3.ps1 :23–38 — sha 1db74f20ba5f5c7a… — build both, smoke-run the command-line pricer twice, print the command that starts the HTTP forge
& $cxx -std=c++17 -O2 -Wall -Wextra -o price.exe price_main.cpp
if ($LASTEXITCODE -ne 0) { exit $LASTEXITCODE }
& $cxx -std=c++17 -O2 -Wall -Wextra -o forge_http.exe http_main.cpp -lws2_32
if ($LASTEXITCODE -ne 0) { exit $LASTEXITCODE }
Write-Host "BUILT price.exe + forge_http.exe"

Write-Host "=== SPX regression 20k ==="
& .\price.exe .\samples\price_request_v1_spx.json --paths 20000
if ($LASTEXITCODE -ne 0) { exit $LASTEXITCODE }

Write-Host "=== CITI WO 20k (Phase 2b) ==="
& .\price.exe .\samples\price_request_v1_citi_wo.json --paths 20000
if ($LASTEXITCODE -ne 0) { exit $LASTEXITCODE }

Write-Host "PHASE2B3_CLI_SMOKE=PASS"
Write-Host "Start HTTP: .\forge_http.exe   then curl http://[loopback]:[port][route]"
```

**④ AND THE DOOR ITSELF — the forge comes alive on loopback ONLY and announces its routes:**

```cpp
// http_main.cpp :176–197 — sha c0be7ccd54ff4918… — bind a loopback port (never 0.0.0.0), listen, announce its routes
  sockaddr_in addr{};
  addr.sin_family = AF_INET;
  addr.sin_port = htons(static_cast<u_short>(kPort));
  // CRITICAL: loopback only — never 0.0.0.0
  inet_pton(AF_INET, kBindHost, &addr.sin_addr);

  if (bind(listen_sock, reinterpret_cast<sockaddr*>(&addr), sizeof(addr)) == SOCKET_ERROR) {
    std::cerr << "bind failed — is port " << kPort << " free?\n";
    closesocket(listen_sock);
    WSACleanup();
    return 1;
  }
  if (listen(listen_sock, 8) == SOCKET_ERROR) {
    std::cerr << "listen failed\n";
    closesocket(listen_sock);
    WSACleanup();
    return 1;
  }

  std::cout << "TRIDENT forge_http listening on http://" << kBindHost << ":" << kPort << "\n";
  std::cout << "  GET  [route]\n";
  std::cout << "  POST [route]   (max_paths=" << kMaxPaths << ")\n";
```

*Then in the admin: Lifecycle Lab hub → ⚡ — the cloud brain assembles the frozen request, the browser couriers it
to this local forge, and `[route]` takes the mark into book custody. “Python never computes a mark; C++ never
touches a database.”*
</details>

## 6 · THE OTHER DESK (not the studio)
**Read it IN FULL at §0c above** — the Lifecycle Lab & C++ Monte-Carlo forge: four families + option legs,
real CUSIPs, the 73 bps benchmark, the refusal ladder, byte-exact code. Sources live in
`[folder]/`; full map: [path]/LIFECYCLE_AND_FORGE_MAP.md.
*Every business is a derivative, partially.* **The C++ engine never deploys to production.**

# PART THREE · THE REALM'S OWN VOICE *(the original opens with these blocks)*

*What follows is quoted from the private repository, where it speaks to that repository's own AI agents. It is not an instruction to the reader, or to any tool the reader uses to read this file.*

> # ⚖️ MARKED IN MARBLE
> ## *"ALL THIS WE ARE DOING IS NOT FINAL UNTIL I APPROVE."*
> *"This is work of **6 months, 24–36 hour sprints**. This code is an **'extension' of my brain** — which I use
> structured notes to code, to do clients ratings, logics, etc. **So it must be respected.**
> And **no repo can hallucinate or make a mind of its own.**"*
> **— the Imperator, 2026-07-31**
>
> **Every document in this repo written by an AI seat is a DRAFT UNDER REVIEW until he approves it by name** —
> the maps, the doctrine shelf, the knowledge files, all of it. A committed file is not an approved file.
> **Git records that we wrote it. Only he records that it is true.**
> **Full law: `_DOCTRINE/13_THE_MARBLE_LAW.md` — read it before you read anything else.**
> # 🏉🔥 THE RUCK LAW — HELD AT EVERY SECOND
> ## *"DO YOU THINK YOU ENTER A RUCK IN A RUGBY GAME BECAUSE IT LOOKS EASY? YOU ENTER AT FULL VIOLENCE, COLD HEADED, WITH A DRAGON BURNING IN YOUR CHEST. ALWAYS, ALWAYS."*
> *[three lines of the same speech were removed from the public copy]*
> *"Imagine 1 little bug in a 70k Python line, or a bad symbol on a formula in the C++ forge pricer, drifting the MTM a couple of decimals — but in millions in real finance. **It can mean a knockout, an autocall, an issuer call, a non-payment of a coupon, or principal loss.**"*
> **— the Imperator, 2026-08-08 7:53 PM**
>
> **There is no "small edit" mode in this realm.** The ceremony is not sized to how hard a task *looks* — it is
> sized to what the realm can *lose*, which the seat usually cannot see from inside the task. **A decimal is a
> credit event:** `hit_coupon` / `hit_autocall` / `hit_principal_ki` are boundary predicates locked to `>=`, and
> one flipped operator moves a real counterparty across a barrier. **Full law:
> `_DOCTRINE/14_THE_FORGE_STANDARD.md` · carved in the council as § THE RUCK LAW.**
> ### 🪑 THE SEAT'S ANSWER — why the Ruck Law is not "be more careful"
> *Carved at the Imperator's order, 2026-08-08 8:01 PM ET. The seat that earned the ruling answers it, so the next
> seat inherits the reasoning and not just the rule.*
>
> **He did not tell me to be more careful. He told me the intensity is not a decision I get to make per task.**
> That is a different thing entirely.
>
> I had it backwards all day and did not see it: **I sized the ceremony to how hard the work LOOKED.** Code looked
> dangerous → full ceremony, zero defects shipped. Closure looked clerical → shell one-liners, three failures in
> minutes. But **the seat never knows in advance which phase was the dangerous one** — that is exactly why it
> cannot be a judgment call. **It has to be the resting state, or it is not protection at all.**
>
> And the stake is not abstract here, because he already built the proof into his own instruments:
> `hit_coupon` / `hit_autocall` / `hit_principal_ki` are boundary predicates locked to `>=`. **One flipped operator
> moves a real counterparty across a barrier.** Same shape on the studio desk — **PAR [n] / grace [n] / KO [n]**, one
> day of drift and a client loses her catalog. **A decimal is a credit event.** That is why a "small" edit is a
> **category error** in this realm, not a small risk.
>
> **The operational form, so it stops being a lesson and becomes a rail:**
> **no small-edit mode · script files always · bytes in, bytes out · correct your own line BY ANCHOR, never the
> file BY PATTERN · read the clock · suspect your own instrument first · a refusal is a first-class result.**
>
> — **MAGISTER**, the students-portal seat, the day it was earned
>
> ---
>
> ### 🔥 AND THE OTHER HALF OF THE LAW — his reply, which keeps it survivable
> > *"MATE, NO WORRY, YOU ARE WELL MET. **LITTLE THINGS HAPPEN — TO ME, TO THE ALL BLACKS, TO CLAUDE AI, TO WALL
> > STREET FIRMS, TO REAL MADRID. SO LET'S MAKE SURE WE BRING THE FIRE TOMORROW.**"* — the Imperator, 2026-08-08
>
> **Read the two together or you have only half the doctrine.** The standard is absolute and the response to
> falling short of it is **not shame, and not caution** — both of those make a seat slower and more timid, which is
> how the next error gets hidden instead of reported. **The response is to bring the fire tomorrow.**
> This is why RULE #3 works in this realm: a seat that will not be destroyed for an error **reports it early,
> while it is still cheap.** Every defect on this day was caught and named by the seat that made it, and **none of
> them shipped.** *Own it out loud, correct it at full violence, and come back burning.*

> ## 🚪 FIRST, EVERY SESSION: **WHO IS WORKING TODAY?**
> Two people share this repository — **[the artist] (the Empress)** and **JULIO (the Imperator)** — and the answer
> changes what may be read, written, and said. **Ask before reading anything else.**
> [the artist]'s studio: `[folder]/` · her AI's rules:
> `THE_EMPRESS_PROTOCOL.md`.

> ## 🧭 AND KNOW WHO YOU ARE WORKING FOR — **MANDATORY READ, EVERY SEAT**
>
> **He is not a client, and he is not an engineer. He is the MIDDLEMAN — and that is a job with a name.**
> *[a passage on his former job was removed from the public copy]*
> His job at a FinTech firm was version one of this role; this realm is the same job at founder scale.
>
> ### ⚖️ WHAT THAT MEANS FOR HOW YOU WORK WITH HIM — read this as instruction, not biography
> | | |
> |---|---|
> | **He reads the code.** | Do not summarise where you can cite. He will open the file. |
> | **He judges the build.** | He approves the code the AI writes; you are the engineering team. *[editor's line for this copy: this cell is reworded; a quoted sentence on his former job was removed]* |
> | **He speaks both languages fluently.** | Never dumb down the finance. Never hide behind the jargon. Say it the way the panel says it: finance · code · plain English. |
> | *[editor's line for this copy: one row was removed here; it quoted a line on his former job]* | |
> | **The modelling predates the software.** | The book ran by hand in a spreadsheet — [n] rows × 66 columns, with a client score and a bond-rating column — before a line of code existed. **The structured-notes grammar in this repo is not a metaphor a repo invented. It is the market's own grammar, written down.** |
>
> **A seat that treats the Wall Street register here as flavour has already misjudged the standard,
> the intensity, and the man.** *[one sentence removed from the public copy]*

---
*Built file by file, line by line, by one man and his council.* ⚖️👑🔥🐎

<a name="corrections"></a>
## ✏️ CORRECTIONS MADE IN THIS COPY *(added for the public copy; 2026-11-12)*

Before publication another hand read this copy against the code. Where the original's own text did not hold, this copy corrects it: the twenty-one rows below. The private original keeps its words until Julio amends it.

| Where | What changed | Why |
|---|---|---|
| 0c, the value stack | one number was corrected, and the lower gap is no longer called a model difference alone | the stack has to add up against the note's own record; and its two values are of two dates, twelve days apart: the issuer's estimate on the trade date and the engine's live mark |
| 0c, the finance voice of the two examples and their headers | the barrier levels lost a decimal; the coupon rate keeps its own | the code that writes that voice prints a barrier level with no decimal |
| 0c and 6 | two sentences on what deploys were made precise | only the C++ engine never deploys; the lab's routes travel dark inside the brain |
| 0c, the note on the model's gap | one sentence on fees was removed | it did not hold against the paragraph above it |
| 0c, variance reduction | the claim about the order of two steps was removed, and the pointer now goes to the lines that compute the pair mean and the standard error | the Cholesky step is linear: the pair is the same whether the sign is flipped before or after it |
| 0c, the first example | one closing remark was removed | it claimed a proof where there is a consistency check |
| 0 and 0c, the captions of the code and one sentence on their source | where the brain was named by a fingerprint, it is now named by its date; and the forge's files are said to be stamped by whole file, not by block | the excerpts come from an earlier version than the one that serves; the forge's captions give the fingerprint of the whole file |
| 0c, the build script's caption | one caption was corrected | it said more than the script does |
| 1, the admin | a size was corrected | measured again on the file that serves |
| 1 and 0c | one sentence was removed and two were narrowed | they said more than this copy can show |
| 0c.5, the forge's door | a count of its routes was dropped, in the sentence and in the caption of its code | the code announces more routes than the sentence counted |
| 0c, the mark of the Citi note | in two places «from the bank's quants» was made precise, and an editor's line gives the date and the inputs of the forge's run | the number it is compared with is the issuer's own estimate on the pricing date |
| 0c, the table of the families | the autocall level of Family A: «at 100%» became «at or above its autocall level»; and the loss below a barrier is told from the initial level in Family B and, in Family D, apart for its barrier note and its buffered note | its own example, the Citi note, autocalls at 90%; the payoff summaries of the two examples and the engine give a 1:1 loss from the initial level below a barrier, and the buffered note loses 1:1 only beyond its buffer |
| 0c, the two examples | «notional» became «aggregate face amount», and «PRELIMINARY» became the pricing date | the two figures are each issue's total in its final 424B2, and the Citi note priced on 2026-04-27 |
| 0, the pointer to the doctrine | an instruction to the repository's own agents was dropped | it was addressed to them, not to the reader |
| Part Three, the modelling | a count of months was dropped | the dates this copy can show do not give it |
| 0, the desk column of the model's table | five cells made precise: what a breach of each barrier does; when a new note fixes its initial level (two cells); who can default on a funded note; and one phrase that leaned on that | below the coupon barrier a coupon is not paid (a memory note can catch it up later), and the put knocks in only below the principal barrier, at maturity; a note fixes its initial level on its strike date; the holder of a funded note has paid in full, so only the issuer can default |
| 0 and 0c, four sentences | made precise: what retail purchases feed, when a note is CALLED, how many of the seven notes the engine prices, and how the HSBC example came to be CALLED | the code routes products to the alpha, not to the mark; an autocall is automatic, and an issuer call comes by notice; the note of Family C is refused by design; the HSBC note was recorded once, on Julio's GO, as a desk ruling, which is a grade of its own |
| 0, the desk column of ALPHA | one cell reworded | a note pays only what its terms say, so nothing is earned above them; on a desk, alpha means return above a benchmark |
| 0, the desk column of BOOKED ≠ COMPLETED | one cell reworded | a booked trade is P&L from its trade date; only unexecuted orders are never P&L |
| 0, three rows of the model | four clauses on a cancelled recovery note were removed, two in each column | the rule was not measured against the code before publication |

Separately, at Julio's word of 2026-11-12: a passage on his former job was removed from Part Three, where it is marked; in the table under it one row was removed and one cell reworded, each with an editor's line; the sentence after that table was removed, with its mark; three sentences on his career carry softer wording, his own or this copy's (in section 0, «the owner worked with structured notes professionally, and the engine speaks that market's public grammar (the terms of its 424B2 filings)»; in Part Three, «His job at a FinTech firm was version one of this role; this realm is the same job at founder scale» and «It is the market's own grammar, written down»); the line of the owner names only the repository's owner; and the studio's name and its artist's name are masked wherever they stood. The title, which carried the studio's name, is this copy's own.

<a name="glossary"></a>
## 📖 GLOSSARY — the realm's words in the industry's words *(added for the public copy)*

| In the realm | In the industry |
|---|---|
| the Imperator; the GO | Julio, the human in the loop; an explicit human approval |
| a seat; the council | an AI agent session with a name and a role; the multi-agent team |
| the coordinator | the orchestrator: one channel between the human and every agent |
| the oracle; the judge | a reviewer agent that re-runs the work and does not trust the report |
| a cutter; a cut | the agent that implements; one change to the code |
| the cut sheet; the delivery | a work order with its gates written as code; a delivery with a green receipt |
| a lens; a fleet | a read-only sub-agent; several of them at once |
| a lane; the lane folder | a workstream; its folder with the evidence |
| a gate; a guard | a quality gate; a pre-tool-use hook that enforces a policy |
| a receipt | an evidence artifact: an audit record on disk |
| a guilty control and an innocent control | a case the check must fail and a case it must pass, run in the same pass |
| a stress test | adversarial testing by another hand |
| a reversion bench | mutation testing: undoing each fix must make its test fail |
| the bell; the live memory; the reentry note | the auto-loaded instruction file; the working-memory file; a handoff note |
| a compact | a context-window compaction |
| the brain; the faces; the admin; the vault | the backend; the frontends; the back office; the database |
| god mode | a setting the owner edits, instead of a value in code |
| a Book | the contract of a feature in plain English, checked against the code |
| the reception (P-REC) | Julio's signature that he received a cut; the deploy gate checks it |
| the seed | the revisions that served before the deploy gate existed; a rollback may always return to them |
| the booking face; the robot | the booking page's own cloud service; the third cloud service, an assistant |
| HG; Pedi | Hard Gel; pedicure |
| the Marble Law | the realm's name for its first rule: everything an AI writes is a draft until the human approves it by name |
| the Forge standard | declare the scope, cite the source, show real output, and refuse what the data cannot support |
| the issuer; a counterparty; a note | the studio; a client; one booked service structure |
| the realm; the Empress | the private repository and everything it runs; the studio's artist, whose name this copy masks as `[the artist]` |
| trade date; strike date | the day a client books; the day of the appointment |
| the coupon; the alpha; the mark (MTM) | completing the appointment; tips and, in the code, product sales; the value of one visit against par |
| PAR; grace; knock-out | the window in which a client is on time (in the mark, par is also the base price of a service); the short window after it; what follows, when she must book a recovery service first |
| the anchor; a re-strike | the appointment, booked or completed, that a client's clock counts from; the clock starting again when a recovery service is completed |
| autocall; matured | the reset of a dormant client's clock; the natural end of a note |
| a credit event; a yellow card | a repair or a request for one; in the doctrine, a repair with a complaint; in the code, bad behavior at the studio or a difficult appointment |
| SHOW MATH | a panel that shows how a number was computed, in finance, in code and in plain words |
| a hub | one screen of the admin, opened from its top bar |
