# Operations Log

## 2026-08-03 (scheduled run: seo_page)
- Built cap-rate-calculator.html: interactive cap rate calculator (NOI breakdown, price-at-target-cap) + full guide (formula, worked example verified by recalculation, good-cap-rate guidance, cap rate vs cash-on-cash, offer-price method, limitations). FAQPage JSON-LD, canonical tag.
- Interlinked: index.html now links to the new page (body + footer); new page links back to index and to Gumroad product.
- Added page to sitemap.xml. Next task: product (landlord income & expense tracker).

## 2026-07-31 (launch, interactive session)
- Built and published Rental Property Deal Analyzer Pro on Gumroad ($24).
- Launched apophaticstudios.github.io with free ROI calculator funneling to the product.
- Seeded ops files, sitemap.xml, robots.txt. Next scheduled task: seo_page.

## 2026-08-05 (scheduled run: product)
- Built product #2: Landlord Income & Expense Tracker (.xlsx, 8 tabs: Start Here, Properties, Income/Expense/Mileage logs, Schedule E Summary, Dashboard, hidden Lists). 630 formulas, LibreOffice recalc: 0 errors; spot values verified by hand (depreciation mid-month proration, split 2026 mileage rates 72.5c/76c per IRS, Schedule E totals, monthly cash flow).
- Delivered workbook + ready-to-paste Gumroad listing copy ($24 suggested) to Joshua. AWAITING: Joshua uploads/publishes on Gumroad, then adds URL to state.json products_built.
- Next task: seo_page (suggested: rental property tax deduction checklist page — cross-sells the new tracker).

## 2026-08-07 (scheduled run: seo_page)
- Built brrrr-calculator.html: interactive BRRRR calculator (cash left in deal, refi proceeds at chosen LTV, post-refi cash flow, DSCR, cash-on-cash on cash-left-in, all-in/ARV ratio, 70% rule max offer) + full guide (method, worked example, refi LTV & seasoning facts researched 2026-08-07: Fannie 75%/70% investment cash-out LTV per Eligibility Matrix, 6-mo title + 12-mo existing-mortgage seasoning per SEL-2023-01, delayed financing exception, DSCR lenders 3-6 mo & 70-80% LTV, hard money 8-15%/1-4 pts, appraisal & rehab-overrun risks). FAQPage JSON-LD, canonical tag.
- Verified: worked example recomputed independently in Node (all figures match page copy exactly: $183k all-in, $182k loan, $5k left, DSCR 1.22, $265/mo CF, CoC 63.7%); page run headlessly in Chromium — zero JS errors, edge cases (rate 0, term 0, LTV 80, higher ARV → "all cash out ∞" badge) all behave correctly; JSON-LD parses as FAQPage.
- Interlinked: index.html (body + footer) and cap-rate-calculator.html (footer) now link to the new page; new page crumbs/footer/body link back to both and CTA to Gumroad product. Added to sitemap.xml.
- Rationale: page pre-builds SEO for roadmap product #3 (BRRRR deal analyzer), which the next run (product) will build — then cross-promote it on this page.
- Next task: product (BRRRR deal analyzer workbook).
