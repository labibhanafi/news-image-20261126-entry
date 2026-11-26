# VERIFICATION — news-image-20261126 v1

Built 26 Nov 2026, ~15:00–16:15 WIB. All 46 stories happened or were first
reported on Thursday 26 November 2026, verified against live web reporting
during the build. Items first reported 25 Nov (US evening) but carried in
26 Nov editions worldwide are included per the competition rule ("happened,
or first reported, on 26 November 2026 in any time zone").

## Lead (double-checked, 2 sources)
- **US proposes new tariffs on 14 economies** (China up to 20%, Vietnam up
  to 35%, EU 15%): OneTurn world-news edition 26 Nov + Asia Daily
  ("USTR Jamieson Greer signed the findings on November 25, 2026 … 14
  economies … China up to 20 percent … Vietnam up to 35 percent") +
  FXStreet APAC update 26 Nov. Numbers agree across all three.

## Sources per story (headline sources)
- OneTurn 26 Nov edition: tariffs, Cairo fire (31 dead, 21 hurt), Houthis /
  Ras Tanura, US leave Iran, Gaza Hamas chief, Kim nuclear vow, Colombia
  hostages (76), Nigeria meth lab ($227m), Sudan Blue Nile (15), UK→Eswatini,
  Brent $91.19, U-17 Africa, Barcelona UCL.
- Reuters via Finwire 26 Nov: ASEAN+3 digital-payments talks, Kyoto.
- Asia Daily 26 Nov: tariff detail (14 economies, rates).
- FXStreet 26 Nov: BOK +25bp to 3.25%, tariff reaction, Nvidia halt.
- Euronews / Reuters / KuCoin 26 Nov: EU Brussels summit (€2tn budget,
  €45bn Ukraine loan, Macron Dec deadline), Poland no-fly zone.
- theScore / Fox Sports / NBC Sports: Rams 26-13 Packers, Corum 184 yds.
- Reuters / WVLT / Bloomberg Law 26 Nov: Macy's 100th parade moved to
  Saturday (first weather postponement; gusts 60 mph).
- Channel News Asia (via sumi.news) 26 Nov: Indonesia mine flood (13 dead,
  13 missing), Indonesia factory fire (26 dead), China Chen Jining probe,
  Indonesia treason charge, Huawei US conviction.
- Vocemundi / Morningstar / Monochrome Chronicles: FCC SpaceX 1m satellites
  (Starmind), Huawei 10 of 12 counts, Huang returns as Nvidia CEO.
- OpenSight News Flash 26 Nov: 1Password breach (staff GitHub account),
  NY AI chatbot toy ban (5 years).
- Globe TV / Jabulani Radio 26 Nov: Netanyahu Case 4000, FedEx Miami runway
  overrun, California king tides, Bangladesh 36% pay rise, Australia–
  Solomon Islands pact.
- Al Jazeera / The Star / AP: Mexico "El Chapo Isidro" capture (US drone,
  11 dead), Flavio Bolsonaro flees Brazil, Venezuela–Shell $400m, Peru
  quake 6.7, French navy 3.3t meth seizure, Canary Islands 2,100/day.
- Defence / Euronews: Russia ~500,000 troops leaked; Germany drone regiment;
  Spain Sunday vote; UK knife licensing.

## Excluded after checking
- Miss Universe 2026 (Puerto Rico's Jennifer Barreto): crowned **24 Nov** —
  excluded, not a 26 Nov event.
- Lula re-election (Brazil): 22 Nov — excluded; only the 26 Nov Flavio
  Bolsonaro flight is used.
- Shenzhou-24 launch itself was 25 Nov; the item used is the **26 Nov**
  boarding of Tiangong by Pakistan's Zeeshan Ali (first foreign astronaut
  aboard), as reported 26 Nov.

## Determinism / size checks
- `main.py` run twice (out1, out2): identical sha256
  `6611be00409870b32e74bea043271d2acd20f49b918e73cdc6b05ca876db7e5a`.
- Stdlib-only fallback (PIL blocked): byte-identical output.
- Size 527,713 bytes (target 450–600 KB, ≤1 MiB). PNG 1024×1024.
- Thumbnail 300 px + lead-band crop inspected: masthead and lead legible,
  hierarchy clear.
- Layout: hero-led (chosen over 3-column-only: the lead band + masthead
  carry the day at thumbnail size; lesson from news24 v3→v4).
