# Familia Research

An AI skill for worldwide genealogy, with detailed routes for the Russian Empire, the USSR, all 15 post-Soviet countries, Jewish communities, border regions, and migration.

Find records, connect generations, and keep every claim traceable to its source. Start with the family's existing archive and follow the historical jurisdiction of each event.

The skill and reference guides are written in Russian. The agent follows the user's preferred language and searches in the languages of the records.

## What it covers

- Parish registers, civil records, revision lists, censuses, military service, education, repression, evacuation, and collateral branches.
- Belarus and the Polish–Lithuanian borderlands, including changing civil and religious jurisdictions.
- Jewish communities worldwide, communal records, Yizkor books, burials, Holocaust documentation, refugee aid, and diaspora archives.
- European, American, Israeli, Scandinavian, Asian, African, Australian, and New Zealand research routes, with local jurisdiction guiding the search.
- Official APIs, IIIF images, documented MCP servers, multilingual OCR, and verified delivery of findings when authorized.
- Original scans, uncertain readings, competing identities, dependent sources, and searches with no result in a defined scope.
- Existing family trees and source-preserving exports, with private details excluded from public outputs.

Eleven reference guides include the [original 66-entry directory](references/sources-2026-11-07.md), [50 Jewish research routes](references/jewish-research.md), [70 additional worldwide routes](references/worldwide-sources.md), and [16 API/standard entries plus two documented MCP servers](references/apis-and-mcp.md). These lists overlap and include sections of larger portals; they are not a count of independent archives.

Checks describe what was accessible on **7 November 2026**: a readable page, official pointer, browser interface, access error, or tested structured request. They do not promise that a person's records exist or are available online. Open Archives MCP returned 22 tools and real search results; a year filter was not honored, so the guide records this limitation. An Open Library query returned structured bibliographic data. Other integrations may require authorization or keys.

For a broad family project, the skill tracks every named person and expands through newly found places, relatives, institutions, and record types. A source directory remains a starting point: the agent searches for additional local repositories and records the actual coverage and unresolved questions.

## Install

For Codex, clone into an unused skill directory:

```sh
git clone https://github.com/mikwiseman/familia-research.git ~/.codex/skills/familia-research
```

If that directory already exists, review its contents before replacing or updating it. Other agents that load `SKILL.md` can use this repository in their own skill directory.

The skill is Markdown guidance: it installs no runtime, scripts, certificates, or external integrations. API and MCP documentation does not automatically connect a server. Research requires the agent's normal file-reading and web tools; individual archives may require an account or an archive request.

## Use

```text
Use $familia-research. Our family archive is at /path/to/family-archive.
Continue the existing research for everyone in the family books, including
maternal and collateral branches. Find documents that establish or disprove
relationships. Expand the source directory as new places and collections
appear. Save originals, conflicting accounts, and each search's actual scope.
```

Keep family books, personal records, and research outputs in the family project, outside the skill repository. Research authorization does not by itself authorize sending letters, paying for copies, uploading DNA, or publishing a family tree.

Start with [SKILL.md](SKILL.md), which links to the relevant guides.

## Attribution

Adapted from [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research), by Denis Shiryaev, version 1.37.0. The original already covers the Russian Empire and Belarus. This adaptation provides a shorter entry point, a dedicated Belarus guide, regional routing, and a dated source directory.

See [provenance and pinned upstream references](references/upstream.md). MIT licensed; the [original copyright notice is preserved](LICENSE). This is an independent adaptation, not an upstream endorsement.
