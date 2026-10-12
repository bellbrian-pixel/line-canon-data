# Incentive Watcher — review needed — 2026-10-12

**Coverage: 40 of 46 targets live, 6 blind.** A blind target reports nothing, which looks exactly like good news.

```
INCENTIVE CANON WATCHER — 2026-10-12
Targets: 46 | staged to pending[]: 2

CHANGED (staged for approval):
  GA [review] detected=(none)  Georgia Entertainment Industry Investment Act  https://dor.georgia.gov/film-tax-credits
  VA [review] detected=$250,000  prior to January 1, 2031, any motion picture production company with qualifying expenses of at least $250,000  https://law.lis.virginia.gov/vacode/title58.1/chapter3/section58.1-439.12:03/

LIVE VALUES (semantics=value):
  MO detected=$7,860,522  https://mofilm.org/tax-incentives/motion-media-production/

LOCATOR NOT FOUND (likely redesign — re-derive locator, NOT a value change):
  KY ky_film  https://kyfilm.org/incentives/

BLOCKED (403 — needs a fallback source):
  AZ az_cc  https://www.azcommerce.com/film-media/incentive/
  MN mn_emn  https://www.exploreminnesota.com/film/incentives

FETCH ERRORS:
  MD md_commerce — HTTP 404
  MS ms_code — HTTP 503
  PR pr_ddec — Exception: Address unavailable: https://puertoricofilm.ddec.pr.gov/incentives/

Source-ranking exceptions in play: statute/reg > revenue > film office > industry.
  RI: statute governs; the administrative regulations are stale despite being binding.
  WA: washingtonfilmworks.org (a 501(c)(6) nonprofit) is the authoritative administrator, not a state agency.
  TN: the film-office page contradicts itself on the same page — never auto-resolve; human review required.

Nothing here changed a canon value. CHANGED/VALUE/TRAP rows are staged in pending[] for approval in the app.
```
