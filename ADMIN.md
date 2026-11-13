# 🎛️ THE ADMIN — CTA BY CTA

> **Approved for publication by Julio on 2026-11-12.**
>
> **What this file is.** The admin of the studio, button by button. A CTA is a button: each one opens a tool that was built in the private repository this copy comes from. This file is a companion to the README of this repository, and it hangs from the same grammar: the studio is the issuer, and each client holds notes. This version is an inventory with pieces of code. End-to-end walk-throughs may come later, after a review of their own.
>
> **The size of it,** measured on 2026-11-12, before that day's cut (README, section 4i). The live admin showed a base screen and 27 hubs on its top bar, with 57 panels across the hubs and the base screen. Its code is one engine file of about 60 thousand lines: a base, and modules appended after it as features came. Behind it the backend's code holds about 260 distinct admin path strings, and some of them are switched off.
>
> **How to read it.** The labels are close to the ones the owner sees; a few are given in English, and one in general words. “First recorded” is the month a feature first appears in the realm's own log. Route names, collection names, the numbers of the business and client data are not here, and one write flag inside a code block is masked as `[flag]`. Two buttons of the top bar are not described in this copy. Each block of code was sliced by line range from the private repository and its delivery archive; its caption gives the file, the lines and a fingerprint: the first 16 hex characters of the SHA-256 of the lines as they are printed here, joined by line feeds.
>
> **The rule that repeats, and its limits.** Most buttons that write rehearse first: a preview or a dry run, then a confirm, then the write. A few save directly (mark paid, a new product and the approval of a review among them). Most things are retired, voided or switched off instead of deleted; there are real deletes too, and the rows name the main ones.
>
> **Switches.** Many of the newer pieces sit behind a server flag that ships off. What production has switched on is not measured in this document.

## 1 · Access and the shell

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Admin login | sign-in before any hub opens | verified on the server | Jul 2026 |
| One hub at a time | opening a hub hides the others, with one way out | the base hubs hide the top bar's buttons and switch each other off; the eight newer module buttons open overlays on top, outside that system. New features mostly arrive as modules appended at the end of the engine file, each with its own window. When one needs the core, the cut adds a named anchor there, and the base has taken dated hooks and cures. The cost: four generations of the course editor still sit in one file of about 3 MB | Jul 2026 |
| A limit on heavy reads | a heavy read gives up after a time limit | a read that can be aborted | Jul 2026 |
| The server decides | two hubs appear only when the backend says they are on | buttons gated by a status read | Aug to Oct 2026 |
| Self-audit | almost every appended module carries an audit that runs in the console | one audit of the base, the Finance Lab's, downloads its verdict as a file | Jul 2026 |
| Its own deploy | the admin is served as its own bundle, published by hand, outside the deploy gate (the README, 4j) | most modules and many routes carry a build tag | Jul 2026 |
| Emergency row | the next edit skips the calendar sync, only after a typed phrase | a typed confirmation | — |

