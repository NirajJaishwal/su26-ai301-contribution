# Contribution [#]: [Issue Title]

**Contribution Number:** 1
**Student:** Niraj Jaishwal  
**Issue:** (https://github.com/tqec/tqec/issues/718)
**Status:** [Phase I Complete]

---

## Why I Chose This Issue

I chose this because I wanted to get experience in open source and complete the issue successfully. So I found this issue to be a good first issue to work on. 

---

## Understanding the Issue

### Problem Description

The Documentation guide needs to be updated based on the documentation contributions. 

### Expected Behavior

A new section and a subsection should be added to the docs/contributor_guide.rst file.

### Current Behavior

The current documentation page doesn't have those sections.

### Affected Components
These components is affected as the section will be added here, and those sections will be created probably at the top.
tqec\docs\contributor_guide.rst


## Reproduction Process

### Environment Setup

As I am working in with the documentation part, I didn't have to stuggle a lot in reproducing the environment. I try to validate the exisitng component and it was giving some trouble which is yet to be figured out.

### Steps to Reproduce
1. Fork the Repo
2. Clone the Repo to the local IDE
3. Create a separate branch to work on
4. Create a venv environment to work

### Reproduction Evidence

- **Commit showing reproduction:** https://github.com/NirajJaishwal/tqec
- **Screenshots/logs:** (.venv) (base) PS C:\Users\niraj\Open Source Contribution\tqec> git branch
* docs/update-contributing-guide
  main
(.venv) (base) PS C:\Users\niraj\Open Source Contribution\tqec> 

- **My findings:** I was able to find out that the documentation needs to in the .rst file. So I should look at some examples of how to use the .rst file.

---

## Solution Approach

### Analysis
It is not a problem. It is adding a documentation guide for contributing.
[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]
I will add two sections to the contributor guide.rst file where I will implement section for adding a user guide page, adding a gallery example, using references in docs.

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** 
Contributer don't have clear guidance on how to add to the documentation. Specifically:
* How to add a new page to the user guide
* How to add an example to the docs
* How to use references/citations in docs?

**Match:** [What similar patterns/solutions exist in the codebase?]
1. User guide Page already uses .rst format, also uses .jupyter-execute for executable code blocks
2. Gallery example: already use .ipynb format
3. References: BibTex format, alphabetized by author last name

**Plan:** [Step-by-step implementation plan]
1. Add a new section to contributor_guide.rst placed after "installation procedure" and before "How to contribute"
2. Add three sections, adding a user guide page (explain .rst)
3. Include concrete code examples like the sample .rst user guide structure, sample BibTeX entry
4. Validite docs build

**Implement:** https://github.com/NirajJaishwal/tqec/tree/docs/update-contributing-guide

**Review:** yes

**Evaluate:** Reviewed formatting and structure for consistency with the existing contributor guide.
Verified the new content is valid reStructuredText.

---

## Testing Strategy

### Unit Tests
Not applicable
- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests
Not applicable for documentation
- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** https://github.com/tqec/tqec/pull/981

**PR Description:** [Draft or final PR description - much of the content above can be adapted]
Description
Adds a new "Contributing to documentation" section to docs/contributor_guide.rst with guidance on:

Adding pages to the user guide
Adding examples to the documentation gallery
Clearing notebook outputs before committing
Using references with sphinxcontrib-bibtex

Fixes #718

Please add the appropriate labels in the sidebar (e.g., bug fix, CI/CD, documentation).

How Has This Been Tested?
Reviewed formatting and structure for consistency with the existing contributor guide.
Verified the new content is valid reStructuredText.

Test Configuration:

Python version: 3.13
Operating system and system architecture: Windows 11
**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
