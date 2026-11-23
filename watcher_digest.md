# Incentive Watcher — review needed — 2026-11-23

**Coverage: 43 of 47 targets live, 4 blind.** A blind target reports nothing, which looks exactly like good news.

```
INCENTIVE CANON WATCHER — 2026-11-23
Targets: 47 | staged to pending[]: 0

LIVE VALUES (semantics=value):
  MO detected=$7,860,522  https://mofilm.org/tax-incentives/motion-media-production/

BLOCKED (403 — needs a fallback source):
  AZ az_cc  https://www.azcommerce.com/film-media/incentive/
  MN mn_emn  https://www.exploreminnesota.com/film/incentives

FETCH ERRORS:
  MS ms_code — HTTP 404
  PR pr_ddec — Exception: Address unavailable: https://puertoricofilm.ddec.pr.gov/incentives/

STALENESS (verified_on age — silence is not confirmation):
  [WARN] AL Alabama — 96 days since verified
  [WARN] AZ Arizona — 96 days since verified
  [WARN] AR Arkansas — 96 days since verified
  [WARN] CA California — 96 days since verified
  [WARN] CO Colorado — 96 days since verified
  [WARN] CT Connecticut — 96 days since verified
  [WARN] DE Delaware — 96 days since verified
  [WARN] DC Dist. of Columbia — 96 days since verified
  [WARN] GA Georgia — 96 days since verified
  [WARN] HI Hawaii — 96 days since verified
  [WARN] IL Illinois — 96 days since verified
  [WARN] IN Indiana — 96 days since verified
  [WARN] IA Iowa — 96 days since verified
  [WARN] KY Kentucky — 96 days since verified
  [WARN] LA Louisiana — 96 days since verified
  [WARN] ME Maine — 96 days since verified
  [WARN] MD Maryland — 96 days since verified
  [WARN] MA Massachusetts — 96 days since verified
  [WARN] MN Minnesota — 96 days since verified
  [WARN] MS Mississippi — 96 days since verified
  [WARN] MO Missouri — 96 days since verified
  [WARN] MT Montana — 96 days since verified
  [WARN] NE Nebraska — 96 days since verified
  [WARN] NV Nevada — 96 days since verified
  [WARN] NJ New Jersey — 96 days since verified
  [WARN] NM New Mexico — 96 days since verified
  [WARN] NY New York — 96 days since verified
  [WARN] NC North Carolina — 96 days since verified
  [WARN] OH Ohio — 96 days since verified
  [WARN] OK Oklahoma — 96 days since verified
  [WARN] OR Oregon — 96 days since verified
  [WARN] PA Pennsylvania — 96 days since verified
  [WARN] PR Puerto Rico — 96 days since verified
  [WARN] RI Rhode Island — 96 days since verified
  [WARN] SC South Carolina — 96 days since verified
  [WARN] TX Texas — 96 days since verified
  [WARN] UT Utah — 96 days since verified
  [WARN] WA Washington — 96 days since verified
  [WARN] WV West Virginia — 96 days since verified
  [WARN] WI Wisconsin — 96 days since verified

Source-ranking exceptions in play: statute/reg > revenue > film office > industry.
  RI: statute governs; the administrative regulations are stale despite being binding.
  WA: washingtonfilmworks.org (a 501(c)(6) nonprofit) is the authoritative administrator, not a state agency.
  TN: the film-office page contradicts itself on the same page — never auto-resolve; human review required.

Nothing here changed a canon value. CHANGED/VALUE/TRAP rows are staged in pending[] for approval in the app.
```
