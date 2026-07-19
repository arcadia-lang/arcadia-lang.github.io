# AGENTS.md

## Purpose

This repository contains the specification for **Arcadia**, a constructed language.

Arcadia prioritises:

1. Deterministic parsing.
2. Internal consistency.
3. Regularity over familiarity.
4. Semantic transparency.
5. Minimal exceptions.

When proposing changes, always optimise for these goals rather than natural-language realism.

---

# Repository Structure

The repository is organised by language.

Each top-level directory is named using an ISO 639 language code.

Examples:

- `en/`
- `es/`
- `el/`

Each language directory contains the complete documentation for that language.

Every language directory **must** contain a file named `LOCALE`.

`LOCALE` contains exactly one line containing the official locale identifier.

Examples:

- `en-GB`
- `es-ES`
- `el-GR`

The locale specified in `LOCALE` defines the spelling, grammar and stylistic conventions for every document beneath that directory.

Always follow the nearest `LOCALE` file when creating or editing documentation.

---

# Documentation Formatting

Documentation is optimised for Git history and translation.

Every sentence must occupy its own line.

Do not place multiple sentences on the same line.

Treat the sentence—not the paragraph—as the atomic unit of documentation.

Use British English whenever the active locale is `en-GB`.

---

# Design Philosophy

## Deterministic grammar

Every grammatical construction should have a single unambiguous parse.

Avoid introducing ambiguity unless it provides substantial expressive value.

## Regularity over naturalism

Natural languages are useful sources of inspiration, not design constraints.

Prefer consistency, simplicity and expressive power over typological realism.

Avoid suggestions based solely on:

- "this is what most languages do";
- "this feels more natural";
- "this sounds more familiar".

## Semantic-first design

Grammar should reflect semantic structure.

Verbs license semantic roles.

Cases encode semantic roles directly.

Avoid introducing concepts such as subject, object or grammatical pivot unless discussing other languages.

## Phrase-head principle

Every phrase has exactly one overt head.

Grammatical markers attach to the head while taking scope over the entire phrase.

Different lexical categories may realise those markers differently.

## Pivotless syntax

Arcadia has no grammatical pivot.

No participant is privileged.

Verb types define:

- licensed roles;
- mandatory roles;
- canonical ordering.

Cases identify participant roles directly.

## Productive morphology

Prefer productive derivation and inflection.

Generalise rules whenever possible.

Morphological exceptions are acceptable only when they intentionally preserve grammatical distinctions.

## Phonology

Default phonological rules may be overridden by morphology when preserving grammatical meaning.

---

# Documentation Style

Use concise technical prose.

Prefer normative wording:

- must;
- may;
- cannot.

Avoid speculative wording unless describing genuinely optional behaviour.

---

# Suggestions

When proposing changes:

1. Preserve internal consistency.
2. Remove unnecessary rules instead of adding new ones.
3. Generalise before introducing exceptions.
4. Keep the grammar deterministic.
5. Preserve parser friendliness.

The preferred solution is usually the one that eliminates an entire rule rather than adding another.
