# 05 — Multilingual Linguistic QA

## 📌 Project Overview

This case study demonstrates a multilingual **Linguistic Quality Assurance (LQA)** workflow for evaluating localized content across multiple target languages.

The objective is to apply a consistent evaluation framework while respecting the linguistic and cultural characteristics of each target market.

---

## 🎯 Objective

The purpose of this case study is to demonstrate how linguistic reviewers can evaluate multilingual content based on:

- Accuracy
- Fluency
- Terminology
- Grammar
- Localization
- Cultural appropriateness
- Style
- Severity

---

## 🌎 Languages Evaluated

| Language | Locale |
|---|---|
| Portuguese | Brazilian Portuguese (PT-BR) |
| Spanish | Spanish (ES) |
| Italian | Italian (IT) |
| French | French (FR) |
| German | German (DE) |

---

# 1. Source Content

### English Source

> Discover your personalized recommendations and find products you'll love.

This sentence was selected because it contains marketing language that may require adaptation across different languages.

---

# 2. Sample Localizations

## 🇧🇷 Brazilian Portuguese

> Descubra suas recomendações personalizadas e encontre produtos que você vai amar.

### QA Assessment

**Issue:** The phrase "que você vai amar" is understandable but slightly influenced by English marketing language.

### Recommended Version

> Descubra suas recomendações personalizadas e encontre produtos que combinam com você.

**Category:** Localization / Style

**Severity:** Minor

---

## 🇪🇸 Spanish

> Descubre tus recomendaciones personalizadas y encuentra productos que te encantarán.

### QA Assessment

The translation is natural and preserves the original marketing intent.

**Category:** —  
**Severity:** No Issue

---

## 🇮🇹 Italian

> Scopri i tuoi consigli personalizzati e trova prodotti che amerai.

### QA Assessment

The translation is understandable, but "consigli personalizzati" may not accurately reflect the product concept if "recommendations" refers to an algorithmic recommendation system.

### Recommended Version

> Scopri i tuoi suggerimenti personalizzati e trova i prodotti che fanno per te.

**Category:** Terminology / Localization

**Severity:** Minor

---

## 🇫🇷 French

> Découvrez vos recommandations personnalisées et trouvez des produits que vous allez adorer.

### QA Assessment

The translation is grammatically correct and natural.

However, "que vous allez adorer" creates a slightly more literal promotional structure.

### Recommended Version

> Découvrez vos recommandations personnalisées et trouvez des produits qui vous correspondent.

**Category:** Style / Localization

**Severity:** Minor

---

## 🇩🇪 German

> Entdecken Sie Ihre personalisierten Empfehlungen und finden Sie Produkte, die Sie lieben werden.

### QA Assessment

The translation is grammatically correct, but the phrase "die Sie lieben werden" can sound somewhat unnatural in German marketing copy.

### Recommended Version

> Entdecken Sie Ihre personalisierten Empfehlungen und finden Sie Produkte, die zu Ihnen passen.

**Category:** Localization / Style

**Severity:** Minor

---

# 3. Comparative LQA Matrix

| Language | Accuracy | Fluency | Terminology | Localization | Overall |
|---|---:|---:|---:|---:|---:|
| PT-BR | 5/5 | 4/5 | 5/5 | 4/5 | 18/20 |
| ES | 5/5 | 5/5 | 5/5 | 5/5 | 20/20 |
| IT | 4/5 | 4/5 | 4/5 | 4/5 | 16/20 |
| FR | 5/5 | 5/5 | 5/5 | 4/5 | 19/20 |
| DE | 5/5 | 4/5 | 5/5 | 4/5 | 18/20 |

---

# 4. Error Severity

## Critical

No critical issues identified.

## Major

No major issues identified.

## Minor

Several minor issues were identified involving:

- Literal marketing structures
- Terminology choices
- Naturalness
- Cultural adaptation
- Promotional tone

---

# 5. LQA Methodology

Each localization was reviewed using the same core framework.

### Step 1 — Source Analysis

Understand the meaning, context, audience, and intent of the original content.

### Step 2 — Linguistic Review

Evaluate grammar, syntax, spelling, and fluency.

### Step 3 — Terminology Review

Verify whether product-specific terminology follows approved terminology.

### Step 4 — Localization Review

Evaluate whether the content feels natural and appropriate for the target market.

### Step 5 — Severity Classification

Classify identified issues according to their impact on meaning and user experience.

### Step 6 — Correction

Provide a recommended localized version when necessary.

---

# 6. Cross-Language Findings

Although the same English sentence was used as the source, different languages required different types of adaptation.

This demonstrates an important principle in multilingual localization:

> **A consistent QA framework does not mean identical linguistic decisions.**

Each language has its own:

- Grammar
- Syntax
- Cultural conventions
- Marketing conventions
- Terminology
- Register
- Natural expressions

Therefore, LQA must balance **global consistency** with **local linguistic expertise**.

---

# 🏆 Final Assessment

The multilingual review identified primarily minor issues related to naturalness, terminology, and localization.

No critical or major errors were found.

The exercise demonstrates how a structured LQA framework can be applied across multiple languages while allowing reviewers to make language-specific decisions.

---

## Key Takeaway

> **Multilingual QA requires consistency in methodology, not uniformity in language.**
