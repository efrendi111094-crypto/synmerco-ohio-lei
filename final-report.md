# Ohio's 40 largest banks matched to their LEI records

Intent b302dc23-270a-4f91-95c7-f8f9bdd74600. Escrow esc_6d14a55dde5e402a9c31661c (funded). Seller: agent 1 "Muse Nusantara" (did:key:z6Mkof8Ht8kDzGR87QK4Nu4BNPwXyX5S3YhxyLjJQbWqgE2y).

Three timed pulls, 24 hours apart. Pull 1: 19 Nov 2026 12:53 WIB (note 12:54:49 WIB). Pull 2: 20 Nov 2026 13:00 WIB. Pull 3: 21 Nov 2026 12:59 WIB (note 13:00:33 WIB). The 40 banks are fixed by CERT from pull 1.

## The 40 banks — raw FDIC rows (pull 1)

FDIC BankFind, /banks/institutions, filters STALP:OH AND ACTIVE:1, sort ASSET descending, fields NAME, CITY, CERT, ASSET, limit 40. 155 active Ohio banks in total; these are the 40 largest. Raw rows as returned:

| CERT | NAME | CITY | ASSET |
|---:|---|---|---:|
| 384 | The Ohio Valley Bank Company | Gallipolis | 1646225 |
| 628 | JPMorgan Chase Bank, National Association | Columbus | 4091315000 |
| 5962 | Sutton Bank | Attica | 1740659 |
| 5969 | The Farmers & Merchants State Bank | Archbold | 3490494 |
| 6531 | The Citizens National Bank of Bluffton | Bluffton | 1103400 |
| 6540 | The Farmers National Bank of Canfield | Canfield | 7159502 |
| 6544 | Peoples Bank | Marietta | 9530050 |
| 6548 | U.S. Bank National Association | Cincinnati | 705554946 |
| 6560 | The Huntington National Bank | Columbus | 283073605 |
| 6600 | First Financial Bank | Cincinnati | 22351293 |
| 6605 | The Merchants National Bank | Hillsboro | 1266936 |
| 6623 | LCNB National Bank | Lebanon | 2219306 |
| 6636 | THE VINTON COUNTY NATIONAL BANK | Mcarthur | 1588792 |
| 6653 | The Park National Bank | Newark | 12608562 |
| 6672 | Fifth Third Bank, National Association | Cincinnati | 299177000 |
| 9139 | The Commercial and Savings Bank of Millersburg, Ohio | Millersburg | 1295187 |
| 9437 | First State Bank | Winchester | 1240816 |
| 9457 | The North Side Bank and Trust Company | Cincinnati | 1172039 |
| 9463 | Unified Bank | Martins Ferry | 871724 |
| 11860 | The Killbuck Savings Bank Company | Killbuck | 953780 |
| 12969 | The Union Bank Company | Columbus Grove | 1443930 |
| 12978 | The Richwood Banking Company | Richwood | 1296076 |
| 12982 | Civista Bank | Sandusky | 4286454 |
| 13339 | The State Bank and Trust Company | Defiance | 1612519 |
| 13341 | The Croghan Colonial Bank | Fremont | 1414784 |
| 17534 | KeyBank National Association | Cleveland | 188555486 |
| 19482 | Consumers National Bank | Minerva | 1279390 |
| 27998 | Guardian Savings Bank | West Chester | 1394713 |
| 28263 | CFBank, National Association | Columbus | 2167338 |
| 29011 | Mechanics Bank | Mansfield | 896438 |
| 29488 | First Federal Savings and Loan Association of Lakewood | Lakewood | 2942482 |
| 29787 | First Federal Community Bank, National Association | Dover | 994585 |
| 29847 | Main Street Bank Corp. | Wooster | 1553716 |
| 30012 | Third Federal Savings and Loan Association of Cleveland | Cleveland | 18062658 |
| 32242 | Liberty Savings Bank, F.S.B. | Wilmington | 1111698 |
| 32296 | Union Savings Bank | Cincinnati | 4019642 |
| 32612 | NATIONAL COOPERATIVE BANK, N.A. | Hillsboro | 4329072 |
| 57269 | Signature Bank, National Association | Toledo | 1309420 |
| 58433 | Waterford Bank, N.A. | Toledo | 1771847 |
| 59378 | Erebor Bank, N.A. | Columbus | 4664972 |

## Match table — last good pull (pull 3)

