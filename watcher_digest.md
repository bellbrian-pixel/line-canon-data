# Incentive Watcher — review needed — 2026-09-10

**Coverage: 42 of 46 targets live, 4 blind.** A blind target reports nothing, which looks exactly like good news.

```
INCENTIVE CANON WATCHER — 2026-09-10
Targets: 46 | staged to pending[]: 0

NOTE: Text normaliser v4 -> v5. All fingerprints discarded and re-baselined; no CHANGED comparison this run.

LIVE VALUES (semantics=value):
  KY detected=$75,000,000  https://kyfilm.org/incentives/
  MO detected=$7,860,522  https://mofilm.org/tax-incentives/motion-media-production/

BLOCKED (403 — needs a fallback source):
  AZ az_cc  https://www.azcommerce.com/film-media/incentive/
  MN mn_emn  https://www.exploreminnesota.com/film/incentives

FETCH ERRORS:
  MS ms_code — HTTP 404
  PR pr_ddec — Exception: Address unavailable: https://puertoricofilm.ddec.pr.gov/incentives/

Source-ranking exceptions in play: statute/reg > revenue > film office > industry.
  RI: statute governs; the administrative regulations are stale despite being binding.
  WA: washingtonfilmworks.org (a 501(c)(6) nonprofit) is the authoritative administrator, not a state agency.
  TN: the film-office page contradicts itself on the same page — never auto-resolve; human review required.

Nothing here changed a canon value. CHANGED/VALUE/TRAP rows are staged in pending[] for approval in the app.
```
