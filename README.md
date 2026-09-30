# Hi, I'm Dylan

I’m a student interested in **cybersecurity, defensive automation, and applied computer science**. I build small, reproducible experiments to understand how attacks appear in data, how defenders can detect them, and where security tools fail.

My work is intentionally student-scale: each project starts with a question, uses synthetic data, reports measurable results, and documents limitations instead of pretending to be a production security system.

## Featured projects

### [URL Security Lab](https://github.com/dylanfomo0-debug/URLSecurityLab)
**Question:** Can transparent lexical rules screen suspicious URLs?

A rule-based URL experiment using explainable features such as URL length, IP addresses, special characters, path depth, and suspicious words. The baseline reached **85.7% accuracy** on the synthetic dataset while still missing some suspicious examples.

### [Login Defense Lab](https://github.com/dylanfomo0-debug/LoginDefenseLab)
**Question:** How easily can a rule-based login detector be evaded?

Generates normal behavior, brute-force attempts, password spraying, night-time attacks, and slow-evasion scenarios. The key finding is that fast attacks are easier to detect than attacks deliberately kept below rate thresholds.

### [Password Security Lab](https://github.com/dylanfomo0-debug/PasswordSecurityLab)
**Question:** Does password complexity predict resistance to simple guessing strategies?

A safe experiment using only synthetic passwords. It compares dictionary, pattern-based, and bounded brute-force strategies while discussing why ordinary SHA-256 is not appropriate for production password storage.

### [Log Integrity Lab](https://github.com/dylanfomo0-debug/LogIntegrityLab)
**Question:** Can security logs reveal controlled tampering?

Creates synthetic authentication logs, injects duplicate events, timestamp changes, missing entries, unknown users, and new source IPs, then measures which checks can identify the changes.

## Core skills and technologies

- **Languages:** Python, SQL fundamentals, Markdown
- **Security:** anomaly detection, log analysis, URL analysis, password-security concepts, defensive experimentation
- **Engineering:** CSV data pipelines, deterministic simulations, command-line tools, unit testing, reproducible documentation
- **Data and reasoning:** feature design, confusion-matrix thinking, false positives/negatives, experiment design, limitations analysis
- **Tools:** Git, GitHub, GitHub CLI, Linux, basic visualization and technical writing

## Community and learning

- Participate in **CS club activities**
- Experience as a **founder**
- Attend and learn from **security conferences**
- Continue exploring how defensive systems behave under unusual or adversarial conditions

## What I’m exploring next

- Better evaluation with larger licensed datasets
- Time-based testing to reduce data leakage
- More realistic password-hashing comparisons
- Threshold tuning and false-positive analysis
- Small dashboards that make security findings easier to understand

> My goal is not only to build tools that detect suspicious behavior, but also to understand what those tools miss and why.