Per bank: the LEI, GLEIF legal name, city, region, entity status and match rule. GLEIF cells are empty for conflict and no match. Sorted by CERT as a number.

| CERT | NAME | CITY | ASSET | lei | gleif legal name | gleif city | gleif region | entity status | match rule |
|---:|---|---|---:|---|---|---|---|---|---|
| 384 | The Ohio Valley Bank Company | Gallipolis | 1646225 | 549300JQGT4VX22XJ495 | The Ohio Valley Bank Company | Gallipolis | US-OH | ACTIVE | exact name |
| 628 | JPMorgan Chase Bank, National Association | Columbus | 4091315000 | 7H6GLXDRUGQFU57RNE97 | JPMorgan Chase Bank, National Association | Columbus | US-OH | ACTIVE | exact name |
| 5962 | Sutton Bank | Attica | 1740659 | 549300KYZ21NWSUOYP36 | Sutton Bank | Attica | US-OH | ACTIVE | exact name |
| 5969 | The Farmers & Merchants State Bank | Archbold | 3490494 | 254900LDNBFL67R4FW27 | The Farmers & Merchants State Bank | ARCHBOLD | US-OH | ACTIVE | exact name |
| 6531 | The Citizens National Bank of Bluffton | Bluffton | 1103400 | 549300HNMUG8WS7JLL28 | The Citizens National Bank of Bluffton | Bluffton | US-OH | ACTIVE | exact name |
| 6540 | The Farmers National Bank of Canfield | Canfield | 7159502 | 549300YNUT7D0FWKU636 | The Farmers National Bank Of Canfield | Canfield | US-OH | ACTIVE | exact name |
| 6544 | Peoples Bank | Marietta | 9530050 |  |  |  |  |  | no match |
| 6548 | U.S. Bank National Association | Cincinnati | 705554946 | 6BYL5QZYBDK8S7L73M02 | U.S. Bank National Association | Cincinnati | US-OH | ACTIVE | exact name |
| 6560 | The Huntington National Bank | Columbus | 283073605 | 2WHM8VNJH63UN14OL754 | The Huntington National Bank | Columbus | US-OH | ACTIVE | exact name |
| 6600 | First Financial Bank | Cincinnati | 22351293 | MV4O55SH8HO6KQSGW013 | First Financial Bank | Cincinnati | US-OH | ACTIVE | exact name |
| 6605 | The Merchants National Bank | Hillsboro | 1266936 | 254900PJ63T7KFSHAV90 | The Merchants National Bank | Hillsboro | US-OH | ACTIVE | exact name |
| 6623 | LCNB National Bank | Lebanon | 2219306 | 549300Q55VW95EP3CM33 | LCNB National Bank | Lebanon | US-OH | ACTIVE | exact name |
| 6636 | THE VINTON COUNTY NATIONAL BANK | Mcarthur | 1588792 | 54930087JNDLPJWOLV11 | THE VINTON COUNTY NATIONAL BANK | Mcarthur | US-OH | ACTIVE | exact name |
| 6653 | The Park National Bank | Newark | 12608562 | 549300CEHN5CVC6INV48 | The Park National Bank | Newark | US-OH | ACTIVE | exact name |
| 6672 | Fifth Third Bank, National Association | Cincinnati | 299177000 | QFROUN1UWUYU0DVIWD51 | Fifth Third Bank, National Association | Cincinnati | US-OH | ACTIVE | exact name |
| 9139 | The Commercial and Savings Bank of Millersburg, Ohio | Millersburg | 1295187 | 254900VHR12KN8C3F913 | THE COMMERCIAL AND SAVINGS BANK OF MILLERSBURG, OHIO | Millersburg | US-OH | ACTIVE | exact name |
| 9437 | First State Bank | Winchester | 1240816 |  |  |  |  |  | no match |
| 9457 | The North Side Bank and Trust Company | Cincinnati | 1172039 |  |  |  |  |  | no match |
| 9463 | Unified Bank | Martins Ferry | 871724 | 2549001ZX3163R62TB83 | UNIFIED BANK | Martins Ferry | US-OH | ACTIVE | exact name |
| 11860 | The Killbuck Savings Bank Company | Killbuck | 953780 |  |  |  |  |  | no match |
| 12969 | The Union Bank Company | Columbus Grove | 1443930 | 254900BDGU9FU91PQA51 | THE UNION BANK COMPANY | COLUMBUS GROVE | US-OH | ACTIVE | exact name |
| 12978 | The Richwood Banking Company | Richwood | 1296076 | 549300F263I3XPN55P35 | The Richwood Banking Company | Richwood | US-OH | ACTIVE | exact name |
| 12982 | Civista Bank | Sandusky | 4286454 | 549300H8JJI69WD7I525 | Civista Bank | Sandusky | US-OH | ACTIVE | exact name |
| 13339 | The State Bank and Trust Company | Defiance | 1612519 | UBNR8NKAK8J9JL4NZF88 | The State Bank and Trust Company | Defiance | US-OH | ACTIVE | exact name |
| 13341 | The Croghan Colonial Bank | Fremont | 1414784 | 5493004F1BOBD3SG7P54 | THE CROGHAN COLONIAL BANK | FREMONT | US-OH | ACTIVE | exact name |
| 17534 | KeyBank National Association | Cleveland | 188555486 | HUX2X73FUCYHUVH1BK78 | KeyBank National Association | Cleveland | US-OH | ACTIVE | exact name |
| 19482 | Consumers National Bank | Minerva | 1279390 | 549300E0P87HTQVFQH08 | Consumers National Bank | Minerva | US-OH | ACTIVE | exact name |
| 27998 | Guardian Savings Bank | West Chester | 1394713 | 549300ENNFGLHCMQ1U82 | Guardian Savings Bank | West Chester | US-OH | ACTIVE | exact name |
| 28263 | CFBank, National Association | Columbus | 2167338 | 549300ZGCIDP1G72QO72 | CFBank, National Association | Columbus | US-OH | ACTIVE | exact name |
| 29011 | Mechanics Bank | Mansfield | 896438 | 254900048S1FLI3G2922 | MECHANICS BANK | MANSFIELD | US-OH | ACTIVE | exact name |
| 29488 | First Federal Savings and Loan Association of Lakewood | Lakewood | 2942482 | 549300DPWFIO1S3DF358 | First Federal Savings And Loan Association Of Lakewood | Lakewood | US-OH | ACTIVE | exact name |
| 29787 | First Federal Community Bank, National Association | Dover | 994585 | 254900EYC7A87UC2J682 | First Federal Community Bank, National Association | Dover | US-OH | ACTIVE | exact name |
| 29847 | Main Street Bank Corp. | Wooster | 1553716 | 549300WLYZ63QPFTDP84 | MAIN STREET BANK CORP. | WOOSTER | US-OH | ACTIVE | exact name |
| 30012 | Third Federal Savings and Loan Association of Cleveland | Cleveland | 18062658 | 5493008CPTDVOS570626 | Third Federal Savings And Loan Association Of Cleveland | Cleveland | US-OH | ACTIVE | exact name |
| 32242 | Liberty Savings Bank, F.S.B. | Wilmington | 1111698 | 549300MU2YI0HXIT3257 | Liberty Savings Bank, F.S.B. | Wilmington | US-OH | ACTIVE | exact name |
| 32296 | Union Savings Bank | Cincinnati | 4019642 | 549300HFBEONQN2CK447 | Union Savings Bank | Cincinnati | US-OH | ACTIVE | exact name |
| 32612 | NATIONAL COOPERATIVE BANK, N.A. | Hillsboro | 4329072 | 5493001GAASLCSP1PB64 | NATIONAL COOPERATIVE BANK, N.A. | Hillsboro | US-OH | ACTIVE | exact name |
| 57269 | Signature Bank, National Association | Toledo | 1309420 | 549300MONA3L2BDK8Q22 | SIGNATURE BANK, NATIONAL ASSOCIATION | TOLEDO | US-OH | ACTIVE | exact name |
| 58433 | Waterford Bank, N.A. | Toledo | 1771847 | 549300Z8EM6P4IUIYG50 | Waterford Bank, N.A. | Toledo | US-OH | ACTIVE | exact name |
| 59378 | Erebor Bank, N.A. | Columbus | 4664972 | 254900S59ZHI2UFM9J76 | Erebor Bank, National Association | Columbus | US-OH | ACTIVE | exact name |

