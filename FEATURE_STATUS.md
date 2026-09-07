# Feature status — Accounting, AP/AR & audit

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 239 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 2 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 10 | 0 | Native records/view |
| Activity & audit trail | audit | 8 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| Vendor master normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice and payment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exact duplicate detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuzzy invoice matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Split-invoice detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate expense analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor credit-balance discovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Statement-to-ledger reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cancelled payment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery case management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor correspondence generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund and credit tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| General-ledger reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Preventive payment controls | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor and root-cause analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer contract and price library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice and receivable ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash and lockbox matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Short-payment detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deduction reason classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unauthorized discount detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Freight deduction validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Damage deduction validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Promotion allowance validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax and pricing analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proof-of-delivery matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence request workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deadline and aging control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovered cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer root-cause analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lease agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Device serial registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter read ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Included volume calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mono color click rate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply inclusion control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service downtime credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Device relocation tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate device billing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property tax fee review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Early termination audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet device analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product channel registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross revenue reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund chargeback allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax pass-through exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue-share tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum guarantee tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing service fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing payment detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner product profitability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bank lockbox ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer payer normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remittance extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice candidate matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exact cash matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Probabilistic cash matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partial payment allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consolidated payment handling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deduction identification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unidentified receipt workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer credit analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund reapplication control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Aging escalation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer unit analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice Matching | records | 1 | 0 | Native records/view |
| Payment Reconciliation | records | 1 | 0 | Native records/view |
| Dunning Optimization | records | 1 | 0 | Native records/view |
| Cash Application | records | 1 | 0 | Native records/view |
| Discount Capture | records | 1 | 0 | Native records/view |
| Aging Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor Health Score | records | 1 | 0 | Native records/view |
| Customer Credit Advisor | records | 1 | 0 | Native records/view |
| Dunning Letter Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice Anomaly Detector | records | 1 | 0 | Native records/view |
| Cash Flow Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intercompany Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax Compliance Validator | records | 1 | 0 | Native records/view |
| Discount Dashboard | records | 1 | 0 | Native records/view |
| 3-Way Matching | records | 1 | 0 | Native records/view |
| Vendor Fraud Detection | records | 1 | 0 | Native records/view |
| Multi-Currency FX | records | 1 | 0 | Native records/view |
| ERP Mapping Suggestions | records | 1 | 0 | Native records/view |
| AI History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Notifications & Alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Evidence | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Statistical Sampling | records | 1 | 0 | Native records/view |
| Workpapers | records | 1 | 0 | Native records/view |
| Audit Findings | records | 1 | 0 | Native records/view |
| Compliance Checklists | records | 1 | 0 | Native records/view |
| Evidence Adequacy | records | 1 | 0 | Native records/view |
| Materiality Calc | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Risk Heat Map | records | 1 | 0 | Native records/view |
| Workpaper Templates | records | 1 | 0 | Native records/view |
| Advanced AI Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PBC Aging Risk | records | 1 | 0 | Native records/view |
| Audit Trail | records | 3 | 0 | Native records/view |
| User Management | records | 1 | 0 | Native records/view |
| Missing features | records | 2 | 0 | Native records/view |
| Production readiness | records | 2 | 0 | Native records/view |
| Expense Reports | records | 2 | 0 | Native records/view |
| Employees | records | 1 | 0 | Native records/view |
| Departments | records | 1 | 0 | Native records/view |
| Categories | records | 1 | 0 | Native records/view |
| Vendors | records | 3 | 0 | Native records/view |
| Policy Rules | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Budget Limits | records | 2 | 0 | Native records/view |
| Trip Plans | records | 1 | 0 | Native records/view |
| Approvals | records | 2 | 0 | Native records/view |
| AI Fraud Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Anomaly Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Duplicate Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Vendor Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Employee Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Policy Compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Policy Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Approval Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Tax Deductions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Spending Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Budget Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Dept Benchmark | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Cost Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Smart Search | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Categorization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Receipt Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Report Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Trip Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Currency Converter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Audit Report Gen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Merchant risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Admin tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benford's Law Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction Anomaly Detection | records | 1 | 0 | Native records/view |
| Embezzlement Pattern Recognition | records | 1 | 0 | Native records/view |
| Financial Statement Fraud Scoring | records | 1 | 0 | Native records/view |
| Financial Ratios Calculator | records | 1 | 0 | Native records/view |
| Data Import | records | 1 | 0 | Native records/view |
| Network Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shell Company Linkage | records | 1 | 0 | Native records/view |
| Extras | records | 1 | 0 | Native records/view |
| Purchase Orders | records | 1 | 0 | Native records/view |
| Payments | records | 1 | 0 | Native records/view |
| Expense Categories | records | 1 | 0 | Native records/view |
| Receipts | records | 1 | 0 | Native records/view |
| Tax Records | records | 1 | 0 | Native records/view |
| Bank Reconciliation | records | 1 | 0 | Native records/view |
| Credit Notes | records | 1 | 0 | Native records/view |
| Currency Conversions | records | 1 | 0 | Native records/view |
| Duplicate Detection | records | 1 | 0 | Native records/view |
| Revenue recognition engine work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Control | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Gap | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Classify Deficiency | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Generate Narrative | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Review Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze ITGC | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Financial Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SoD Conflict Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Access Risk Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Change Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remediation Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Audit Plan Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Control Library | records | 1 | 0 | Native records/view |
| Evidence Requests | records | 1 | 0 | Native records/view |
| Policy Mapping | records | 1 | 0 | Native records/view |
| Audit Workflows | records | 1 | 0 | Native records/view |
| Risk Dashboard | records | 1 | 0 | Native records/view |
| Remediation Retests | records | 1 | 0 | Native records/view |
| Report Exports | records | 1 | 0 | Native records/view |
| Trends & Retests | records | 1 | 0 | Native records/view |
| Executive Dashboards | records | 1 | 0 | Native records/view |
| Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence Vault | records | 1 | 0 | Native records/view |
| Management Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Financial Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Segregation of Duties | records | 1 | 0 | Native records/view |
| Access Control | records | 1 | 0 | Native records/view |
| Change Management | records | 1 | 0 | Native records/view |
| Audit Reports | records | 1 | 0 | Native records/view |
| Audit Planning | records | 1 | 0 | Native records/view |
| PCAOB Workpaper Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Controls Monitor | records | 1 | 0 | Native records/view |
| Regulatory Updates | records | 1 | 0 | Native records/view |
| Sampling Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence Quality | records | 1 | 0 | Native records/view |
| Key Report Completeness | records | 1 | 0 | Native records/view |
| regulatory change digest ingesting sec pcaob updates flagging | records | 1 | 0 | Native records/view |
| anomaly detection in gl payroll ap transaction feeds | records | 1 | 0 | Native records/view |
| remediation tracking dashboard with timeline view and predictive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| evidence adequacy checker via rag over pcaob coso | records | 1 | 0 | Native records/view |
| continuous controls monitoring with real time exception alerts | records | 1 | 0 | Native records/view |
| sampling recommendation engine test size based on | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| evidence quality assessment is provided evidence sufficient | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai driven control to risk auto mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| integration with workiva auditboard or other audit | integration | 1 | 0 | Provider request records only |
| workflow approvals sign offs for findings no approval | records | 1 | 0 | Native records/view |
| multi year trend analysis or re test scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| webhooks notifications for remediation deadlines or new | integration | 1 | 0 | Provider request records only |
| dedicated audit trail subsystem despite domain requirement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dashboards for executive reporting beyond pdf export | records | 1 | 0 | Native records/view |
| Sox ops | records | 1 | 0 | Native records/view |
| Aging dashboard | records | 1 | 0 | Native records/view |
| Shortfall alerts | records | 1 | 0 | Native records/view |
| Bill scheduling | records | 1 | 0 | Native records/view |
| Tax prep pack | records | 1 | 0 | Native records/view |
| Finance tracker eakarsu work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transactions | records | 1 | 0 | Native records/view |
| Products | records | 1 | 0 | Native records/view |
| Accounts | records | 1 | 0 | Native records/view |
| Paper Broker Controls | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 239 feature pages were visited in the browser; 237 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 142 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

142 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
