# Arcadia

Arcadia is a highly expressive conlang built on **consistency and clarity**, eliminating exceptions entirely.

Its **innovative grammar and syntax**, coupled with extreme expressiveness and precision, make the learning curve steep.
However, because Arcadia is **logical and predictable**, with a **simple orthography and phonology**, a **small vocabulary** that expands through prefixes, mastery becomes easier once the fundamentals are learned.

---

## How to Use This Guide

To gain a foundational understanding of Arcadia's syntax, **follow this sequence**:

1. Read the **[Verbs Guide][verbs]**.
2. Review the **[Nouns Guide][nouns]**.
3. Explore the **[Articles Guide][articles]**.

The **[Vocabulary Guide][vocabulary]** serves as a reference, but all other sections should be read **in order as they appear in the navigation**.

---

## Syntax

Arcadia's syntax is designed to be **intuitive and flexible**.
Its standard word order is **Verb-Subject-Object (VSO)**, emphasizing **action over actor**.
However, as a **pro-drop language with case markings**, word order may shift **for emphasis**.

Arcadia follows the **Austronesian alignment**, but **not purely**; it incorporates elements from other **alignment systems** as well.

### **Understanding Syntax through Diagrams**

Traditional **nominative-accusative languages** follow an asymmetric structure.
In **active voice**, the **subject** is the main actor, the **verb** conveys action, the **direct object** receives the action, and the **indirect object** is the recipient.

```mermaid
graph LR
  A([**Subject**<br/>_John_]) --> B@{ shape: circle, label: "**Action**<br/>_gives_" }
  subgraph objects
    direction TB
    C([**Direct Object**<br/>_the ball_]) --> D([**Indirect Object**<br/>_to Mary_])
  end
  B --> objects
```

In **passive voice**, the **direct object** can be promoted, but the syntax undergoes major changes:

```mermaid
graph LR
  A([**Subject**<br/>_The ball_]) --> B@{ shape: circle, label: "**Action**<br/>_is given_" }
  subgraph recipients
    direction TB
    C([**Agent**<br/>_by John_]) --> D([**Indirect Object**<br/>_to Mary_])
  end
  B --> recipients
```

---

### **Arcadia's Symmetric Syntax**

Arcadia's syntax is **symmetric**, following the **Austronesian alignment**.

```mermaid
graph LR
  B@{ shape: circle, label: "**Action**<br/>_gives_" }
  subgraph participants
    direction TB
    A([**Actor**<br/>_John_])
    C([**Patient**<br/>_the ball_])
    D([**Recipient**<br/>_to Mary_])
  end
  B --> A
  B --> C
  B --> D
```

The **actor, patient, and recipient** can **all** act as the focus.

!!! note "Recipient"

    The recipient here refers to the **receiver of the patient**, **not the action** itself.

To fully understand Arcadia's **case system**, refer to the **[Noun Cases Guide][cases]**.
For verb transformations, see the **[Verb Generation Guide][generation]**.

---

## Subclauses

Arcadia allows an **infinite number of nested subclauses**, enabling highly expressive ideas.

- Subclauses use the **indicative mood**, meaning they **retain their own subjects**.
- **Tense is always relative** to the **narrator's perspective**, ensuring seamless narrative progression.

[articles]: ./determiners/articles.md
[verbs]: ./verbs/index.md
[nouns]: ./nouns/index.md
[vocabulary]: ./vocabulary/index.md
[cases]: ./nouns/case.md
[generation]: ./generation/verbs.md
