# Familia Research

An AI skill for genealogy across the Russian Empire, the USSR, all 15 post-Soviet countries, border regions, and emigration.

Find records, connect generations, and keep every claim traceable to its source. Start with the family's existing archive and follow the historical jurisdiction of each event.

The skill and reference guides are written in Russian. The agent follows the user's preferred language and searches in the languages of the records.

## What it covers

- Parish registers, civil records, revision lists, censuses, military service, education, repression, evacuation, and collateral branches.
- Belarus and the Polish–Lithuanian borderlands, including changing civil and religious jurisdictions.
- Jewish and Lutheran records, Holocaust documentation, Scandinavian records, and migration beyond the former empire.
- Original scans, uncertain readings, competing identities, dependent sources, and searches with no result in a defined scope.
- Existing family trees and source-preserving exports, with private details excluded from public outputs.

Eight reference guides include a dated directory of 66 archival and research resources. Portal checks describe what was accessible on **7 November 2026**; they do not promise that a person's records exist or are available online.

## Install

For Codex, clone into an unused skill directory:

```sh
git clone https://github.com/mikwiseman/familia-research.git ~/.codex/skills/familia-research
```

If that directory already exists, review its contents before replacing or updating it. Other agents that load `SKILL.md` can use this repository in their own skill directory.

The skill is Markdown guidance: it installs no runtime, scripts, certificates, or external integrations. Research requires the agent's normal file-reading and web tools; access to individual archives may require an account or an archive request.

## Use

```text
Use $familia-research. Our family archive is at /path/to/family-archive.
Read the existing research, identify the unresolved relationships, and
find the next documents that could establish them. Save the sources,
conflicting accounts, and the exact scope of each search.
```

Keep family books, personal records, and research outputs in the family project, outside the skill repository. Research authorization does not by itself authorize sending letters, paying for copies, uploading DNA, or publishing a family tree.

Start with [SKILL.md](SKILL.md), which links to the relevant guides.

## Attribution

Adapted from [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research), by Denis Shiryaev, version 1.37.0. The original already covers the Russian Empire and Belarus. This adaptation provides a shorter entry point, a dedicated Belarus guide, regional routing, and a dated source directory.

See [provenance and pinned upstream references](references/upstream.md). MIT licensed; the [original copyright notice is preserved](LICENSE). This is an independent adaptation, not an upstream endorsement.