## 2 · The day: the schedule is the money desk

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Day · Week · Month · New booking | the schedule: book, edit, reschedule, cancel | every cancel records whose fault it was: the client's, the studio's or unknown. That feeds the client's volatility in the Finance Lab, and a fault of the studio never counts against her. A cancel also deletes the visit's inventory movements and its calendar event, and its settlement when the admin confirms | Jul 2026 |
| Products at the visit | what was used or sold at the chair | preview, then write; a re-save on a settled visit deletes its earlier use movements | — |
| Payment details & admin checkout | charges the saved card | on the server, after the amount is confirmed | Jul 2026 |
| Studio settle | closes the ticket: card, cash or a transfer app, plus the tips | three layers: the deposit, the checkout at the chair, the settlement. Settling moves the inventory and books the usage as an expense. There is an unsettle, which deletes those inventory movements | to Aug 2026 |
| The desk's emails | the settlement email, locked after one send unless it is resent on purpose; the booking notice to the studio; the daily, weekly and portfolio summaries | the sends from the admin sit behind a server flag that ships off; the booking notice has no flag of its own, and only the note's figures in it sit behind a second flag. The server writes the text in English and Spanish and an outside mail service assembles the email. An audit row for the settlement and for each summary. The daily and the weekly refuse until the day or the week is closed | Jul 2026 |
| Yellow card | after a confirm, for bad behavior at the studio or a difficult appointment (in the doctrine, a repair with a complaint is one). A repair is its own credit event, marked in the Finance Lab | written from the checkout; removed with a reason, by deactivation: the history stays | Jul 2026 |
| Start manicure services (in the checkout) | graduates a client who wears extensions. While she is on the extensions ladder (behind a switch that ships off), her menu is her matching correction plus pedicures; after the graduation the full menu opens, with Hard Gel | after a confirm; it writes an audit row | — |
| Ledger | after the last appointment of the day it asks for the day's expenses | integer cents; append-only; deterministic ids, with a suffix on a collision. The “no expenses” stamp refuses a future day and a day already reported | Jul 2026 |
| Analyst | earned, spent, kept, the margin, the biggest cost, a tax reserve, and a hire calculator | roll-ups by period; the calculator is plain arithmetic in the browser | Jul 2026 |
| Services & Clients | the counter: visits, services, new, returning and recurring clients, booked against collected, bookings by trade date and by strike date, products. Tapping a number shows its rule and its rows | a pure module of rules that audits itself. In the studio's working language by default, with other languages one tap away | Oct 2026 |
| Check-in, on each appointment | on an iPad: the suggested forms and one signature. Once saved it opens read-only, and a correction is made field by field. A kiosk mode hands the iPad to the client, full screen, with only her part | the saved check-in is frozen; every correction is kept in a history | Oct 2026 |
| Check-in ⚙ (god mode: see section 10) | the switch, the window, the design, the forms and the map of suggested forms | every save is “Rehearse”, then “Confirm and save”: the confirm must carry the fingerprint of the body that was rehearsed, or the server refuses it. A field is retired, never deleted. “How it works” opens the Check-in Book | Oct 2026 |
| Sell products · Product orders | a sale at the counter, always previewed; a web order holds the card and charges it only on approval | a settle that can be repeated without charging twice; a check of the expected total that refuses if the price changed; one transaction | Sep 2026 |
| Download Evening Report | product buyers and their review follow-up; new clients, rebooked or not; the follow-up list | built on the server as a workbook: a dashboard sheet and three data sheets | Sep 2026 |
| Appointment photos | upload, list, remove; an email that invites the client to log in and see them, after a confirm | a signed upload straight to storage. A removal goes after a confirm: the record stays, marked as removed, and the photo file is deleted from storage | Jul 2026 |

The counter does not trust its own numbers. After it counts, it checks that they add up; if any check fails, the screen shows no number:

```python
# contador_contract.py :484–506 — as printed here, sha 5777e587d2435440… — the counter audits itself (names in Spanish: clients = new + returning + recurring; completed + scheduled = total)
    def chk(nombre: str, ok: bool, detalle: str = "") -> None:
        out.append({"check": nombre, "ok": bool(ok), "detalle": detalle})

    for c in COLUMNAS:
        t = tabla[c]
        chk(f"{c}: clientas = nuevas + returning + recurrentes",
            t["clientas"] == t["nuevas"] + t["returning"] + t["recurrentes"])
        chk(f"{c}: servicios = manicuras + pedicuras + otros + sin_clasificar",
            t["servicios"] == t["manicuras"] + t["pedicuras"] + t["otros"] + t["sin_clasificar"])
        chk(f"{c}: reservado y cobrado no son negativos", t["reservado_cents"] >= 0 and t["cobrado_cents"] >= 0)
        chk(f"{c}: clientas <= visitas <= citas", t["clientas"] <= t["visitas"] <= t["citas"])
        filas = [r for r in show_math if c == "total" or r["columna"] == c]
        chk(f"{c}: visitas = pares (clienta, día) del show_math", t["visitas"] == len({(r["k"], r["fecha"]) for r in filas}))
        chk(f"{c}: multi = citas multi del show_math", t["multi"] == sum(1 for r in filas if r["cubeta"] == "multi"))
    for campo in ("citas", "multi", "manicuras", "pedicuras", "otros", "sin_clasificar", "servicios",
                  "reservado_cents", "cobrado_cents"):
        chk(f"completadas + agendadas = total ({campo})",
            tabla["completadas"][campo] + tabla["agendadas"][campo] == tabla["total"][campo])
    chk("el total de clientas no supera la suma de las dos columnas",
        tabla["total"]["clientas"] <= tabla["completadas"]["clientas"] + tabla["agendadas"]["clientas"])
    chk("show_math = citas del total", len(show_math) == tabla["total"]["citas"])
    chk("reservado del total = suma del show_math",
        sum(int(r["reservado_cents"]) for r in show_math) == tabla["total"]["reservado_cents"])
```

