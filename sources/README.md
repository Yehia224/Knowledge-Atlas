# Source Library — working foundation v0.1

Status: pending owner approval. This is a repository storage convention, not a decision about website sections, Gardens, ontology, or learning sequence.

Sources are external reference objects, not research results or canonical knowledge. A source may support multiple research scopes; a claim may use multiple sources.

- [Websites](websites/index.json) — public URLs and bibliographic metadata.
- [Books](books/README.md) — edition-specific bibliographic records, lawful file intake and analysis.
- [Papers](papers/index.json) — research papers and DOI/URL metadata.
- [Standards](standards/index.json) — standards, specifications and guidance; verify applicable edition and scope.
- [Handbooks](handbooks/index.json) — separately versioned handbook references.
- [Source record template](source-record.template.json).

The initial 12 links were transcribed from the prior Evidence Recovery register. They are recovered references, not newly re-verified facts or independently approved sources. No third-party text, images, book files, paid standards or private archives are copied here.

## Workflow

1. Search existing source IDs/URLs/DOIs/ISBNs and exact editions before creating a record.
2. Register source identity, author/publisher, title, edition/date, locator, acquisition date, permission, and access boundary.
3. Record exact page/chapter/section or web heading and access date for each research claim.
4. Separate extracted evidence from interpretation and note contradictory sources.
5. Link research findings to source IDs and exact locators. Record missing evidence explicitly.
6. Preserve original evidence IDs and map them to new source IDs in a crosswalk; never overwrite the old archive.
7. Subject review and explicit owner approval remain separate from registration and publication.

Public repository: metadata and permitted, reviewed material only. Do not upload private books, copyrighted scans or unpublished raw research. Store such items in an authorized private workspace and keep private locators out of public Git. A public branch is public too; .gitignore is a guard, not access control.