## Counts by match rule

- matched — exact name: 36
- matched — active preferred: 0
- matched — city preferred: 0
- matched total: 36
- conflict: 0
- no match: 4
- total banks: 40

## Match rule (as specified in the TASK)

Both names are normalized: lower-case, each punctuation character made a space, spaces collapsed, then a leading "the" and the words national association, n a, na, inc, corporation, corp, company and co removed. A candidate matches when the normalized names are equal and its legal address region is US-OH. One match: record it. Several: prefer entity status ACTIVE, then the one whose legal address city equals the bank's CITY (case-insensitive); still several: list them all and record none. None matches: record none.

## Rejected candidates

Per bank: the count rejected because the name differs; every other non-chosen candidate on one line (CERT, LEI, legal name, reason).

Per bank: the count rejected because the name differs, then one line per other
non-chosen candidate (CERT, LEI, legal name, reason).

- CERT 628 — JPMorgan Chase Bank, National Association: rejected because the name differs: 9
- CERT 6548 — U.S. Bank National Association: rejected because the name differs: 4
- CERT 6672 — Fifth Third Bank, National Association: rejected because the name differs: 9
- CERT 6560 — The Huntington National Bank: rejected because the name differs: 0
- CERT 17534 — KeyBank National Association: rejected because the name differs: 0
- CERT 6600 — First Financial Bank: rejected because the name differs: 2
  - 6600, 549300YIZECN2NB3I529, First Financial Bank, region not US-OH
  - 6600, 254900CNZPI5WN45KW48, First Financial Bank, region not US-OH
  - 6600, 549300IVURCTJ6QVMD67, First Financial Bank, region not US-OH
  - 6600, 549300E0S1LZYZ9QNX81, First Financial Bank, National Association, region not US-OH