## 3 · Clients and growth

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Create Client · Search Clients | create, search, update, merge, block; a preview of her portal as she sees it | an edit of a client reaches her appointments, with an audit of before and after | Sep 2026 |
| Download all clients (CSV) | every client record in one file, from behind the admin's sign-in | read page by page; maps become counts and lists are capped | — |
| Client journeys | her timeline: the photos and the notes of each session, shown to her or not | a presentation view over the client's page; her check-in answers, one card for each visit | Jul 2026 |
| Client Roster | the book by life cycle, from lost lead to dormant, and by stage, from new to loyal | the same two labels Julio kept in his spreadsheet: the code's own comments name the spreadsheet column | Jul 2026 |
| Relationship Management | removes or restores a client's access to her portal, with a note; the absence list | a confirm first; the list is read-only | Jun 2026 |
| Login Analytics | who logged in and whether she booked; new and existing clients; leads that stopped halfway; an audit of shared phones | read-only | Jun 2026 |

## 4 · The rules: the studio run as a structured-notes desk

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Barrier Rules | the maintenance covenant of each of the two programs | the rules, a preview for one client (breached or good), restore defaults, and a save that goes directly, behind a server flag | Jul 2026 |
| Barrier Contract · Autocall | a dated contract with versions for each program: the master switch, the autocall, the realm's clock and the clients' own clocks | a dry run first: the save stays disabled until a dry run of the identical body passes. A second dry run runs right before the real write, and the server also asks for a write flag. The past never changes. “How it works” opens the Barrier Book | Oct 2026 |
| God Mode: Barrier Reminders | the master switch of the nightly reminders, and their delivery ledger with the clients masked | one switch behind a confirm, read back after every write. The engine sends in two steps: the attempt is written before the send and the delivery after it | Sep 2026 |
| HG Studio Exemptions | reliefs for a fault of the studio (one of them moves the anchor forward), goodwill windows, and a dated “issuer call, mature” window (a setting of this desk, not of the barrier's contract) | a dry run, then a confirm that names the write flag, then the save. A deactivation goes the same way. At booking the “mature” window only lifts the knock-out; the Finance Lab reads it as matured | Aug 2026 |
| Appointment Emails — God Mode | every field with its value and where the value comes from, the document or the default; and the configuration in effect | it saves directly, with an audit row | Sep 2026 |
| Availability Hub | offering groups, saved to the catalog; a preview of the slots; a delete of a group | — | — |

In the desk's grammar, from the Barrier Book: the god-mode document is the term sheet's parameter page, and its dated versions are the fixing schedule; a new fixing never re-prices a past observation. A client's own clock is a bespoke note for one counterparty. A studio-fault exemption is the issuer re-fixing the observation date.

The past never changes, in code:

```python
# barrier_contract.py :511–532 — as printed here, sha 8d3bb5abdf646a43… — a version in force cannot be removed or changed, and a new one cannot be backdated
        for d, ov in old_by_date.items():
            od = _as_date(d)
            if od is None or od > now:
                continue
            nv = new_by_date.get(d)
            if nv is None:
                errors.append(f"{p}:past_version_removed:{d}")
            elif (_as_whole_days(nv.get("par_days")), _as_whole_days(nv.get("autocall_days"))) != (
                _as_whole_days(ov.get("par_days")), _as_whole_days(ov.get("autocall_days"))
            ):
                errors.append(f"{p}:past_version_changed:{d}")
        clean_versions = []
        for d in sorted(new_by_date):
            v = new_by_date[d]
            vd = _as_date(d)
            en_vigor = d in old_by_date and vd is not None and vd <= now
            ov = old_by_date.get(d) or {}
            cambiada = d not in old_by_date or (
                (_as_whole_days(v.get("par_days")), _as_whole_days(v.get("autocall_days")), str(v.get("note") or ov.get("note") or ""))
                != (_as_whole_days(ov.get("par_days")), _as_whole_days(ov.get("autocall_days")), str(ov.get("note") or "")))
            if d not in old_by_date and vd is not None and vd < now:
                errors.append(f"{p}:new_version_backdated:{d}")
```

And the save itself: validate, rehearse, and only then write:

```python
# main.py :26479–26488 — as printed here, sha 79bfbd0becf0687a… — a dry run returns what would be written; the real write also needs a server flag
    if not ok:
        return {"ok": False, "error": "validation_failed", "errors": errors, "dry_run": dry_run, "written": False}
    proposed = dict(normalized)
    proposed["version"] = 1
    proposed["audit"] = {"updated_by": str(admin_email or "").strip().lower(), "updated_via": "barrier_contract_save"}
    if dry_run:
        return {"ok": True, "dry_run": True, "written": False, "proposed_doc": proposed, "before": before_doc or {}}
    if not [flag]_enabled():
        return {"ok": False, "error": "real_write_disabled", "reason": "[flag]",
                "dry_run": False, "written": False}
```

## 5 · The money desks

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Master sheet (month) | one month of appointments as clean rows, with a CSV download | a range query; it drops the deleted, cancelled and waitlist rows; it joins the catalog for the prices and the clients for the names; one typed row for each appointment. Integer cents from the server; dates in the studio's time zone and dollars rendered in the browser. It is a SELECT, a JOIN and a projection, written in Python | before Aug 2026 |
| Download ledger CSV | Julio's old spreadsheet, returned: one month, a range or everything | the service amount records where its number came from; integer cents from the server, dollars with two decimals in the file; a missing price counts as 0 in revenue and is flagged in the data-quality column; cancels marked. A partial pull can only be downloaded marked as incomplete | Aug 2026 |
| CRM / Business Ledger | the bridge from the spreadsheet to the code: the old ledger saved as snapshots in a vault; the live ledger computed in Python; and a compare, with a gap report | matching by name and date: the same day is a strong match; one day off is a weaker one, with the amount as the tie-break. One to one; an ambiguous pair is flagged | Jul 2026 |
| Finance Lab | the live book of every client: standing, credit events, the structure assigned to her, and portfolio views. Its first prototype is outdated, by Julio's own ruling, and it is still on the top bar | a cockpit, a life-cycle view, a radar for each client, “Show Math” on each cell, English and Spanish; a frozen copy so that the book opens at once | Jun to Aug 2026 |
| Business Expenses | fixed bills, purchases, roll-ups by period, mark paid; an unmark deletes the paid event | mark paid saves directly | Jul 2026 |
| Dashboard Summary | deposits not yet earned, appointments with no photos, journey engagement, products sold, live standing, the life cycle of the notes | each number opens its own list | Jul 2026 |

One appointment becomes flat money columns, and the service amount says where its number came from:

```python
# main.py :50968–50982 — as printed here, sha d5581c60c49ec96e… — the service amount records where its number came from: stored, catalog sum or missing; integer cents
            tpc = d.get("total_price_cents")
            try:
                stored_cents = int(tpc) if tpc is not None and str(tpc).strip() != "" else None
            except (TypeError, ValueError):
                stored_cents = None

            svc_amt_cents: Optional[int] = stored_cents
            price_src = "stored" if stored_cents is not None else None
            if svc_amt_cents is None and sid:
                calc = total_price_cents_for_booking(catalog, sid, addons)
                if calc > 0:
                    svc_amt_cents = calc
                    price_src = "catalog_sum"
            if svc_amt_cents is None:
                price_src = "missing"
```

## 6 · The store and the products

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Product Inventory | vendors, stock, and purchase batches with their invoice | a repeated invoice number is refused; a batch with the same date and total as an earlier one needs a confirm | Sep 2026 |
| Catalog | products by vendor; create and edit | a new product starts with no stock; stock comes in through batches, and count adjustments correct it; a new product saves directly | Jul 2026 |
| Products & Batches — God Mode | every field of a product, with its sizes in ounces, grams or units, kept exactly as typed; price, stock, lot, photos; batches with their invoices; filling retail jars from a bulk batch, counted in grams; bottles opened, finished or voided; the shelf count; adjustments with a reason | what was already filled is summed from the movements, never read from a stored counter. A refusal says how many jars still fit. One atomic write, safe to repeat. Products, sizes and batches are deactivated or voided, never deleted; a photo can be hidden, or deleted for good after a typed word | Sep to Oct 2026 |
| The catalog guard | at every save it refuses, in the sizes that save touches, a packaging word inside a size name, two active sizes with the same measure, and a change of measure on a size that has stock unless a reason is given | false positives were hunted first. If the guard itself fails, the save still goes through, with a named warning | Sep 2026 |
| Sets | bundles by recipe: components, sizes, quantities and one price | preview, save, a delete that needs a typed word, a self-check, and a master switch that ships off. A pure module: no database, no network, no clock; built never to raise | Sep 2026 |
| Product Email Reminders | care reminders after a product is sold at a visit: the cadence and the friendly name of each product, a master switch, mute one client, a preview of tonight's run | every fact is checked again at send time; a ledger against duplicates; the sent mark is written only after the mail service accepts the message. Its configuration saves directly | Aug 2026 |
| Product Reviews | reviews from verified buyers; moderation in two languages | a signed token with a time limit and with no email or name inside. A rejection needs one of four reasons; an approval saves directly | Sep 2026 |
| Review QR | a QR for each product, or one for all; print it or download it | a QR engine written in-house, with Reed-Solomon error correction, that checks its own output. Codes can be rotated. Duplicates are caught, and there is a daily cap | Sep 2026 |
| Meta · Google | a read-only board of what goes out to Meta and to Google | an outbox with red, amber and green lights: no answer is never green. A public catalog feed whose ids are the ids of the purchase events. Server-side events, with personal data hashed. The push to Google's merchant catalog is decided, not started | Jul and Sep 2026 |
| Service Hub | services and add-ons with their images, which also feed the ads and the catalog feed | — | Jun 2026 |

Filling jars from a bulk batch. What was already filled is a sum of the movements, and the refusal says how many jars fit:

```python
# main.py :35087–35106 — as printed here, sha c139bf2dafbfb8e1… — what was already filled is summed from the movements, never read from a stored counter (two seat tags removed from the comments)
    # cuanto se ha envasado YA de este lote: se SUMA de las huellas, no de un contador guardado.
    # Un contador puede desincronizarse; la suma de los movimientos es la verdad.
    ya_g = 0.0
    fills = 0
    for mv in (part.get("movements") or []):
        if str(mv.get("movement_type") or "") != "fill":
            continue
        if str(mv.get("batch_id") or "") != batch_id:
            continue
        ya_g += _studio_inventory_finite_pos(mv.get("grams_used")) or 0.0  # un fill con nan no anula la compuerta
        fills += 1
    piden_g = gramos_por_unidad * unidades
    quedan_g = bulk_g - ya_g
    if piden_g > quedan_g + 1e-6:
        caben = max(0, int(quedan_g // gramos_por_unidad)) if gramos_por_unidad > 0 else 0  # jamas negativo
        return {"ok": False, "error": "not_enough_bulk", "http": 409,
                "batch_id": batch_id, "bulk_grams": bulk_g, "already_filled_grams": round(ya_g, 3),
                "remaining_grams": round(quedan_g, 3), "requested_grams": round(piden_g, 3),
                "missing_grams": round(piden_g - quedan_g, 3), "fits_units": caben,
                "hint": "caben %d tarro(s), no %d" % (caben, unidades)}
```

Two sizes that measure the same would be confused in the store and in the book, so the save is refused when it touches one of them:

```python
# catalog_guard.py :811–834 — as printed here, sha b627c5979b96e166… — two active sizes with the same measure, when the save touches one of them: refused, with a hint in plain words
        # ── ⓑ dos tamanos ACTIVOS con la misma medida, con al menos uno tocado ─────────────────
        by_key: dict[tuple, list[tuple[dict[str, Any], str, bool]]] = {}
        for z, zid, _prev, touched in rows:
            if not _active(z):
                continue   # un tamano APAGADO no compite en la tienda (T3 inocente)
            # C-LAZO + B-EV2: se compara por la medida COMPARABLE. «2 oz» y «2 oz jar» activos a la
            # vez SIGUEN siendo un duplicado (miden lo mismo de verdad), y «2 oz» escrito en el campo
            # `oz` choca con «2 oz» derivado del nombre, que antes se escapaba.
            key = measure_key_comparable(z, wlist)
            if key is None:
                continue   # sin medida medible no hay duplicado que declarar (jamas se adivina)
            by_key.setdefault(key, []).append((z, zid, touched))
        for key, grupo in by_key.items():
            if len(grupo) < 2 or not any(t for _z, _i, t in grupo):
                continue
            nombres = [_name(z) for z, _i, _t in grupo]
            ids = [i for _z, i, _t in grupo]
            texto = _measure_text(key)
            return ({"ok": False, "error": "size_measure_duplicate", "http": 400,
                     "names": nombres, "size_ids": ids, "measure": key, "measure_text": texto,
                     "hint": ("«%s» miden lo mismo (%s). Dos tamanos activos con la misma medida se "
                              "confunden en la tienda y en el libro: cambia la medida de uno, o apaga el otro."
                              % (" y ".join("«%s»" % n for n in nombres if n) or " y ".join(ids), texto))},
                    warnings)
```

The QR engine was written in the private repository, and it does not trust itself:

```javascript
// the admin's engine file :48068–48084 — as printed here, sha 2d41718a93323fd5… — the QR engine checks its own output: every Reed-Solomon syndrome must be zero
    /* --- (6) SINDROMES de Reed-Solomon: todos deben ser CERO --- */
    var rsOk = true;
    var sindromes = [];
    for (i = 0; i < nBloques && rsOk; i++) {
      var pal = bloques[i].datos.concat(bloques[i].ecc);
      var sb = [];
      for (j = 0; j < eccLen; j++) {
        var xj = GF_EXP[j % 255];
        var acc = 0;
        for (var t = 0; t < pal.length; t++) acc = gfMul(acc, xj) ^ pal[t];
        sb.push(acc);
        if (acc !== 0) rsOk = false;
      }
      sindromes.push(sb);
    }
    checks.rs = rsOk;
    fuera.sindromes = sindromes;
```

And in the public feed, a boolean that arrives as text is a trap. In doubt the function answers its caller's default, and for what the store shows that default is no, so it does not publish; for active and in stock it is yes:

```python
# catalog_feed_meta.py :135–153 — as printed here, sha 3d4339f009c325cb… — a boolean that arrives as text: in doubt it answers its caller's default
def _verdad(v, por_defecto=False):
    """
    Un booleano que llega como TEXTO es una trampa pagada de este reino: en python
    `bool("false")` es True, asi que un `storefront_visible: "false"` PUBLICA.
    Aqui solo es verdad lo que de verdad lo dice, y ante la duda se responde que NO:
    en un feed publico el error barato es no publicar, jamas publicar de mas.
    """
    if v is None:
        return bool(por_defecto)
    if isinstance(v, bool):
        return v
    if isinstance(v, (int, float)):
        return v > 0
    t = _s(v).strip().lower()
    if t in ("true", "1", "yes", "y", "si", "sí", "on"):
        return True
    if t in ("false", "0", "no", "n", "off", ""):
        return False
    return bool(por_defecto)
```

## 7 · The academy (the “Students Help” button is the whole student platform)

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Students Courses Editor | edits a course in the portal's own look: modules, lessons, several videos, PDFs, images, product cards, a switch between student and editor | it edits only the draft (sandbox) copy of the course: the live course opens read-only. A PDF lands where students open it. Autosave; every save stores a version first; history and restore | Aug 2026 |
| New Course | creates a course from scratch, then shows it and prices it | one atomic batch creates the live and the sandbox pair, hidden and with no price. Visibility and price are separate steps. Behind a flag | Aug 2026 |
| Video IDs | puts the streaming video ids into the sandbox lessons | it never publishes | Aug 2026 |
| Design Studio | paints the student portal: dials, presets, a live preview | draft, publish and unpublish, all with no deploy; a bad value is refused by name | Aug 2026 |
| Students Roster | questions and media grouped by student, the longest wait first | read-only | Aug 2026 |
| Publish to live | from the sandbox to the live course | check and compare first. It refuses, by name, if the live course changed meanwhile or the video ids are malformed. A copy is stored first. Only the fields on an allowlist are copied, and the price is not one of them; if the course already has its own price, publishing also reveals it. Exams travel too; a removed one is switched off, never deleted. Live history and restore | Aug 2026 |
| Student Form Editor | the onboarding questions | a dry-run preview on request, then the save; fields are retired, never deleted; an editor that sends its revision is told when it is stale | Aug 2026 |
| Exams — God Mode | exams for each course, graded by the artist | text or media questions; a number of free attempts, then a wait after each failed one. The state is computed when it is read, with no scheduled job. Grading in one transaction. The email carries a link, never the verdict. Behind a flag | Sep 2026 |
| Certificates | request, approve, reject, revoke; the template; the signature | the requirement is every lesson and every visible exam. One transaction freezes the serial, the versions of the template and of the signature with their hashes, and a hash of the record. Every view checks the hashes again. A public check by serial never returns an email. A template with scripts or outside addresses is refused, and the preview runs in a locked frame | Sep 2026 |
| Subscribed Students · Questions · Missions | the roster with its totals; answers to questions; mission photos reviewed slot by slot; a chapter passed | a read-only roster; replies and reviews | Jul 2026 |

Honest gaps: the flags of the newer pieces are off by default in the code, and what production has is not measured here. The portal side of exams and certificates is not measured here either. Video ids are pasted by hand. Four generations of the editor still sit in the engine file.

The state of an exam is not stored and it is not scheduled. It is computed when someone asks:

```python
# main.py :16184–16205 — as printed here, sha 8feb5e75cb3e1690… — the state of an exam is computed when it is read: no scheduled job
    open_n = 0
    passed = False
    not_pass_graded: list[int] = []
    for a in attempts:
        v = str(a.get("verdict") or "").strip().lower()
        if v == "pending":
            open_n = _academy_exam_int(a.get("n"), 0, 1, 10000) or len(attempts)
        elif v == "pass":
            passed = True
        elif v == "not_pass":
            not_pass_graded.append(int(a.get("graded_at") or 0))
    used = len(not_pass_graded)
    next_available_at = 0
    if passed:
        state = "passed"
    elif open_n:
        state = "pending_review"
    elif used >= attempts_initial:
        next_available_at = (max(not_pass_graded) if not_pass_graded else 0) + retry_wait_days * 86400
        state = "throttled" if now_epoch < next_available_at else "available"
    else:
        state = "available"
```

A certificate is approved in one transaction, and what it was issued with is frozen by hash:

```python
# main.py :18264–18284 — as printed here, sha 74037625d88c7057… — one transaction approves a certificate and freezes what it was issued with, by hash
    @firestore.transactional
    def _c2_approve_txn(transaction) -> None:
        outcome.clear()
        snap = ref.get(transaction=transaction)
        cur = (snap.to_dict() or {}) if snap.exists else None
        cst = _c2_cert_status_of(cur)
        if cst != "requested":
            outcome["error"] = cst
            return
        doc = dict(cur)
        doc.update({
            "status": "approved", "serial": serial, "issue_date": issue_date, "completion_date": completion,
            "requirement": {"lessons_done": req["lessons_done"], "lessons_total": req["lessons_total"], "exams": req["_snapshot"]},
            "template_version": tpl["version_id"], "template_sha256": str(tpl.get("sha256") or ""),
            "signature_version": sig["version_id"], "signature_sha256": str(sig.get("sha256") or ""),
            "decided_by": by, "decided_at": now, "build": C2_CERT_BUILD_TAG,
        })
        doc["record_sha"] = _c2_cert_record_sha(doc)
        doc["history"] = _c2_cert_history(cur.get("history"), "requested", "approved", by, now)
        transaction.set(ref, doc)
        outcome["doc"] = doc
```

## 8 · The paper archive (the “Check-ins” button)

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Ingest New Package | photos of the paper package of a day, read by AI, then a queue to confirm, then the archive | “Extract with AI”, a review, “Finalize & Archive” | Jul 2026 |
| Consecutivo check · Breaks report | the receipt numbers in order; the paper against the ledger | — | Jul 2026 |
| Active Book · Week | counts, payment rails, products sold, missing pictures, the totals of a day; a weekly CSV | — | Jul 2026 |

## 9 · The other desk

| Button or feature | What it does | How it is built | First recorded |
|---|---|---|---|
| Lifecycle | the structured-notes lab: the book of notes issued by banks, a field dictionary, the life-cycle table with fresh quotes, pending events | an event is approved or denied after a confirm, and the lab never stamps a note as called by itself. The pricing is done by a local C++ Monte Carlo engine, told in the README | Jul 2026 |

## 10 · The pattern of a god mode

A god mode is a setting the owner edits, instead of a value in the code. Most of them share this pattern. Appointment emails and product email reminders save directly, with an audit row; the barrier-reminders switch saves after a confirm and keeps only who changed it last; Barrier Rules saves directly behind a flag, and the form editor's dry run is on request.

- **One editable document for each lane.**
- **The constants in the code are the floor.** An invalid document leaves the constants standing. The read shows the value of each field and where it comes from, and the configuration in effect.
- **A dry run first.** A rehearsal whose fingerprint the confirm must carry, or a dry run that is the default; and a write flag on the server.
- **Forward only.** A version in force cannot be changed. Maps and templates are versioned before they are overwritten.
- **Honest unknowns.** What is not known is shown as not known.
- **Late answers are dropped,** and a double load is guarded.

## 11 · Not built, said plainly

- A button to read the server's logs: planned, with no record that it shipped.
- A mirror desk, from the card processor to the payouts to the bank: designed and prototyped, never built.
- Weekly goals for the business: a design only.
- A card reader: a study only.
- Expiry dates by lot, labels and printing: a wish.
- A time zone on every date of the admin: a wish.
- A team module for the admin, for more than one technician: **no longer in this list.** It went live on 2026-11-12 (README, section 4i), after this file was measured, and is not described here.
