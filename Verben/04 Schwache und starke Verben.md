---
level: A2
tags:
  - verben
  - grammatik
---

# Schwache und starke Verben — the compute/memorize split

Building any past tense requires knowing which of two classes a verb belongs to; the two classes form
their past forms differently. The same split exists in English:

- **walk → walked → walked** — regular, predictable. Add *-ed*. (German: **weak**.)
- **sing → sang → sung** — the vowel changes and is memorized. (German: **strong**.)

German works the same way. One class is **computed**, the other is **hardcoded**.

---

## Weak = compute (the default)

Weak verbs **keep their stem** and mark the past with a **-t-**. The rule is invariant, so the forms
are derived, not stored:

> **Präteritum** (simple past): stem **+ te** → machen → er **machte**
> **Partizip II** (past participle): **ge-** + stem + **-t** → machen → ge**macht**

This is the **open, growing** class. New verbs (*googeln, downloaden*) are weak by default. Weak is a
formula, not a list.

---

## Strong = hardcode (the closed list)

Strong verbs **change their stem vowel** (the technical name is *ablaut*), and the participle ends in
**-en**, not -t:

> **Präteritum**: vowel change, **no -te** → singen → er **sang**
> **Partizip II**: **ge-** + (often new vowel) + **-en** → singen → ge**sungen**

The vowel is not computable — *singen* takes *a*, *finden* takes *fand/gefunden*, *gehen* takes
*ging/gegangen*. This is **per-verb data**, the verb equivalent of a noun's gender. There are roughly
**200** of them, and they are the most common verbs in the language, so they recur constantly.

For this reason the word list stores the **principal parts** — infinitive → Präteritum →
Partizip II — as the verb's triple. That is the unguessable data; everything else is computed from
it. → [[Verben 001-100]]

---

## Side by side

| | weak (compute) | strong (hardcode) |
| ------------- | -------------- | ----------------- |
| **stem vowel** | unchanged | changes (ablaut) |
| **Präteritum** | stem **+ te** (machte) | vowel change, no -te (sang) |
| **Partizip II** | ge + stem + **t** (gemacht) | ge + stem + **en** (gesungen) |
| **the class** | open, default, infinite | closed, ~200, high-frequency |

---

## Ablaut patterns

Strong verbs are not 200 unrelated facts — they fall into **vowel-pattern families**. Identifying the
family yields several verbs at once:

- **ei → ie → ie**: bleiben → blieb → geblieben · schreiben → schrieb → geschrieben
- **i → a → u**: finden → fand → gefunden · trinken → trank → getrunken · singen → sang → gesungen
- **ie → o → o**: fliegen → flog → geflogen · ziehen → zog → gezogen

They are still memorized, but by family rather than individually.

---

## Mixed verbs

A small, closed group combines the **strong vowel change** with the **weak -t- ending**. The full
list is short:

| infinitive | Präteritum | Partizip II | English |
| ---------- | ---------- | ----------- | ------- |
| denken | **dachte** | gedacht | think |
| bringen | **brachte** | gebracht | bring |
| kennen | **kannte** | gekannt | know (be familiar with) |
| wissen | **wusste** | gewusst | know (a fact) |

---

The two past tenses are two ways of using these forms: the spoken past ([[05 Perfekt]]) and the
written past ([[06 Präteritum]]).
