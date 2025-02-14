# Contributing to Arcadia

Thank you for your interest in contributing to Arcadia!
We welcome contributions that align with Arcadia's linguistic framework and philosophy.

## Guidelines for Contributions

### **1. Structure & Formatting**

- All documentation is in **markdown** and uses [Material for MkDocs][mkdocs-material].
- Readability is **paramount**; this guide is for humans, and we love consistency:
    - Consistency within this project is important.
    - Consistency within one markdown file is more important.
    - Knowing when to break consistency is the most important.
- All _markdown_, _yaml_, _css_ files should be formatted using [prettier].

### **2. Linguistic Contributions**

- New **vocabulary** proposals must adhere to Arcadia's phonological rules.
- **Grammar** refinements should maintain consistency with existing syntax.

### **3. Technical Contributions**

- All **scripts** should be well-commented and optimised for efficiency.
- **Git commits** should be atomic, with clear and descriptive commit messages.
    - If adding a new translation, it's expected to do all the translations in one commit.

### **4. Translation Contributions**

- All translations should be **faithful to the original text**.
- Currently, we use [pysetta], even though it's still in alpha.

## How to Contribute

### **1. Fork & Clone**

First, fork the repository and clone it locally:

```bash
git clone git@github.com:arcadia-lang/arcadia-lang.github.io.git arcadia-lang
cd arcadia-lang
```

### **2. Branch Naming**

Use **clear branch names** to indicate the purpose of the update:

- `orthography/punctuation/new-marks`
- `grammar/nouns/declension-update`

### **3. Pull Requests**

When submitting a PR:

- Provide a **clear description** of the changes.
- Reference related issues using `Closes #issue-number`.
- Ensure all updates adhere to Arcadia's linguistic framework.

For major contributions, **discussion in the issues tab is encouraged** before submission.

## Code of Conduct

All contributors are expected to follow Arcadia's Code of Conduct.
Please maintain respectful and constructive communication in all discussions and submissions.

[mkdocs-material]: https://squidfunk.github.io/mkdocs-material/
[prettier]: https://prettier.io/
[pysetta]: https://github.com/spapanik/pysetta
