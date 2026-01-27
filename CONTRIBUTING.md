# Contributing to Openwater Patents

Thank you for helping us maintain an accurate and transparent patent portfolio listing. This repository serves as the public record of Openwater's patent filings and the Patent Pledge that governs their use.

---

## How You Can Help

### 1. Report Errors in Patent Data

If you find inaccuracies in the patent listing, please open an issue. Common errors to report:

| Error Type | Example |
|------------|---------|
| Incorrect patent/application number | "US 9,730,649 should be US 9,730,694" |
| Wrong status | "Patent shows as Pending but was granted on [date]" |
| Incorrect dates | "Filing date listed as Sep 2016 but USPTO shows Sep 2017" |
| Missing patents | "Patent US X,XXX,XXX is assigned to Open Water Internet Inc. but not listed" |
| Broken links | "Link to patent page returns 404" |

**How to report:**
1. Go to [Issues](https://github.com/OpenwaterHealth/openwater-patents/issues)
2. Click "New Issue"
3. Use a clear title: `[Data Error] US Patent 9,730,649 - Incorrect issue date`
4. Include:
   - Which patent/application is affected
   - What the current (incorrect) value is
   - What the correct value should be
   - Source for the correct information (USPTO link, EPO link, etc.)

### 2. Report Status Changes

Patent statuses change over time. If you notice a status update, let us know:

- **Pending → Issued**: A patent application was granted
- **Pending → Abandoned**: An application was abandoned
- **Published**: A new application was published

Include the official source (USPTO PAIR, EPO Register, etc.) when reporting.

### 3. Ask Clarifying Questions

If something in the patent listing or Patent Pledge is unclear, open an issue with the `question` label. We'll do our best to clarify or improve the documentation.

---

## What This Repository Does NOT Cover

### ❌ Legal Advice
We cannot provide legal advice about:
- Whether your use case is covered by the Patent Pledge
- Patent infringement questions
- Interpretation of specific patent claims

**Instead**: Consult with a qualified patent attorney.

### ❌ General Openwater Questions
For questions not related to patents:
- **Technical questions**: See the [Openwater Wiki](https://wiki.openwater.health)
- **Product questions**: Visit [openwater.health](https://www.openwater.health)
- **Community discussions**: Join the [Openwater Discord](https://discord.com/channels/1187061250379751475/1187061250895663206)

### ❌ Patent Document Requests
Patent documents (PDFs) are not stored in this repository. Access them via:
- [Openwater Patents Page](https://www.openwater.health/patents) (Google Drive links)
- [USPTO Patent Center](https://patentcenter.uspto.gov/)
- [EPO Espacenet](https://worldwide.espacenet.com/)
- [WIPO Patentscope](https://patentscope.wipo.int/)

---

## Issue Templates

### Data Error Template

```markdown
**Patent/Application**: [e.g., US 9,730,649]
**Field with Error**: [e.g., Issue Date]
**Current Value**: [e.g., Aug 15, 2018]
**Correct Value**: [e.g., Aug 15, 2017]
**Source**: [e.g., https://patentcenter.uspto.gov/...]
```

### Status Update Template

```markdown
**Patent/Application**: [e.g., US 18/122,124]
**Previous Status**: Pending
**New Status**: Issued
**Effective Date**: [e.g., Jan 15, 2026]
**New Patent Number** (if issued): [e.g., US 12,345,678]
**Source**: [link to official record]
```

### Question Template

```markdown
**Section/Patent**: [which part of the README or which patent]
**Question**: [your question]
**Context**: [why you're asking, what you're trying to understand]
```

---

## How Updates Are Made

1. **Issues are reviewed** by the Openwater team
2. **Verified against official sources** (USPTO, EPO, WIPO, CNIPA)
3. **README is updated** with corrections
4. **Issue is closed** with a reference to the commit

We aim to review issues within 2 weeks. Complex questions about the Patent Pledge may take longer and may require input from legal counsel.

---

## Code of Conduct

This repository follows the [Openwater Code of Conduct](https://github.com/OpenwaterHealth/.github/blob/main/CODE_OF_CONDUCT.md). Please be respectful and constructive in all interactions.

---

## Contact

- **Patent-related issues**: Open an issue in this repository
- **Patent Pledge questions**: Review the [Openwater Patent Pledge](Openwater%20Patent%20Pledge.pdf) first, then open an issue if unclear
- **General inquiries**: [openwater.health/contact](https://www.openwater.health/contact)

---

*Thank you for helping us maintain transparency in our patent portfolio!*
