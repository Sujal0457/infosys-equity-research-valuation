# Infosys Ltd (NSE: INFY) — Equity Research Coverage

A self-directed equity research project: a full DCF + comparable-companies valuation model and a written sell-side-style research note, built as portfolio evidence for equity research / financial analyst roles.

**Rating: Hold/Neutral | CMP: Rs 1,121 | Target: Rs 1,037 (12M, indicative) | Downside: -7.5%**

## Files in this project

| File | What it is |
| --- | --- |
| `Infosys_Equity_Research_Model.xlsx` | 37-sheet valuation model: historical financials, ratio analysis, WACC/beta build, segment-level forecast, an FCFF DCF with a top-down/bottom-up reconciliation through a corporate-cost bridge, comps, scenarios, and a 22-check audit dashboard |
| `Infosys_Equity_Research_Note.docx` | 3-5 page written research note — business overview, recent performance, valuation, investment thesis, risks & catalysts |
| `Infosys_Equity_Research_Tear_Sheet.pdf` | One-page visual summary (football field chart, key outputs, thesis) |


## How the model is organized

Tabs are grouped and color-coded into sections. Start with `Model Checks` (the dashboard: 22 formula-driven checks, all passing) and `Legacy vs Integrated` (line-by-line reconciliation between the top-down and bottom-up builds of the DCF), then `Valuation Summary` for the target-price derivation.

## Methodology, in brief

**One FCFF DCF, built and cross-checked two ways.** The forecast is assembled bottom-up from eight reporting segments and also viewed top-down as a single consolidated EBIT path. Because both views draw on the same revenue and the same consolidated EBIT margin, they reconcile to the rupee (Rs 796/share on each build) — an internal build-integrity check that the segment sum ties to the aggregate, not two independent opinions. The bottom-up build explicitly deducts normalized corporate/unallocable costs — Rs 6,191 crore reported, less a Rs 1,289 crore one-off labour-code provision, giving a Rs 4,902 crore normalized base — to reconcile segment operating income down to consolidated EBIT. Debt/net debt is formula-linked consistently to the Data Sheet/WACC definition: Rs 9,176 crore debt less Rs 22,201 crore cash = Rs -13,025 crore net debt. Comparable companies provide the genuine external, market-based cross-check. A terminal-value diagnostic (implied terminal EV/EBITDA of ~6.9x versus a ~11.6x core-peer median) is disclosed as a reasonableness check on the terminal cash-flow economics, not as an exit-multiple input.

**Terminal value is derived, not assumed.** Terminal reinvestment rate = terminal growth / terminal ROIC (3.0% / 40% = 7.5%), with terminal ROIC set explicitly (40%, faded down from Infosys's historical ROIC but held above WACC) rather than left as a residual. Both builds apply the same Gordon (1+g) terminal-FCFF convention, which is why they tie exactly.

**Risk-free rate / market return documentation:** the model uses a 6.77% India benchmark 10-year G-Sec yield (6.768% observed 6 Aug 2026, rounded), a 12.95% total market return built from the geometric/CAGR Nifty 50 price-return series for 2000–2025 plus a 1.30% dividend yield, and therefore a 6.18% ERP. Sources are documented on the `Rm` and `WACC` tabs.

**Beta is bottom-up.** Peer regression betas (the five core peers, refreshed over the same 2-year weekly window as Infosys's own regression) are unlevered, the median (0.8045) is taken and re-levered at Infosys's capital structure to 0.8244 for use in the WACC — producing a cost of equity of 11.87% and a WACC of 11.59%. Infosys's own 2-year weekly regression (raw beta ~0.73, R^2 ~ 0.13) is low-explanatory-power and is shown for reference only — it is deliberately not used in the WACC.

**Comps are split into core and extended peer sets**, not blended into one number. Core peers (TCS, HCL Technologies, Wipro, Tech Mahindra, LTIMindtree) are large-cap IT services firms genuinely comparable in scale; an extended set (Persistent Systems, Coforge, Mphasis, Hexaware) trades at materially higher multiples reflecting a smaller, higher-growth profile and is shown for context only, not used to anchor the target price. (A combined all-nine-peer median, shown separately on the `Comps Val` tab for transparency, implies ~Rs 1,677/share on EV/EBITDA — this reference figure is not the core-peer valuation and is not used in the target.)

**The target price uses a stated, fixed weighting (60% DCF / 40% core-peer EV/EBITDA)**, not a number picked to hit a preferred rating. The DCF is treated as primary because it captures Infosys's own guided cash-flow economics directly; comps are a market-based cross-check. At this weighting, the DCF's implied overvaluation dominates the peer discount, producing a Hold/Neutral call with ~7.5% downside to the indicative target — not the direction a self-interested "make it look attractive" model would have been built to reach.

## Known limitations (disclosed, not hidden)

- **Beta data refreshed.** The 2-year weekly regression window runs through the week of 18 August 2026 (last weekly observation 16 August 2026), the last trading week before the valuation date, using NSE Infosys, NSE peer, and NIFTY 50 weekly observations. The beta-freshness audit passes.
- **The 60/40 DCF/comps weighting is a judgment call**, stated explicitly rather than derived. A reader who weights comps more heavily would reach a less negative, or even positive, view — the model does not claim there is one objectively correct weighting.
- **Terminal ROIC (40%) and terminal growth (3.0%)** are explicit analyst assumptions, not derived from the model — visible and adjustable in `Operating Drivers`, but opinions, not facts.
- **The DCF is deliberately conservative relative to the market.** Fair value (~Rs 796) sits well below both the current price and where core peers trade (core EV/EBITDA implies ~Rs 1,399); the Hold rests on the DCF, with comps preventing an overly bearish call.
- **The terminal-value diagnostic (~6.9x FY31 implied EV/EBITDA vs ~11.6x current core-peer median)** assumes today's peer multiple structure persists through the forecast horizon; if sector multiples compress (e.g. AI-driven fee-pool disintermediation across the peer set), the diagnostic would overstate the terminal value's plausibility even when it reads as within range.

## Build notes

Historical financials sourced from Infosys's FY26 Integrated Annual Report (including the segment/unallocable-cost disclosure on p.387) and Screener.in; FY27 guidance and Q1 FY27 results from company press releases. Peer multiples and peer betas from Screener.in and NSE weekly price data; historical P/E and Nifty 50 dividend-yield context from Trendlyne; Nifty 50 annual price-return history from NSE Indices; risk-free benchmark yield from India 10-year G-Sec market data. The model tabs document the specific point-in-time inputs and methodology. This is a self-directed research exercise for portfolio purposes and is not investment advice.
