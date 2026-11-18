# Junction 2026: MariaDB's Wikipedia challenge

[submissions.csv](submissions.csv) has one row per submission to the MariaDB Foundation's challenge at Junction 2026
(Espoo, 13–15 November 2026). See the [main README](../README.md#junction-2026) for the challenge and the winners.

The data comes from the Junction platform and from reading each team's repository on 16 November 2026. Two
repositories were not public. Some columns are our own judgement, not facts read from the code: Wikipedia angle,
primary user, delivery form, how Vector and SVT are combined, and MariaDB findings and friction.

## Columns

| Column | What |
|---|---|
| Project, Team, Punchline | As submitted on the Junction platform |
| Placement | 1st, 2nd or 3rd for the three winners |
| Wikipedia angle | Cross-language discrepancies, history and edit wars, or trustworthy answers with sources |
| Primary user, Delivery form | Who it is for, and whether it is a web app, a browser extension, a MediaWiki extension or local only |
| Source code | The team's repository |
| Video, Video status | The video link, given only when the team has made the video public |
| Demo, Demo status | The demo link, and whether it answered when we checked. Many ran on temporary servers. |
| Licence | The licence in the repository, if any |
| MariaDB version | The version stated in the repository or its Docker image |
| MariaDB datasets used, Other data used | Which of our datasets (S, M, L) the team used, and what else |
| How Vector and SVT are combined | For example both in one query, both separately, or mainly one of them |
| How MariaDB Vector is used, How system-versioned tables are used, Other MariaDB features | What the code does |
| MariaDB findings and friction | What the team measured or struggled with in MariaDB |
| Connector / driver, Languages, Runs on, Frameworks | The stack |
| LLMs in the product, LLM writes the answers?, Embedding model | The AI parts of the product |
| Partner tech | Other Junction partners' technology the team used |
| AI coding tools visible | AI coding tools seen in commits or instruction files |
| Commits, First commit, Last commit, Test files, Lines of code, README lines, Team size | Size and activity |
