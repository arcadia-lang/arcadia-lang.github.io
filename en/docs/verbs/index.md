# Verbs

In Arcadia, **verb type determines sentence structure**.

The verb functions as the structural core of the clause.
It determines:

- Which participant roles are licensed
- Which roles are mandatory or optional
- Which role is the default pivot
- How agreement and omission behave

Arcadia does **not** categorise verbs by transitivity.
Valency emerges from verb type and role structure, not from a transitive/intransitive distinction.

Verb types and their role structures are defined in **[types][type]**.

## Clause Structure

The default clause order is:

**Verb – Core Roles – Obliques**

Core roles and obliques may be reordered for discourse emphasis, poetic rhythm, or stylistic effect.

**Role assignment is never determined by word order.**
Roles must remain recoverable through morphology and verb type.

Arcadia is fully pro-drop.
Core roles may be omitted when recoverable from verbal morphology or discourse context.

## Verbal Morphology

Arcadia verbs encode grammatical information through a fixed suffix sequence.

The suffix template is:

**Root–T–M–A–P–N**

Where:

- **T (Tense)**: single vowel
- **M (Mood / Hypermood)**: one or two consonants
- **A (Aspect)**: vowel–consonant pair, or ∅ for zero aspect
- **P (Person)**: single vowel
- **N (Number)**: zero or one consonant

Each slot contains at most one morpheme.
Zero aspect is expressed by the absence of the aspect slot.

Detailed paradigms are provided in:

- [Mood][mood]
- [Tense][tense]
- [Aspect][aspect]
- [Person][person]

## Orientation and Role Selection

Arcadia uses **orientation prefixes** to select which role is treated as the pivot of the clause.

The default pivot is defined by verb type.
Orientation prefixes allow an alternative licensed role to become the pivot.

This mechanism:

- Avoids lexical verb pairs (e.g., buy/sell-type alternations)
- Enables omission of non-pivot roles
- Supports morphosyntactic alignment without duplicating roots

The full inventory and generation rules are defined in the **[verb generation guide][generation]**.

## Reflexivity and Reciprocity

Arcadia uses prefixes to mark **reflexive** and **reciprocal** constructions.

Prefix scope order is fixed:

**Reflexive / Reciprocal → Orientation → (other derivational prefixes) → Root**

The reflexive or reciprocal prefix is always closest to the verb root among prefixes.

Full forms and combinatorial rules are described in the **[verb generation guide][generation]**.

[mood]: ./mood.md
[tense]: ./tense.md
[aspect]: ./aspect.md
[person]: ./person.md
[type]: ./types.md
[generation]: ../generation/verbs.md
