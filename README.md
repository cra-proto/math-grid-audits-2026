# Math grid audits

*description of the project*

**Timeframe** 2026-03-17 - 2026-06-23

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/math-grid-audits-2026](https://cra-proto.github.io/math-grid-audits-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-31

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Forms and publications - CRA)
    node4(Canada Revenue Agency publications listed by number)
    node5(T4012 T2 Corporation - Income Tax Guide 2024)
    node6(T2 Corporation – Income Tax Guide – Chapter 2: Page 2 of the T2 return)
    node1 --x node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node5 --x node6
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/forms-publications.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/forms-publications/publications.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/t4012.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/t4012/t2-corporation-income-tax-guide-chapter-2-page-2-t2-return.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node6 inscope
```
