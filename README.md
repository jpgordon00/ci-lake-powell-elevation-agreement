# How closely do satellite and dam-gauge changes agree at Lake Powell?

Compare changes in water-surface elevation from qualifying satellite passes and the public dam-gauge series.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/lake-powell-elevation-agreement/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-lake-powell-elevation-agreement/pulls)

## Why this matters

NASA’s SWOT LakeSP product reports pass-level water elevations and quality flags. The Bureau of Reclamation releases observed daily Lake Powell elevations. A relative-change comparison can handle an undocumented constant datum offset.

## What to contribute

Predeclare October 1 through November 20, 2026. Select all qualifying Lake Powell passes with a fixed lake identifier and quality filter. Match each to the nearest daily gauge reading and subtract each series’ first matched value.

## How reviewers check it

Include IDs, acquisition dates, time gaps, excluded passes, units and uncertainties. Report relative change in metres and only compare absolute levels if a common vertical datum is documented.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/lake-powell-elevation-agreement
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/lake-powell-elevation-agreement/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-lake-powell-elevation-agreement/security/advisories/new) for security reports.

## Sources

- [NASA SWOT LakeSP D product](<https://podaac.jpl.nasa.gov/dataset/SWOT_L2_HR_LakeSP_D>)
- [Bureau of Reclamation Lake Powell elevation data](<https://data.usbr.gov/catalog/2362/item/508>)
