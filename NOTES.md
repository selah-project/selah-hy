# NOTES — hy.v1 · The Selah Armenian Rendering

*Chair 62. The first Armenian-script chair, the third census polarity
(Armenian-home). Lit 2026-09-05 ~14:07 (e9aa7064), gate passed 14:36,
sealed 2026-09-05 ~23:20. Burn ~7.5h through ~2.9k verses/hour.*

## The seal

| Count | Value |
|---|---|
| Files | 23,213 (complete) |
| Յահվե (gloss seat) | 5,810 |
| Էլոհիմ (gloss seat) | 2,063 |
| ⟨את⟩-verses | 7,231 |
| Տէր/Տեր at a Name seat | **0** |
| Եհովա | **0** |
| NT-leak (Հիսուս/Քրիստոս/…) | **0** — sixth consecutive chair |
| Շեոլ at שאול seats | 55/55, no դժոխք |
| Aleph-tav audit | [0 0 0 0] at fixpoint |
| Token spine | ≡ en ≡ OSHB (consonantal), 0 diffs |

## The family shape

- **Տէր-ZERO from the first hour.** The Name seat held perfectly from
  round one — 0 Տեր in 6,825 opportunities, against every printed
  Armenian Bible. Third chair running where the erasure word never
  reached the seat.
- **Third census polarity held.** Armenian-home: Latin and Cyrillic
  both count as bleed, and both sealed to zero.
- **The Aramaic rails row worked.** אלה/אלהא → Էլահ/Էլահա applied
  from the bench (the kk lesson); Daniel and Ezra did not drift.
  Dan 3:12's יתהון carries ⟨את⟩ նրանց — the ninth chair for that verse.
- **The զ- trap pre-empted.** The rails ruled the Grabar object-marker
  *never*; a 4,436-token sweep found it held everywhere except two
  verses inside a classical-register drift block (Hos 8:6–7), which
  were re-rendered.
- **Յահվեն enclitic spectrum** — the full case system on an intact
  stem: Յահվեի 4,943 · Յահվեն 4,427 · bare 2,919 · Յահվեին 1,545 ·
  Յահվեից 206 · Յահվեով 60 · Յահվեում 7. Zero welds. This is the
  Armenian face of the case-suffix family ruling (now seven chairs:
  ro -ul, hu, kk, sr, hy -ը/-ն, ka -მ, rw noun-class).

## The cruxes

**The 405 alphabet.** Mashtots built the Armenian alphabet (405 AD)
to carry this text — the first sentence ever written in it was
Scripture. The Տէր erasure entered Armenian Scripture the same moment
the alphabet did: there was never an Armenian Bible before the
substitution. This chair is the first Armenian rendering where the
Name stands at its seats. Stated, not moralized.

**The spine plague.** The largest lookalike incident of any chair,
and the first in the token spine itself: Armenian letters written
into the *Hebrew surfaces* at 1,578-file scale (մ→מ ×695, հ→ה ×125,
լ→ל ×105, ր→ר ×103, ն→נ, բ→ב, վ→ו, ա→א, ո→ו, դ→ד, ի→י, շ→ש, տ→ת,
פ→պ), plus pointing marks leaked into surfaces, plus one verse
(Exod 28:37) with the whole spine transliterated into Armenian
letters. 1,436+ tokens restored deterministically against the en
spine; ~330 real deviations (rotations, respellings, fabricated
spine tokens — Josh 2:6 carried two fabricated את *tokens*) were
re-rendered or rebuilt en-aligned. **The census was blind to all of
it** — welds hide from whole-script counters. *Spine-diff-vs-en is
now a standing groove step*, and it caught an en-side fault too:
Exod 30:5 carried וצצפית (doubled צ) against OSHB's וצפית — fixed in
the en repo (c07a7ef78).

**The hooks-word family.** The curtain-hooks fault took its sixth
straight chair, and here it spread across the whole tabernacle
court: וגו / וקי / ושויהם / וגויהם fabricated for ווי / וויהם in
nine verses (Exod 26:37, 27:10, 27:11, 36:36, 38:10, 38:11, 38:12,
38:17, 38:19) — a fabricated gimel, a qof-for-vav, a shin insertion.
Every one restored against en. The double-vav hooks word is a
standing adversary.

