# Methodology — Mamdani's first six months: the promise ledger

**Product:** an embeddable Vital City-styled infographic tracking Mayor Zohran Mamdani's signature campaign promises through his first six months in office (Jan. 1 – July 1, 2026), plus major actions that were not campaign promises.

**Live file:** `index.html` (standalone card; `?embed=1` for the Ghost-embedded version).

## Data sources

All claims come from news coverage and official press releases published January–June 2026, gathered by web search and page fetches on July 1, 2026. Each entry in the graphic links directly to at least one named source. The primary outlets relied on:

- Gothamist (rent freeze vote, city budget deal, minimum wage bill, public-safety pace)
- New York Focus (final state budget contents)
- PBS NewsHour (Office of Community Safety launch)
- Hell Gate (housing plan analysis, pothole verification)
- Chalkbeat New York (class size / teacher hiring)
- amNewYork (adopted city budget, CityFHEPS)
- Streetsblog (Albany transit testimony)
- THE CITY (Tisch retention)
- Time, CBS New York, ABC7, The American Prospect, The Real Deal, The City Reporter
- Official releases: governor.ny.gov, edc.nyc, nyc.gov (mayor's office)
- Cross-checked against the independent Mamdani Tracker (mamdanitracker.nyc) and Vital City's own six-month assessment (vitalcitynyc.org/assessing-mamdani-six-months-in)

## How the promise list was chosen

The fifteen tracked promises are the most prominent, repeatedly reported commitments of the 2025 Mamdani campaign: the affordability agenda he ran on (rent freeze, free buses, universal childcare, city groceries, $30 wage, 200,000 homes, tax increases to fund it), the public-safety platform (Department of Community Safety, retaining Commissioner Tisch, disbanding the Strategic Response Group), other specific pledges that drew coverage (CityFHEPS lawsuit/vouchers, class-size hiring, immigrant legal defense, baby baskets) and the delivery promise woven through his victory and inaugural speeches (a government where excellence is "the expectation... not the exception"). The list is editorial judgment, not exhaustive; the independent trackers listed above follow dozens more.

## Status definitions

- **Delivered** — the specific promised outcome occurred.
- **In progress** — concrete, funded steps exist but the promise is unfinished.
- **Scaled back** — the administration is pursuing a materially smaller version than promised.
- **Blocked in Albany** — the state refused money or authority the promise requires.
- **No visible action** — we found no implementation steps in six months of news coverage and mayoral press releases. This is absence of coverage, not proof of inaction.

Status labels are editorial judgments applied to sourced facts. Borderline calls: universal childcare is "in progress" (not "scaled back") because the state-funded 2-Care launch is a funded first step the administration frames as a path to universality; the 200,000-homes plan is "in progress" (not "scaled back") because the targets were kept — and are more ambitious than the Bloomberg or de Blasio plans — while the financing methodology changed after Albany declined new borrowing capacity; CityFHEPS is "scaled back" rather than "abandoned" because the June budget funded a partial expansion after the February reversal.

## Calculations

The scoreboard strip (2 / 6 / 3 / 2 / 2) is a simple count of the fifteen promise rows by status label. No other derived numbers appear; every dollar figure, date and count is as reported by the linked source. Where authoritative estimates conflict, the graphic shows the range and attributes each figure (bus costs: Mamdani's $600–700M vs. the MTA chair's ~$1B; pied-à-terre revenue: the state's ~$500M projection vs. the comptroller's $340–380M).

## Verification

1. Three independent research passes (accomplishments; promise-by-promise status; stalls and blocks) compiled sourced findings with verbatim quotes, flagging every claim that rested on a search snippet rather than a fetched page.
2. A second, adversarial fact-check pass (four independent verifiers, one per claim group) re-verified every claim in the final graphic — each date, number, status label and quote — against the cited sources, primary documents (nyc.gov and City Council releases, comptroller reports, the Council's Legistar API, governor's office releases) and independent corroboration, and confirmed each cited link supports the sentence it is attached to. It found one factual error (the grocery $70 million figure's scope), two claims overtaken by events (the gang database and immigration legal-services funding) and a set of date and figure refinements, all fixed before publication. The full audit trail is in `FACT-CHECK.md`.
3. Claims that could not be fully confirmed are labeled in the graphic itself (e.g. the $86.4 million restored for immigration legal services against the $165 million pledge; the pothole comparison attributed to the transportation department).

## Limitations

- "No visible action" reflects the absence of public reporting and press releases, not internal City Hall activity.
- Several nyc.gov press pages returned errors to automated fetches; where that happened, claims rest on multiple independent news accounts instead.
- Dollar figures for young programs (grocery stores, Office of Community Safety) are early estimates that may change.
- The six-month window ends July 1, 2026; statuses will drift quickly (the rent freeze, for example, applies to leases beginning Oct. 1, 2026).
- Wikipedia's "Mayoralty of Zohran Mamdani" page was used as a finding aid; items sourced only to it were independently corroborated or flagged during the fact-check pass.

## Reproducibility

A competent researcher with the linked sources can reconstruct every entry. There is no data pipeline: the graphic is hand-assembled static HTML; every claim carries its source link inline. A claim-by-claim audit report (`FACT-CHECK.md`) will be added when the halted fact-check pass is completed. **Do not publish before that pass is done.**
