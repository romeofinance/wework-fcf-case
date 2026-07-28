# WeWork: The Free Cash Flow Illusion
### A Mini-Case on Non-GAAP Metrics and True FCF

**Professor Kelly Shue · Yale School of Management**
**@RomeoFinanceAI**

---

## Background

In April 2018, WeWork raised $702 million through a high-yield bond offering. To make its financials palatable to investors, the company introduced a metric called **"Community Adjusted EBITDA"** — a term so unusual that Adam Cohen, founder of bond research firm Covenant Review, told the Wall Street Journal: *"I've never seen the phrase 'community adjusted Ebitda' in my life."* By August 2019, when WeWork filed its S-1 for a planned IPO at a $47 billion valuation, the metric had been renamed but the underlying logic hadn't changed. The IPO collapsed within weeks. WeWork filed for bankruptcy in November 2023.

## Part 1: What Management Showed Investors

In the 2018 bond offering, WeWork presented three layers of profitability — each one stripping away more of the company's actual costs. The trick was a metric called **"Community Adjusted EBITDA,"** which started with revenue, subtracted only the direct costs of running existing locations, then added back stock-based compensation. Everything else — marketing ($143M), new market development ($110M), G&A ($454M), and pre-opening costs ($131M) — was excluded as a "growth investment," not a real expense.

The result: for 2017, a company with a $933 million net loss reported a positive **$233 million** "Community Adjusted EBITDA." The S-1 filing later relabeled this as **"Contribution margin excluding non-cash GAAP straight-line lease cost"** — a mouthful that accomplished the same thing. The 2018 version of this metric was $467 million, even as the company's actual net loss grew to $1.93 billion.

Why this worked, briefly: by defining profitability at the individual-location level, WeWork could argue that each building was profitable once it filled up. This was technically true in the same way that a lemonade stand is profitable if you don't count the cost of the lemonade, the stand, or the kid running it. The expenses excluded — marketing, corporate overhead, development — were not optional. They were the costs required to acquire members, open locations, and keep the company operational. Without them, there was no business.

## Part 2: The Actual Financial Trajectory

All figures below are from the WeWork S-1 filing (SEC, August 14, 2019), in thousands:

| | **2016** | **2017** | **2018** | **H1 2019** |
|---|---:|---:|---:|---:|
| **Revenue** | $436,099 | $886,004 | $1,821,751 | $1,535,420 |
| Location Operating Expenses | (433,167) | (814,782) | (1,521,129) | (1,232,941) |
| Other Operating Expenses | — | (1,677) | (106,788) | (81,189) |
| Pre-Opening Location Expenses | (115,749) | (131,324) | (357,831) | (255,133) |
| Sales & Marketing | (43,428) | (143,424) | (378,729) | (320,046) |
| Growth & New Market Development | (35,731) | (109,719) | (477,273) | (369,727) |
| General & Administrative | (115,346) | (454,020) | (357,486) | (389,910) |
| Depreciation & Amortization | (88,952) | (162,892) | (313,514) | (255,924) |
| **Total Expenses** | **(832,373)** | **(1,817,838)** | **(3,512,750)** | **(2,904,870)** |
| **Operating Loss** | **(396,274)** | **(931,834)** | **(1,690,999)** | **(1,369,450)** |
| **Net Loss** | **(429,690)** | **(933,494)** | **(1,927,419)** | **(904,652)** |

Notice that total expenses were roughly **2× revenue** in every period. The operating loss *grew* in dollar terms even as revenue doubled. This is the opposite of operating leverage — every dollar of growth required more than a dollar of additional spending.

## Part 3: True Unlevered Free Cash Flow

Applying the framework from Lecture 7A, here is how much cash the business actually consumed. Capital expenditures come from the S-1's "Purchases of property and equipment" line in the cash flow statement, which represents the cash cost of building out new WeWork locations:

| | **2016** | **2017** | **2018** |
|---|---:|---:|---:|
| Operating Loss (EBIT) | (396,274) | (931,834) | (1,690,999) |
| × (1 – τ), where τ ≈ 0% | (396,274) | (931,834) | (1,690,999) |
| + Depreciation & Amortization | 88,952 | 162,892 | 313,514 |
| – Purchases of Property & Equipment | (776,074) | (1,023,953) | (2,055,020) |
| **≈ Unlevered FCF (before ΔWC)** | **(1,083,396)** | **(1,792,895)** | **(3,432,505)** |

The tax rate was effectively 0% because WeWork had massive operating losses — no taxable income, no tax bill. This means the EBIT line flows straight through to after-tax EBIT.

From the S-1 cash flow statement, the company's actual cash flows tell the same story:

| | **2016** | **2017** | **2018** | **H1 2019** |
|---|---:|---:|---:|---:|
| Operating Cash Flow | 176,905 | 243,992 | (176,729) | (198,711) |
| Investing Cash Flow | (818,525) | (1,376,767) | (2,475,798) | (2,362,773) |
| **Net Cash Consumed by Operations + Investment** | **(641,620)** | **(1,132,775)** | **(2,652,527)** | **(2,561,484)** |
| Financing Cash Flow (equity + debt raised) | 727,908 | 2,724,315 | 2,658,469 | 3,430,258 |

The company survived only because it raised more than $2–3 billion in new equity and debt every year. In 2018, it consumed $2.65 billion in cash from operations and investment while raising $2.66 billion from investors — nearly dollar-for-dollar replacement of burned cash with new capital.

## Part 4: The $2 Billion Gap

For 2017, WeWork's preferred metric — "Community Adjusted EBITDA" / "Contribution margin excluding non-cash GAAP straight-line lease cost" — was **+$233 million.** The true unlevered FCF (before working capital changes) was approximately **−$1.79 billion.** That is a gap of roughly **$2 billion.** The expenses excluded to bridge that gap were not "growth investments" in any meaningful sense — they were the cost of running the company.

This gap widened over time. By 2018, the equivalent contribution margin metric had grown to +$467 million, while unlevered FCF had deteriorated to −$3.43 billion. The better the non-GAAP metric looked, the worse the actual cash position became. This is the hallmark of a well-constructed vanity metric: it moves in the opposite direction of economic reality, giving investors false confidence at exactly the moment they should be most concerned.

The bond investors who bought WeWork's 7.875% senior notes in April 2018 were pricing risk based on a company that appeared location-level profitable and growing. The cash flow statement told them they were lending to a company that needed to raise billions annually just to keep the lights on. The bonds eventually traded at severe discounts before WeWork's bankruptcy in 2023.

---

*See companion spreadsheet: [Download WeWork_FCF_Analysis.xlsx](https://raw.githubusercontent.com/romeofinance/wework-fcf-case/main/WeWork_FCF_Analysis.xlsx).*
*All financial data sourced from WeWork S-1 filing (SEC, August 14, 2019). Filed as form S-1 by WeWork Companies Inc., CIK 0001533523.*
