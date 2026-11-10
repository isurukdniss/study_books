# Database Internals

LLM-friendly Markdown extracted from the source PDF. Files follow the PDF's embedded outline,
retain PDF-page provenance comments, and link extracted figures from `assets/`.

## Sections

| Section | PDF pages | Markdown | Characters |
|---|---:|---|---:|
| Front Matter | 1-5 | [00-front-matter.md](00-front-matter.md) | 2,459 |
| Preface | 6-18 | [00-preface.md](00-preface.md) | 15,661 |
| I. Storage Engines | 19-26 | [part-01-storage-engines.md](part-01-storage-engines.md) | 13,643 |
| 1. Introduction and Overview | 27-55 | [chapter-01-introduction-and-overview.md](chapter-01-introduction-and-overview.md) | 35,762 |
| 2. B-Tree Basics | 56-85 | [chapter-02-b-tree-basics.md](chapter-02-b-tree-basics.md) | 35,304 |
| 3. File Formats | 86-110 | [chapter-03-file-formats.md](chapter-03-file-formats.md) | 32,629 |
| 4. Implementing B-Trees | 111-140 | [chapter-04-implementing-b-trees.md](chapter-04-implementing-b-trees.md) | 32,216 |
| 5. Transaction Processing and Recovery | 141-189 | [chapter-05-transaction-processing-and-recovery.md](chapter-05-transaction-processing-and-recovery.md) | 72,665 |
| 6. B-Tree Variants | 190-219 | [chapter-06-b-tree-variants.md](chapter-06-b-tree-variants.md) | 36,199 |
| 7. Log-Structured Storage | 220-271 | [chapter-07-log-structured-storage.md](chapter-07-log-structured-storage.md) | 72,999 |
| Part I Conclusion | 272-274 | [part-01-conclusion.md](part-01-conclusion.md) | 3,842 |
| II. Distributed Systems | 275-277 | [part-02-distributed-systems.md](part-02-distributed-systems.md) | 5,219 |
| 8. Introduction and Overview | 278-313 | [chapter-08-introduction-and-overview.md](chapter-08-introduction-and-overview.md) | 56,662 |
| 9. Failure Detection | 314-326 | [chapter-09-failure-detection.md](chapter-09-failure-detection.md) | 18,553 |
| 10. Leader Election | 327-339 | [chapter-10-leader-election.md](chapter-10-leader-election.md) | 18,358 |
| 11. Replication and Consistency | 340-380 | [chapter-11-replication-and-consistency.md](chapter-11-replication-and-consistency.md) | 66,542 |
| 12. Anti-Entropy and Dissemination | 381-402 | [chapter-12-anti-entropy-and-dissemination.md](chapter-12-anti-entropy-and-dissemination.md) | 30,892 |
| 13. Distributed Transactions | 403-434 | [chapter-13-distributed-transactions.md](chapter-13-distributed-transactions.md) | 48,291 |
| 14. Consensus | 435-484 | [chapter-14-consensus.md](chapter-14-consensus.md) | 75,843 |
| Part II Conclusion | 485-488 | [part-02-conclusion.md](part-02-conclusion.md) | 5,736 |
| A. Bibliography | 489-516 | [appendix-a-bibliography.md](appendix-a-bibliography.md) | 50,936 |
| Index | 517-590 | [index.md](index.md) | 61,421 |

## Provenance

Each Markdown file has YAML front matter with its source and page range. A marker such as
`<!-- pdf-page: 27 -->` identifies where each PDF page begins. `manifest.json` provides the
same section metadata and SHA-256 checksums for automated ingestion.
