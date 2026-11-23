# Junction 2026: MariaDB's Wikipedia challenge

At [Junction 2026](https://2026.hackjunction.com/) in Espoo, Finland, on 13–15 November 2026, the MariaDB Foundation
hosted **MariaDB's Wikipedia challenge**: build the tools Wikipedia is missing, using MariaDB Vector, system-versioned
tables, or both. 36 teams submitted a project. The winners were:

1. [Janus](https://github.com/ayaanjamil/janus), by Saunan Pojat: A browser extension that marks where Wikipedia's
   language editions disagree, right in the article, and ranks the articles that most need attention.
2. [Language Mirror](https://github.com/silvekoski/languagemirror), by Bob the Builders: Compares how every language
   edition tells the same story, and how that has changed over the years, with vector search on system-versioned tables.
3. [Ghosts of Wikipedia](https://github.com/salomeshioshvili/ghosts_of_wikipedia), by Chrysalis: Brings deleted
   sentences back to life, searchable by meaning and traceable through time.

## The other 33 submissions

The same list, with a short comment on each, is at the end of the [blog post](https://mariadb.org/junction-2026/).

### Where the language editions disagree

- [Better-Wikipedia (FR)](https://github.com/Thomas-Sks/muisti), by Para-Celsus: Aligns passages across Finnish, Swedish
  and English to find contradictions and gaps.
- [Consensus](https://github.com/remeseeli/Consensus), by MEBA-data: A browser extension and MediaWiki integration that
  compares facts across editions.
- [Midas' Machine](https://github.com/jppf22/one-verifiable-record), by Midas' Machine: Matches claims across languages
  through Wikidata and vector distance, and spots verdicts that have gone stale.
- [Parallax](https://github.com/timkicker/attention-is-all-we-have/tree/main/parallax), by Attention Is All We Have:
  Shows how seven Wikipedias write the same article differently. ([video](https://youtu.be/eeRs_a-xHF0))
- [Parallax](https://github.com/13shreyansh/parallax), by The CS Guy: Finds cross-language disagreements and claims that
  their sources do not support. ([video](https://vimeo.com/1246955728))
- [Ryyppyton](https://github.com/JUSSI-G/Junction26), by Ryyppyton: Aligns sentences across Finnish, Swedish and
  English, using application-time and system-time periods together.
- [Second Opinion](https://github.com/TheShoutingParrot/second-opinion), by Northbound Dispatch: Measures how each
  edition frames an event, and shows only Wikipedia's own words. ([video](https://youtu.be/G_jkX81Tg10))
- [Since When](https://github.com/KatalystSoftware/junction-2026/tree/main/projects/since-when), by Katalyst: Finds the
  day an edition changed its wording.
- [Wiki Check](https://github.com/Vasuuu641/WikiCheck), by Guardians of the Moonlight: Catches contradictions, missing
  context and shifts in stance in one click.
- [WikiCross](https://github.com/ardubev16/junction2026), by WikiCross: Pairs passages across up to 66 language editions
  and measures their framing in SQL.

### Edit history and edit wars

- [10X](https://github.com/oskrim/junction26-mariadb), by 10X: A reader that replays how an article was written, edit
  war by edit war, with hybrid search over all Finnish articles. ([video](https://www.youtube.com/watch?v=l9lJ2c_cDFM))
- [AMPersand of Truth](https://github.com/Junction2026-AMPersandOfTruth/AmpersandOfTruth), by AMPersand of Truth: Finds
  the articles on a topic with vector search and analyses editing patterns with window functions.
- Dioptase, by Dioptase (code not public): Explains an article through its full revision history.
- [Progresful WikiLens](https://github.com/progresful/wikilens), by Progresful: Matches a question to every wording an
  article ever had. ([video](https://youtu.be/wZkZb7I90Po))
- [Rabbit Hole](https://github.com/gabrieledigilio/rabbithole), by Risorgenza: Keeps the history of every link, and
  suggests links that were never made.
- [TimeProof](https://github.com/LeopoldPichonneau/Junction2026), by ENLMe: Shows who is rewriting history on
  Wikipedia, when and how, with the evidence.
- [Wiki The Truth](https://github.com/Juho-Korhonen/Staticvoid), by Staticvoid: Detects opinionated rhetoric, vandalism
  and suspicious edits in an article's history. ([video](https://youtu.be/w35uU2zS9Y4))
- [wikilens](https://github.com/sebastiansalin/wikilens), by Strongest-Link: Shows where editors disagree and how
  editing patterns change over time.
- [WikiMemory](https://github.com/Pbi-with-love/WikiGoldentime-Junction2026), by ByteMe: Ask a question and see how its
  answer changed. ([video](https://www.youtube.com/watch?v=OPltgd_falM))
- [Wikipedia Time Machine](https://github.com/joeng03/wiki-time-machine/tree/feature/wiki-time-machine), by junctional
  programming: A MediaWiki extension that shows what Wikipedia said then, using bitemporal tables.
- [WikiPilot](https://github.com/PrahasHegde/wiki_pilot_junction_2026), by Hackoholics: Reveals the debate behind an
  article, with old history in an S3 engine cold tier. ([video](https://www.youtube.com/watch?v=Cx7-aBqLoCk))

### Trustworthy answers with sources

- Atlas, by Champions (code not public): Makes Wikipedia's history searchable by meaning.
- D&D – Palimpsest, by D&D (code not public): Answers questions about Wikipedia as of any moment in time.
- [Fact Checker Extension](https://github.com/Eetu-s/wikipedia-factcheck-extension-junction-26), by Klausde by
  Mustropic: Highlight any claim on any web page and get a verdict backed by Wikipedia passages.
- [Hindsight](https://github.com/skarwech/hindsight), by SCAN4x: Rebuilds Finnish Wikipedia articles exactly as they
  stood on any date.
- [Kerros](https://github.com/trietle145/kerros), by Lake Bandits: Answers questions about Finnish history in any
  language, citing the exact revision.
- [Lähde](https://github.com/Piexrre/lahde-wiki), by Maito Juoma Technologies: A low-carbon research assistant that
  answers from Finnish Wikipedia.
- [Quackers](https://github.com/Abhijay25/Palimpsest), by Quackers: Makes Wikipedia easier to explore, verify and trust,
  built into MediaWiki instances of its own.
- [Sourced & Dated](https://github.com/thinhkieu725/sourced-n-dated), by Tampere Titans: Shows how settled each fact is,
  with badges from 20 years of edits. ([video](https://youtu.be/6VNbBP5Uiq8))
- [WikiGuardian](https://github.com/ELNAUL99/WikiGuardian), by ToTheMoon: Checks a proposed edit against what Wikipedia
  already knows.
- [WikiLens](https://github.com/petteri9292/Junction_2026), by ASD: Connects generated explanations to passages from all
  of Finnish Wikipedia.
- [Wikipedia Through Time](https://github.com/KowaloskiX/wikipedia-through-time), by ScoobaNi: Ask Finnish Wikipedia
  anything as it stood on any day since 2003. ([video](https://www.youtube.com/watch?v=zIp27rPViH8))
- [WikiSnitch](https://github.com/DevBytAmir/WikiSnitch), by Brainflow: Tells you whether a Wikipedia sentence has stood
  for ten years or was rewritten last week. ([video](https://youtu.be/PX3RAW2VvDY))

## submissions.csv

[submissions.csv](submissions.csv) has one row per submission. The data comes from the Junction platform and from
reading each team's repository on 16 November 2026. Two repositories were not public. Some columns are our own judgement, not facts read from the code: Wikipedia angle,
primary user, delivery form, how Vector and SVT are combined, and MariaDB findings and friction.

### Columns

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
