---

title: Methodology
layout: col-document-adv
tags: Code Review Guide draft
document: Code Review Guide 3.0
author:
contributors:
order: 
altfooter: true

---
# Technical Reference For Secure Code Review

Here, the guide will have references to common vulnerabilities and technical controls.
Common vulnerabilities are flaws such as SQL injections, Cross-site-scripting, etc.
Such vulnerabilities are covered by OWASP Top 10, and this technical reference will cover the issues following (OWASP top 10 2021)[https://owasp.org/Top10/], which is the most recent list as of writing.

In addition to vulnerabilities, there will be suggestions for important controls and aspects within authentication, authorization, logging, and information leakage, among others.

This section can be used to learn impotant aspects of various controls, and as on-the-job reference when conducting secure code reviews.

This guide does not prescribe a catch-all process for performing a security code review. Rather, it provides guidance for how the effort should be structured and executed. The guide also focuses on the mechanics of reviewing code for certain vulnerabilities.

Manual secure code review provides insight into the "real risk" associated with insecure code. This contextual, white-box approach is the single most important value. A human reviewer can understand the relevance of a bug or vulnerability and code. Context requires human understanding of what is being assessed. With appropriate context we can make a serious risk estmate that accounts for both the likelyhood of attack and the business impact of a breach.
Correct categorization of vulnerabilities helps with priority of remediation and fixing the right things, as opposed to wasting time fixing everything.

## Why Code Has Vulnerabilities
(key sentences)
- Lack of education, from school and job training.
- Lack of time, stressed developers may not have time to think about secure coding and just "get it done". In addition, not enough time to test and fuzz the software properly.
- Vendors not encouraged to spend extra effort to produce secure code due to "black box" software for the consumers. Customers generally not caring about good code and insecure code.


