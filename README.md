# openbi-portfolio

Public **Frozen / journal** page screenshots from [OpenBI Studio](https://www.openbi.no/) packs.
Synced into the Orbit site `/portfolio` `#openbi` section the same way [powerbi-portfolio](https://github.com/AlexTouvras/powerbi-portfolio) feeds Power BI.

**Not included:** Studio projects, gold parquet, raw tapes, prediction drafts, Interactive labs.

## Packs

| Folder | Title | Pages |
|--------|-------|------:|
| `01-ecommerce-churn-retention` | Ecommerce Churn Retention | 12 |
| `02-mortgage-vintage-pd` | Mortgage Vintage PD | 16 |
| `03-mortgage-lifecycle-monitor` | Mortgage Lifecycle Monitor | 5 |
| `04-mortgage-stream-drift` | Mortgage Stream Drift | 10 |
| `05-credit-origination-scorecard` | Credit Origination Scorecard | 14 |
| `06-household-budget-shares` | Household Budget Shares | 14 |
| `07-medicare-peer-review` | Medicare Peer Review | 9 |
| `08-online-retail-segments` | Online Retail Segments | 12 |
| `09-online-retail-association` | Online Retail Association | 12 |
| `10-online-retail-sequences` | Online Retail Sequences | 8 |
| `11-insect-stream-drift` | Insect Stream Drift | 10 |
| `12-electricity-market-drift` | Electricity Market Drift | 10 |
| `13-finnish-vehicle-market-intelligence` | Finnish Vehicle Market Intelligence | 6 |

## Refresh (local)

From the private OpenBI workspace (Studio running):

```powershell
python scripts/export_orbit_openbi.py
```

That updates this repo's `NN-slug/screenshots` + READMEs. Then push `main`.
Orbit picks up changes via `npm run openbi:sync` or the GitHub Action.

## Licence

Screenshots and captions © Alex Touvras. Underlying public datasets keep their own licences (noted on each Studio pack SPEC, not duplicated here).