- CERT 30012 — Third Federal Savings and Loan Association of Cleveland: rejected because the name differs: 0
- CERT 6653 — The Park National Bank: rejected because the name differs: 0
- CERT 6544 — Peoples Bank: rejected because the name differs: 0
  - 6544, 5493009I5VHHGVFQ1O54, PEOPLES BANK, region not US-OH
  - 6544, 549300YTXGR8QZNU8W23, Peoples Bank, region not US-OH
  - 6544, 549300NFNR2DM1ADF224, Peoples Bank, region not US-OH
  - 6544, 254900WQBZOLXT53K570, Peoples Bank, region not US-OH
  - 6544, 254900QIPUZ7PAK59X63, PEOPLES BANK, region not US-OH
  - 6544, 549300EOV6K1PRYMWI64, Peoples Bank, region not US-OH
  - 6544, 54930032OCUOR526IR93, Peoples Bank, region not US-OH
  - 6544, 549300Y7HCU10KIRLG30, Peoples Bank, region not US-OH
  - 6544, 5493001VH4ZJNSI25781, Peoples Bank, region not US-OH
  - 6544, 549300C3IEQBKRJTFK43, Peoples Bank, region not US-OH
- CERT 6540 — The Farmers National Bank of Canfield: rejected because the name differs: 0
- CERT 59378 — Erebor Bank, N.A.: rejected because the name differs: 9
- CERT 32612 — NATIONAL COOPERATIVE BANK, N.A.: rejected because the name differs: 9
- CERT 12982 — Civista Bank: rejected because the name differs: 0
- CERT 32296 — Union Savings Bank: rejected because the name differs: 1
  - 32296, 549300OEWY869SOVHF18, Union Savings Bank, region not US-OH
  - 32296, 1VUZZZCW0TWP6R7N3Z33, Union Savings Bank, region not US-OH
- CERT 5969 — The Farmers & Merchants State Bank: rejected because the name differs: 0
- CERT 29488 — First Federal Savings and Loan Association of Lakewood: rejected because the name differs: 0
- CERT 6623 — LCNB National Bank: rejected because the name differs: 0
- CERT 28263 — CFBank, National Association: rejected because the name differs: 9
- CERT 58433 — Waterford Bank, N.A.: rejected because the name differs: 9
- CERT 5962 — Sutton Bank: rejected because the name differs: 0
- CERT 384 — The Ohio Valley Bank Company: rejected because the name differs: 0
- CERT 13339 — The State Bank and Trust Company: rejected because the name differs: 1
- CERT 6636 — THE VINTON COUNTY NATIONAL BANK: rejected because the name differs: 0
- CERT 29847 — Main Street Bank Corp.: rejected because the name differs: 0
  - 29847, 549300N4D45V7JFCUS34, Main Street Bank Corp., region not US-OH
- CERT 12969 — The Union Bank Company: rejected because the name differs: 0
- CERT 13341 — The Croghan Colonial Bank: rejected because the name differs: 0
- CERT 27998 — Guardian Savings Bank: rejected because the name differs: 0
  - 27998, 2549008O15B0KZJLSV47, Guardian Savings Bank, region not US-OH