**Batch register drift.** The classical/Grabar orthography arrived in
contiguous 3–4 verse runs (~15 of them; Hosea 8:5–8 the specimen
block — classical spelling + Western կը future + աստուած at an
אלהים seat + զ-, four rails in four verses). Re-rendered; the
residue converted deterministically (եւ→և, պէս→պես, մէջ→մեջ,
ութիւն→ություն, կը X→կX).

## Tekoa (Opus fork, read-only class-A)

Applied: 1 Kgs 8:15 (Տէր) title-weld; D1 seats Ps 33:12 (Էլոհիմը),
Isa 43:10 (Էլ), Deut 10:17 (inverted construct → «աստվածների Էլոհիմ
և տերերի Ադոնայ»), Ps 10:4 («Էլոհիմ չկա»); broken stems Յահվհ- in
1 Sam 2:12 + Jer 30:10–12 — **including the Name standing at Jacob's
seat twice** (Jer 30:10 יעקב glossed Յահվհ; Հակոբ restored);
Judg 21:7 Յահվեիւ→Յահվեով; 69 fabricated ⟨את⟩ flow markers stripped
in 57 verses (incl. Gen 1:5, 1:8, 22:8); 109 Armenian-declined
markers (⟨את⟩-ից/-ն/-ով) stripped in 66 files; 4 verses where the
rails' own word ⟨անկյունային⟩ leaked into scripture; Exod 38:25's
fabricated ⟨Աստված գիտի՝⟩; Ps 119:33's Latin acrostic label; empty
glosses filled (10 tokens, en-guided).

## Hand verses (the fable-5-hand ledger)

Jer 15:16 (fabricated marker in ואכלם) · Judg 2:21 (flow marker + NT
paren) · Gen 49:31 (⟨אտ⟩ weld) · Exod 32:19, Ezek 18:19 (⟨אתם⟩→en
shape) · Exod 1:17, 1 Chr 11:23, 2 Kgs 17:6 (gloss welds) ·
Exod 36:36 (spine gimel) · the nine hooks verses · Exod 36:35 +
Zech 14:4 (token-boundary rebuilds, en-aligned) · Micah 1:15 (3-token
plene) · pronoun-את class: Gen 12:13 (Սարայ), Eccl 7:22, Zech 9:11,
Ezek 22:24, Neh 9:6 (Դու) · Dan 3:12 (⟨את⟩ նրանց) · Tekoa's ~20 ·
the seal-trail ~15 (shalom-ն, Նатанաելի, Էլիյահուն, ⟨մאת⟩…).

## OPEN — pending Scott

- **Orthography as a chair-wide lens.** The chair is sealed reformed
  (Յահվե). Classical orthography (Յահւէ, եւ, ութիւն) is a coherent
  register a reader may want whole — a lens, like sr's digraphia,
  not a re-gloss.
- **⟨את⟩ flow-arithmetic**: 1,027 verses where the flow drops a
  marker the glosses carry + 106 the inverse (same open item as sr's
  ~1,185). The token rows are sound; the flow assembly is where it
  goes.
- **Paren-shadows**: 2,468 files (Մովսես 296, never bare) — between
  kk 1,644 and sr 3,705; one posture ruling covers all chairs.
- **Յահվեյի ×3** (Jer 3:10, 3:12, 2 Kgs 22:19) — parasitic յ in the
  genitive; broken stem or tolerable variant needs a native ear.
- **Rail gaps**: האדון (Mal 3:1) and Aramaic מרא (Dan 2:47) have no
  D1 row; both currently render Տեր at non-יהוה seats.
- **Capitalized generic Աստված** (Deut 4:7, 1 Sam 28:13) — the rail
  licences the generic seat lowercase; capitalization posture open.

*The alphabet was built to carry this text. Now it carries the Name.*
