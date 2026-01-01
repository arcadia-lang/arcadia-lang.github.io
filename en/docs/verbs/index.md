# Verbs

In Arcadia, verb type determines sentence structure.
The verb determines word order and conveys extensive grammatical information through **suffixes**, integrating **[mood][mood], [tense][tense], [aspect][aspect], and [person][person] distinctions**.

Arcadia does not categorize verbs by **transitivity**; instead, it distinguishes five core **verb types**:

- [Stative verbs](#stative-verbs)
- [Possessive verbs](#possessive-verbs)
- [Experiential verbs](#experiential-verbs)
- [Cognitive verbs](#cognitive-verbs)
- [Action verbs](#action-verbs)

## Stative verbs { #stative-verbs }

Stative verbs describe **states**, **properties**, **locations**, **relationships**, **existence**, or **natural phenomena**.
They can be either static (e.g., _"The sky is blue"_, _"My friend is sick"_, _"I am here"_) or mutating (e.g., _"The ice is melting"_, _"The flowers are blooming"_, _"The boy entered the classroom"_).

### Syntax

For static stative verbs, the syntax is **Verb - Entity - State**.
For mutating stative verbs, the syntax is **Verb - Entity - Origin - Destination**.

### Case marking

- **Entity:** Absolutive case (optional, default pivot).
- **State:** Locative case, agreeing in number with the entity.
- **Source:** Allative case (optional).
- **Result:** Ablative case (optional).

### Pivot

- The **entity** is the default pivot.
- Verbs without an entity (predominantly the weather verbs), they may optionally lack a pivot, in which case, they **do not take personal suffixes**.

### Examples

- _nivav._:
    - It's snowing.

- _pluvav._:
    - It's raining.

- _dormavi._:
    - You're sleeping.

- _save la portis sanguadhi._:
    - The door is red.

- _save este dias lungi._:
    - This day is long.

## Possessive Verbs { #possessive-verbs }

Possessive verbs describe **possession**, **trade**, or **transfer**.
They can be either static (e.g., _"I have a hand"_, _"I have a car"_) or transfer (e.g., _"I gave her my book"_, _"I sold my car to John for money"_).

### Syntax

The syntax is **Verb - Owner - Asset**.
The syntax is **Verb - Donor - Recipient - Asset - Price**.

### Case marking

- **Owner:** Nominative case (default pivot).
- **Possession:** Accusative case.
- **Recipient:** Dative case (optional).
- **Price:** Ablative case (optional).

### Pivot

- The **entity** is the default pivot.
- Verbs without an entity (predominantly the weather verbs), they may optionally lack a pivot, in which case, they **do not take personal suffixes**.

### Examples

- _nivav._:
    - It's snowing.

- _pluvav._:
    - It's raining.

- _dormavi._:
    - You're sleeping.

- _save la portis sanguadhi._:
    - The door is red.

- _save este dias lungi._:
    - This day is long.

## Experiential Verbs { #experiential-verbs }

Experiential verbs describe **preferences, sensations, or emotions** (e.g., _"I like apples"_, _"I feel cold"_, _"My foot itches"_).

### Syntax

**Verb – Experiencer – Stimulus**

### Pivot

- **Default focus:** **Experiencer**.
- **Unfocused experiencer:** **Absolutive case**.
- **Unfocused stimulus:** **Thematic case**.

### Examples

- _audavo las avisath._:
    - I'm hearing the birds.

## Cognitive Verbs { #cognitive-verbs }

Experiential verbs describe **preferences, sensations, or emotions** (e.g., _"I know mathematics"_, _"I think of you"_, _"He dreamt of a simple life"_).

### Syntax

**Verb – Thinker – Content**

## Action Verbs { #action-verbs }

Action verbs describe **actions**, **communication**, **interaction**, or **events**. (e.g., _"The birds are singing"_, _"I sold a book to Adam"_, _"She wrote a letter"_).

### Syntax

**Verb – Actor – Patient – Recipient**

### Pivot

- **Default focus:** **Actor**.
- **Unfocused actor:** **Ergative case**.
- **Unfocused patient:** **Accusative case**.
- **Unfocused recipient:** **Dative case**.

!!! note "Focus"

    Focus can be omitted, particularly for the **first, second, and fourth persons**.

### Examples

- _saltove la pueris._:
    - The child will jump.

- _legavo la librion._:
    - I'm reading the book.

- _donivo la librion marial._:
    - I'm giving the book to Maria.

## Focus Shifting

Arcadia allows **focus shifting** for experience and action verbs, achieved by modifying:

1. **The case of the focused argument**.
2. **The verb form**, as detailed in the **[verb generation guide][generation]**.

!!! note "Valid Focus Shifts"

    Apart from the basic focus, Arcadia allows following additional focus options:

    -   **Stimulus** for experiential verbs
    -   **Patient** for action verbs
    -   **Recipient** for action verbs
    -   **Instrument**
    -   **Beneficiary**

## Reflexivity and Reciprocity

Arcadia uses **prefixes** to indicate **reflexive** and **reciprocal** actions.
The reflexivity prefix is **applied first**, followed by the **focus-shifting prefix**, ensuring the reflexive element remains **closest to the verb root**.

The full set of reflexive and reciprocal markers is detailed in the **[verb generation guide][generation]**.

[mood]: ./mood.md
[tense]: ./tense.md
[aspect]: ./aspect.md
[person]: ./person.md
[generation]: ../generation/verbs.md