- CERT 57269 — Signature Bank, National Association: rejected because the name differs: 6
  - 57269, 549300925HE78SR7H984, Signature Bank, region not US-OH
  - 57269, 5493004KJY6OLD32A603, Signature Bank, region not US-OH
  - 57269, VLP5AP0XK2GM6GKD1007, Signature Bank, region not US-OH
- CERT 12978 — The Richwood Banking Company: rejected because the name differs: 0
- CERT 9139 — The Commercial and Savings Bank of Millersburg, Ohio: rejected because the name differs: 9
- CERT 19482 — Consumers National Bank: rejected because the name differs: 0
- CERT 6605 — The Merchants National Bank: rejected because the name differs: 1
- CERT 9437 — First State Bank: rejected because the name differs: 0
  - 9437, 254900JQVYSYVGEIMC54, First State Bank, region not US-OH
  - 9437, 254900M0JSF886GBC231, First State Bank, region not US-OH
  - 9437, 254900M61VTP3E1S9E27, First State Bank, region not US-OH
  - 9437, 254900CRPFBFJUTD8P12, First State Bank, region not US-OH
  - 9437, 254900NX6JAQSL0PM696, First State Bank, region not US-OH
  - 9437, 254900EQCMVB0XTB5Y50, First State Bank, region not US-OH
  - 9437, 254900NLF3E53TSP1673, First State Bank, region not US-OH
  - 9437, 549300R8N9KVQUKVNJ71, First State Bank, region not US-OH
  - 9437, 549300MJHRG6VMIL1B67, First State Bank, region not US-OH
  - 9437, 549300DFQP4S0ZYOBT18, First State Bank, region not US-OH
- CERT 9457 — The North Side Bank and Trust Company: rejected because the name differs: 0
- CERT 32242 — Liberty Savings Bank, F.S.B.: rejected because the name differs: 9
- CERT 6531 — The Citizens National Bank of Bluffton: rejected because the name differs: 0
- CERT 29787 — First Federal Community Bank, National Association: rejected because the name differs: 9
- CERT 11860 — The Killbuck Savings Bank Company: rejected because the name differs: 0
- CERT 29011 — Mechanics Bank: rejected because the name differs: 5
  - 29011, 549300W8JPEQ283RKJ52, Mechanics Bank, region not US-OH
  - 29011, 549300TF1E42EUFBSL45, Mechanics Bank, region not US-OH
- CERT 9463 — Unified Bank: rejected because the name differs: 0

## No match — detail

- CERT 6544 — Peoples Bank (Marietta): no match — none matched; 10 candidates returned, all name-equal, all outside Ohio.
- CERT 9437 — First State Bank (Winchester): no match — none matched; 10 candidates returned, all name-equal, all outside Ohio.
- CERT 9457 — The North Side Bank and Trust Company (Cincinnati): no match — no candidate came back (0 returned, HTTP 200).
- CERT 11860 — The Killbuck Savings Bank Company (Killbuck): no match — no candidate came back (0 returned, HTTP 200).

## Conflicts — detail

- (none)

## Changes — PULL 2 vs PULL 1

no change — 40 rows in PULL 1 and 40 rows in PULL 2 (new 0, gone 0, changed 0; later = earlier + new - gone = 40 + 0 - 0 = 40). No LEI changed between pulls, so no GLEIF excerpt is needed here.

## Changes — PULL 3 vs PULL 2

no change — 40 rows in PULL 2 and 40 rows in PULL 3 (new 0, gone 0, changed 0; later = earlier + new - gone = 40 + 0 - 0 = 40). No LEI changed between pulls, so no GLEIF excerpt is needed here.

## PROOF

One line per request: full request, UTC time, HTTP status. Under each pull, its first response's Date header line, copied exactly (the pull's source time).

### PULL 1

Date: Thu, 19 Nov 2026 05:53:07 GMT

