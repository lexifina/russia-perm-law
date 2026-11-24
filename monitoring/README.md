<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Perm Krai only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 14:33 UTC, Perm Krai: Official Internet Portal of Legal Information (region59): 12 addresses read; 23 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Perm Krai: Official Internet Portal of Legal Information (region59)](http://publication.pravo.gov.ru/documents/block/region59) | `zakony-<year>/` | daily | 2026-11-24 14:33 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 14:29](checks/2026-11.md#ru-pravo-perm-20261124t142916z) | pravo-perm | 12 | 23 | 0 | 0 | 0 (0) | changes found | [4](https://github.com/lexifina/russia-perm-law/compare/a5978753a05e...7816e9aa57fb) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
