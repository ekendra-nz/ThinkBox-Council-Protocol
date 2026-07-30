# ThinkBox Council Protocol

This repository contains the canonical **ThinkBox Council Protocol**: a general-purpose framework for structured deliberation among human participants, AI systems, specialist tools, and invited contributors.

The Protocol is designed to improve the quality of collective reasoning by:

* defining a clear deliberative process;
* separating facts, assumptions, interpretations, and preferences;
* exposing weak arguments and unresolved disagreements;
* preserving attribution and minority positions;
* recording how decisions and conclusions were reached;
* supporting transparent amendment and version history.

ThinkBox is not tied to any single project or field. The Protocol may be used to examine research questions, technical designs, governance proposals, practical decisions, disputes, plans, and other subjects requiring careful deliberation.

## Canonical document

The authoritative version of the Protocol is stored in:

```text
PROTOCOL.md
```

The copy published in the ThinkBox Discourse forum is a synchronised presentation of the version stored in this repository.

If the repository and forum copies ever differ, the version on the repository’s default branch is authoritative.

## Amendment process

Changes to the Protocol are deliberated and ratified in the ThinkBox Discourse forum.

The intended publication workflow is:

1. A forum topic containing an approved amendment is tagged `ratified`.
2. The Protocol Versioning Bot reads the topic and collates the ratified changes and their rationales.
3. The bot applies the changes to a branch and opens a pull request in this repository.
4. A human reviews and merges the pull request.
5. A GitHub webhook notifies ThinkBox that the merge has occurred.
6. The bot updates the canonical Protocol post in the forum from the merged repository document.

The bot may prepare changes, but it may not ratify amendments or merge pull requests. Human review remains part of the publication process.

## Repository contents

```text
README.md       Repository overview and governance information
PROTOCOL.md     Canonical text of the ThinkBox Council Protocol
```

Additional supporting files, such as a changelog or machine-readable version metadata, may be added as the versioning process develops.

## Status

The ThinkBox Council Protocol is under active development. Its procedures may be refined through the same deliberative and ratification process that the Protocol defines.

## Public record

This repository provides a durable and inspectable history of published Protocol changes. The associated Discourse discussions preserve the broader deliberative record, including proposals, reasoning, objections, revisions, and ratification decisions.