- https://api.fdic.gov/banks/institutions?filters=STALP:OH%20AND%20ACTIVE:1&fields=NAME,CITY,CERT,ASSET&sort_by=ASSET&sort_order=DESC&limit=40&format=json | 2026-11-19T05:53:05.903Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=JPMorgan%20Chase%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:07.062Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=U.S.%20Bank%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:08.892Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Fifth%20Third%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:09.825Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Huntington%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:10.740Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=KeyBank%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:11.532Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Financial%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:12.304Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Third%20Federal%20Savings%20and%20Loan%20Association%20of%20Cleveland&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:13.515Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Park%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:14.267Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Peoples%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:15.114Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Farmers%20National%20Bank%20of%20Canfield&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:16.070Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Erebor%20Bank%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:16.869Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=NATIONAL%20COOPERATIVE%20BANK%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:18.209Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Civista%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:19.151Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Union%20Savings%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:19.904Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Farmers%20%26%20Merchants%20State%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:20.674Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Federal%20Savings%20and%20Loan%20Association%20of%20Lakewood&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:21.456Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=LCNB%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:22.254Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=CFBank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:23.300Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Waterford%20Bank%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:24.271Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Sutton%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:25.238Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Ohio%20Valley%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:25.999Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20State%20Bank%20and%20Trust%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:26.726Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=THE%20VINTON%20COUNTY%20NATIONAL%20BANK&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:27.520Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Main%20Street%20Bank%20Corp.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:28.301Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Union%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:29.084Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Croghan%20Colonial%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:29.801Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Guardian%20Savings%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:30.601Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Signature%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:31.889Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Richwood%20Banking%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:32.766Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Commercial%20and%20Savings%20Bank%20of%20Millersburg%2C%20Ohio&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:33.864Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Consumers%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:34.897Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Merchants%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:35.670Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20State%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:36.655Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20North%20Side%20Bank%20and%20Trust%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:37.528Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Liberty%20Savings%20Bank%2C%20F.S.B.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:38.429Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Citizens%20National%20Bank%20of%20Bluffton&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:39.362Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Federal%20Community%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:40.455Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Killbuck%20Savings%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:41.445Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Mechanics%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:42.203Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Unified%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-19T05:53:43.115Z | HTTP 200

### PULL 2

Date: Fri, 20 Nov 2026 05:56:35 GMT

- https://api.fdic.gov/banks/institutions?filters=STALP:OH%20AND%20ACTIVE:1&fields=NAME,CITY,CERT,ASSET&sort_by=ASSET&sort_order=DESC&limit=40&format=json | 2026-11-20T05:56:33.710Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=JPMorgan%20Chase%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:35.112Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=U.S.%20Bank%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:37.268Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Fifth%20Third%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:38.148Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Huntington%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:39.017Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=KeyBank%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:39.824Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Financial%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:40.655Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Third%20Federal%20Savings%20and%20Loan%20Association%20of%20Cleveland&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:41.623Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Park%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:42.854Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Peoples%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:43.678Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Farmers%20National%20Bank%20of%20Canfield&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:44.540Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Erebor%20Bank%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:45.303Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=NATIONAL%20COOPERATIVE%20BANK%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:46.122Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Civista%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:46.962Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Union%20Savings%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:47.625Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Farmers%20%26%20Merchants%20State%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:48.380Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Federal%20Savings%20and%20Loan%20Association%20of%20Lakewood&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:49.285Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=LCNB%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:50.085Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=CFBank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:50.959Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Waterford%20Bank%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:51.938Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Sutton%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:52.889Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Ohio%20Valley%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:53.625Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20State%20Bank%20and%20Trust%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:54.325Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=THE%20VINTON%20COUNTY%20NATIONAL%20BANK&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:55.096Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Main%20Street%20Bank%20Corp.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:55.972Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Union%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:56.720Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Croghan%20Colonial%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:57.362Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Guardian%20Savings%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:58.132Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Signature%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:59.062Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Richwood%20Banking%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:56:59.925Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Commercial%20and%20Savings%20Bank%20of%20Millersburg%2C%20Ohio&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:00.701Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Consumers%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:01.644Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Merchants%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:02.395Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20State%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:03.198Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20North%20Side%20Bank%20and%20Trust%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:04.025Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Liberty%20Savings%20Bank%2C%20F.S.B.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:04.716Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Citizens%20National%20Bank%20of%20Bluffton&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:05.697Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Federal%20Community%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:06.392Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Killbuck%20Savings%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:07.263Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Mechanics%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:08.502Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Unified%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-20T05:57:09.529Z | HTTP 200

### PULL 3

Date: Sat, 21 Nov 2026 05:59:08 GMT

