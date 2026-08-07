# EdgeCases
Claude skills to assist in exploration of science and mathematic concepts in short stories, generating output as .epub books. Also includes stories generated in the series.

Short hard science fiction that teaches. Each book takes one concept from science, mathematics, or engineering and builds a story around it, with a twist that is load-bearing: understanding the ending and understanding the concept are the same act. If the twist could be transplanted onto a different topic unchanged, it gets rebuilt. Every book is a single .epub, readable in one sitting.

## The rules

- **One concept per book.** The reader should finish entertained and able to explain the idea to someone else.
- **Primary sources only.** The stories arrive as documents: post-mortems, museum catalogs, station logs, referee reports, recall notices, correspondence. Nobody lectures. A character or artifact explains only what it would plausibly explain to its in-world audience.
- **Real numbers.** Dates, rates, distances, and spectra are checked against reality where the story claims reality. Invented numbers are at least self-consistent, and the arithmetic is audited before packaging.
- **The seam is marked.** When fact and invention sit close together, a short "What's Real" afterword separates them and points at the actual papers.
- **Figures are earned.** Zero to two interior images per book, only when they would plausibly exist inside the fiction, always code-generated, grayscale-friendly for e-ink, captioned in-world.
- **One shelf, one look.** Covers share a design: dark slate, double frame, serif title, and a small in-world detail set in monospace on the accent line.
- **No em dashes.** House rule. Commas, colons, periods, parentheses.

## The shelf

| # | Title | Form | Concept |
|---|-------|------|---------|
| 1 | Not Blocking | Incident post-mortem | Von Neumann probes |
| 2 | The Gallery of Depth | Museum catalog | The digits of pi |
| 3 | Furnace Log | Station log | Quark-gluon plasma and glueballs |
| 4 | Reviewer 2 | Referee reports | Photonic computing |
| 5 | Recall Notice | Product recall, with appendices | Carbon nanotube chirality |
| 6 | The Ninth Nine | Correspondence | Nanotube purity and measurement |

A root-cause analysis in which every component works perfectly, and that is the disaster. An exhibition catalog from a civilization that can finally see. A time-stamped log kept beside the hottest matter anyone has made on purpose. Three rounds of peer review, and the question of what did the computing. A voluntary recall of 3.8 million smart bands, explained by the appendices. Twenty months of letters in which the purity keeps improving and the chips keep dying.

Books stand alone. Numbers 5 and 6 quietly share a universe, and each reorders the other.

## How a book gets made

The series is written collaboratively with Claude, using two custom skills:

- **concept-story** takes a topic and produces the story: it verifies the real facts first (searching current literature where the topic touches anything recent), sets private learning objectives that must each be earned inside a scene, pitches two or three premises in genuinely different narrative forms, then drafts to roughly 2,500 words within ten percent, scaling longer only when the concept demands it. Before packaging, it audits every number and confirms each learning objective has a home.
- **epub-builder** does the packaging: staged XHTML, the series cover, table of contents, metadata, and a validated EPUB 3.

The workflow from the reader's chair is three lines long: name a topic, pick a pitch, receive a book.

## Reading

Any EPUB 3 reader works: Kindle (via Send to Kindle), Kobo, Apple Books, Calibre. The books are one .epub each, named by slug. The figures and covers render cleanly on e-ink, which is where these are meant to live.
