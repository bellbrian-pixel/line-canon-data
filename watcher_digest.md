# Incentive Watcher — review needed — 2026-09-09

**Coverage: 26 of 45 targets live, 19 blind.** A blind target reports nothing, which looks exactly like good news.

```
INCENTIVE CANON WATCHER — 2026-09-09
Targets: 45 | staged to pending[]: 0

LIVE VALUES (semantics=value):
  KY detected=$25,000,000  https://kyfilm.org/incentives/
  MO detected=$7,860,522  https://mofilm.org/tax-incentives/motion-media-production/

LOCATOR NOT FOUND (likely redesign — re-derive locator, NOT a value change):
  CA ca_guidelines  https://cdn.film.ca.gov/wp-content/uploads/2025/08/4.0-Program-Guidelines-1.pdf
  CO co_oedit  https://oedit.colorado.gov/colorado-film-incentive
  DE de_legis  https://legis.delaware.gov/BillDetail?LegislationId=142661
  HI hi_film  https://filmoffice.hawaii.gov/incentives-tax-credits/
  KY ky_ced  https://ced.ky.gov/Locating_Expanding/KEI/
  ME me_legis  https://legislature.maine.gov/doc/9940
  MO mo_ded  https://ded.mo.gov/programs/business-workforce/motion-media-production-tax-credit-program
  OK ok_film  https://www.okfilmmusic.org/incentives
  PA pa_dced  https://dced.pa.gov/programs/film-tax-credit-program/
  SC sc_prt  https://www.scprt.com/film-commission/incentives/production-incentives
  TN tn_tec  https://www.tnentertainment.com/film/incentives/
  TX tx_film  https://gov.texas.gov/uploads/files/film/Incentive_One_Sheet_FY26.pdf
  UT ut_film  https://film.utah.gov/wp-content/uploads/2025/04/IncentiveProgram_SummaryFAQ_April2025.pdf
  VA va_code  https://law.lis.virginia.gov/vacode/title58.1/chapter3/section58.1-439.12:03/
  WA wa_wf  https://www.washingtonfilmworks.org/funding/production-incentive-program

BLOCKED (403 — needs a fallback source):
  AZ az_cc  https://www.azcommerce.com/film-media/incentive/
  MN mn_emn  https://www.exploreminnesota.com/film/incentives

FETCH ERRORS:
  MS ms_code — HTTP 504
  PR pr_ddec — Exception: Address unavailable: https://puertoricofilm.ddec.pr.gov/incentives/

Source-ranking exceptions in play: statute/reg > revenue > film office > industry.
  RI: statute governs; the administrative regulations are stale despite being binding.
  WA: washingtonfilmworks.org (a 501(c)(6) nonprofit) is the authoritative administrator, not a state agency.
  TN: the film-office page contradicts itself on the same page — never auto-resolve; human review required.

Nothing here changed a canon value. CHANGED/VALUE/TRAP rows are staged in pending[] for approval in the app.
```