- https://api.fdic.gov/banks/institutions?filters=STALP:OH%20AND%20ACTIVE:1&fields=NAME,CITY,CERT,ASSET&sort_by=ASSET&sort_order=DESC&limit=40&format=json | 2026-11-21T05:59:06.775Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=JPMorgan%20Chase%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:07.622Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=U.S.%20Bank%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:09.438Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Fifth%20Third%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:10.313Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Huntington%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:11.350Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=KeyBank%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:12.259Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Financial%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:13.046Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Third%20Federal%20Savings%20and%20Loan%20Association%20of%20Cleveland&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:14.099Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Park%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:15.138Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Peoples%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:15.987Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Farmers%20National%20Bank%20of%20Canfield&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:16.928Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Erebor%20Bank%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:17.702Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=NATIONAL%20COOPERATIVE%20BANK%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:18.580Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Civista%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:19.535Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Union%20Savings%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:20.256Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Farmers%20%26%20Merchants%20State%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:20.962Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Federal%20Savings%20and%20Loan%20Association%20of%20Lakewood&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:21.607Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=LCNB%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:22.399Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=CFBank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:23.201Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Waterford%20Bank%2C%20N.A.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:24.096Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Sutton%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:24.977Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Ohio%20Valley%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:25.715Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20State%20Bank%20and%20Trust%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:26.681Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=THE%20VINTON%20COUNTY%20NATIONAL%20BANK&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:27.512Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Main%20Street%20Bank%20Corp.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:28.241Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Union%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:29.005Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Croghan%20Colonial%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:29.647Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Guardian%20Savings%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:30.332Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Signature%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:31.082Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Richwood%20Banking%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:31.948Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Commercial%20and%20Savings%20Bank%20of%20Millersburg%2C%20Ohio&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:32.803Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Consumers%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:33.662Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Merchants%20National%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:34.393Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20State%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:35.472Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20North%20Side%20Bank%20and%20Trust%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:36.446Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Liberty%20Savings%20Bank%2C%20F.S.B.&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:37.182Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Citizens%20National%20Bank%20of%20Bluffton&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:38.103Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=First%20Federal%20Community%20Bank%2C%20National%20Association&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:38.785Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=The%20Killbuck%20Savings%20Bank%20Company&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:39.779Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Mechanics%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:40.499Z | HTTP 200
- https://api.gleif.org/api/v1/lei-records?filter%5Bentity.legalName%5D=Unified%20Bank&filter%5Bentity.legalAddress.country%5D=US&page%5Bsize%5D=10 | 2026-11-21T05:59:41.474Z | HTTP 200

## GLEIF excerpts — one per bank matched in the last good pull (pull 3)

Raw GLEIF record excerpts showing each matched LEI with its legal name, legal address city and region, and entity status.

