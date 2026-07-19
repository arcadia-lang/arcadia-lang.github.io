# Verbs

Arcadian verbs encode grammatical information through a fixed and ordered morphological structure.

This section describes the **forms of verbs**: person, tense, aspect, mood, and the full verbal template.
Clause structure, participant roles, and verb types are described in the [Syntax guide][syntax] and the [Verb Types][verb-types] section.

## Verbal Morphology

Arcadia verbs encode grammatical information through a fixed suffix sequence.

The suffix template is:

**Root–T–M–A–P/N**

Where:

- **T (Tense)**: single vowel
- **M (Mood / Hypermood)**: one or two consonants
- **A (Aspect)**: vowel–consonant pair, or ∅ for zero aspect
- **P/N (Person/Number)**: one or two syllables.

Each slot contains at most one morpheme.
Zero aspect is expressed by the absence of the aspect slot.

Detailed paradigms are provided in:

- [Person][person]
- [Tense][tense]
- [Aspect][aspect]
- [Mood][mood]
- [Conjugation][conjugation]

## Verb Type and Agreement

Verb type determines which participant roles are licensed by the verb.
It also determines which roles are mandatory or optional, and how agreement and omission behave.

Arcadia does not categorise verbs by transitivity.
Valency emerges from verb type and role structure, not from a transitive/intransitive distinction.

The role structures associated with each verb type are defined in [Verb Types][verb-types].

## Prefix Domain

Arcadia uses prefixes to mark role- and valency-related operations, including reflexive and reciprocal constructions.

Because Arcadia is pivotless, no prefix is needed to promote a participant: each role is identified directly through semantic case marking.
This design:

- avoids lexical verb pairs such as buy/sell-type alternations;
- enables omission of any recoverable role;
- supports the role-based alignment without duplicating roots.

Prefix scope order is currently defined as:

**Reflexive / Reciprocal → other derivational prefixes → Root**

The reflexive or reciprocal marker has the tightest role-changing scope among prefixes.
Full prefix inventories and generation rules are described in the [verb word-formation guide][verb-generation].

[syntax]: ../../03-syntax/00-index.md
[verb-types]: ../../03-syntax/02-verb-types.md
[person]: ./01-person.md
[tense]: ./02-tense.md
[aspect]: ./03-aspect.md
[mood]: ./04-mood.md
[conjugation]: ./05-conjugation.md
[verb-generation]: ../../02-vocabulary/02-word-formation/01-verbs.md