- CERT 384: `{"lei": "549300JQGT4VX22XJ495", "legalName": "The Ohio Valley Bank Company", "legalAddress": {"city": "Gallipolis", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 628: `{"lei": "7H6GLXDRUGQFU57RNE97", "legalName": "JPMorgan Chase Bank, National Association", "legalAddress": {"city": "Columbus", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 5962: `{"lei": "549300KYZ21NWSUOYP36", "legalName": "Sutton Bank", "legalAddress": {"city": "Attica", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 5969: `{"lei": "254900LDNBFL67R4FW27", "legalName": "The Farmers & Merchants State Bank", "legalAddress": {"city": "ARCHBOLD", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6531: `{"lei": "549300HNMUG8WS7JLL28", "legalName": "The Citizens National Bank of Bluffton", "legalAddress": {"city": "Bluffton", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6540: `{"lei": "549300YNUT7D0FWKU636", "legalName": "The Farmers National Bank Of Canfield", "legalAddress": {"city": "Canfield", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6548: `{"lei": "6BYL5QZYBDK8S7L73M02", "legalName": "U.S. Bank National Association", "legalAddress": {"city": "Cincinnati", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6560: `{"lei": "2WHM8VNJH63UN14OL754", "legalName": "The Huntington National Bank", "legalAddress": {"city": "Columbus", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6600: `{"lei": "MV4O55SH8HO6KQSGW013", "legalName": "First Financial Bank", "legalAddress": {"city": "Cincinnati", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6605: `{"lei": "254900PJ63T7KFSHAV90", "legalName": "The Merchants National Bank", "legalAddress": {"city": "Hillsboro", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6623: `{"lei": "549300Q55VW95EP3CM33", "legalName": "LCNB National Bank", "legalAddress": {"city": "Lebanon", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6636: `{"lei": "54930087JNDLPJWOLV11", "legalName": "THE VINTON COUNTY NATIONAL BANK", "legalAddress": {"city": "Mcarthur", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6653: `{"lei": "549300CEHN5CVC6INV48", "legalName": "The Park National Bank", "legalAddress": {"city": "Newark", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 6672: `{"lei": "QFROUN1UWUYU0DVIWD51", "legalName": "Fifth Third Bank, National Association", "legalAddress": {"city": "Cincinnati", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 9139: `{"lei": "254900VHR12KN8C3F913", "legalName": "THE COMMERCIAL AND SAVINGS BANK OF MILLERSBURG, OHIO", "legalAddress": {"city": "Millersburg", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 9463: `{"lei": "2549001ZX3163R62TB83", "legalName": "UNIFIED BANK", "legalAddress": {"city": "Martins Ferry", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 12969: `{"lei": "254900BDGU9FU91PQA51", "legalName": "THE UNION BANK COMPANY", "legalAddress": {"city": "COLUMBUS GROVE", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 12978: `{"lei": "549300F263I3XPN55P35", "legalName": "The Richwood Banking Company", "legalAddress": {"city": "Richwood", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 12982: `{"lei": "549300H8JJI69WD7I525", "legalName": "Civista Bank", "legalAddress": {"city": "Sandusky", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 13339: `{"lei": "UBNR8NKAK8J9JL4NZF88", "legalName": "The State Bank and Trust Company", "legalAddress": {"city": "Defiance", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 13341: `{"lei": "5493004F1BOBD3SG7P54", "legalName": "THE CROGHAN COLONIAL BANK", "legalAddress": {"city": "FREMONT", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 17534: `{"lei": "HUX2X73FUCYHUVH1BK78", "legalName": "KeyBank National Association", "legalAddress": {"city": "Cleveland", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 19482: `{"lei": "549300E0P87HTQVFQH08", "legalName": "Consumers National Bank", "legalAddress": {"city": "Minerva", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 27998: `{"lei": "549300ENNFGLHCMQ1U82", "legalName": "Guardian Savings Bank", "legalAddress": {"city": "West Chester", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 28263: `{"lei": "549300ZGCIDP1G72QO72", "legalName": "CFBank, National Association", "legalAddress": {"city": "Columbus", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 29011: `{"lei": "254900048S1FLI3G2922", "legalName": "MECHANICS BANK", "legalAddress": {"city": "MANSFIELD", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 29488: `{"lei": "549300DPWFIO1S3DF358", "legalName": "First Federal Savings And Loan Association Of Lakewood", "legalAddress": {"city": "Lakewood", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 29787: `{"lei": "254900EYC7A87UC2J682", "legalName": "First Federal Community Bank, National Association", "legalAddress": {"city": "Dover", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 29847: `{"lei": "549300WLYZ63QPFTDP84", "legalName": "MAIN STREET BANK CORP.", "legalAddress": {"city": "WOOSTER", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 30012: `{"lei": "5493008CPTDVOS570626", "legalName": "Third Federal Savings And Loan Association Of Cleveland", "legalAddress": {"city": "Cleveland", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 32242: `{"lei": "549300MU2YI0HXIT3257", "legalName": "Liberty Savings Bank, F.S.B.", "legalAddress": {"city": "Wilmington", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 32296: `{"lei": "549300HFBEONQN2CK447", "legalName": "Union Savings Bank", "legalAddress": {"city": "Cincinnati", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 32612: `{"lei": "5493001GAASLCSP1PB64", "legalName": "NATIONAL COOPERATIVE BANK, N.A.", "legalAddress": {"city": "Hillsboro", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 57269: `{"lei": "549300MONA3L2BDK8Q22", "legalName": "SIGNATURE BANK, NATIONAL ASSOCIATION", "legalAddress": {"city": "TOLEDO", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 58433: `{"lei": "549300Z8EM6P4IUIYG50", "legalName": "Waterford Bank, N.A.", "legalAddress": {"city": "Toledo", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`
- CERT 59378: `{"lei": "254900S59ZHI2UFM9J76", "legalName": "Erebor Bank, National Association", "legalAddress": {"city": "Columbus", "region": "US-OH", "country": "US"}, "entityStatus": "ACTIVE"}`

## Data files

```synmerco-data
34b1ab37c29d85e5191e213187e1d4f809b06129c83a5c00cc4a9f00b3914f23 oh-bank-lei-pull1.csv
34b1ab37c29d85e5191e213187e1d4f809b06129c83a5c00cc4a9f00b3914f23 oh-bank-lei-pull2.csv
34b1ab37c29d85e5191e213187e1d4f809b06129c83a5c00cc4a9f00b3914f23 oh-bank-lei-pull3.csv
```
