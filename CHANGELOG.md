# PE Tycoon changelog

Each version is a frozen copy in `versions/pe-tycoon-vX.Y.html`. Open any of them in a browser to play that version.
`pe-tycoon.html` in this folder is always the latest one (the one published online).

## v2.1.4 — 2026-10-24
- Fixed the firm name box on the title screen sticking out past its panel.
- Now also hosted on GitHub Pages: https://newbieoo7.github.io/pe-tycoon/
- Saves from v2.1.3 carry over.

## v2.1.3 — 2026-10-22
- Borrowing − / + buttons now move the debt by one visible step per tap ($0.1M under $100M, $1M under $1B, $0.01B above), snapping to that step. Before, each tap moved it by about $30K, which didn't show in the rounded amount.
- The borrowing slider and its buttons span the full card width, with a thicker track and a larger handle.
- Saves from v2.1.2 carry over.

## v2.1.2 — 2026-10-22
- Card effects are visible again: hand cards show a two-line effect, and the selected-card bar shows the card's full effect under its name.
- Saves from v2.1.1 carry over.

## v2.1.1 — 2026-10-22
- **Operations is now a fixed, swipeable screen:** one company per page, swipe sideways (or tap the dots) to move between companies. Each company fits fully on screen without scrolling, including the card preview and Apply button.
- Compact company card for operations: stats in a 3×2 grid, debt / gauge / bank risk on one line, sell options as a 2×2 grid with sale previews, two-column card preview.
- Hand cards show name and type only (tap for the full effect); the selected-card bar is a single line with Cancel.
- Top bar: year moved into the stat grid, connections sit beside the firm name; hot/cold sector now shows as a tag on companies and on the map (and in the Market explanation).
- The operations tip shows once as a popup.
- Saves from v2.1 carry over.

## v2.1 — 2026-10-22
Phone playtest fixes.
- **Operations screen usable on phones:** the top bar now scrolls away instead of staying pinned; the page measures the real tray height so every company (including the last) scrolls fully above the tray; picking a card tucks the hand away into a slim "Scroll to a company and tap Apply" bar with Cancel; smaller tray cards (3-line effect); Hide/Show cards toggle.
- **Deck tab:** cards in rows of 3, resized to fit (also applies to conference cards).
- **Top bar:** all 9 stats visible at once in a 5-column grid (shorter labels: Cash, Return, Money, Paid out, Rep, Heat, Influence, Market, Interest); connections wrap instead of scrolling.
- Saves from v2.0 carry over.

## v2.0 — 2026-10-22
Graphic overhaul: Satirical Board Game style, mobile-first.
- **New look:** chunky ink outlines, offset shadows, bright game-piece colors, Lilita One + Nunito type. Everything drawn in code (icons, map, cards, gauges).
- **Mobile layout:** sticky top HUD (stat chips + connection icons), four bottom tabs (Play, Office, Deck, Log), hand tray fixed above the tabs during operations and boss fights.
- **Map** drawn as a board: paths, node icons, your route highlighted, market forecast down the side, boss at the top.
- **Cards** look like cards: type colors (Operations yellow, Finance mint, PR pink, Political blue, Shady coral), cost bubble, icon, illegal cards hatched.
- **Company sheets:** sector icon, health stamp, tappable stats, profit sparkline, debt-load gauge with risk pill, tappable trait chips.
- **Boss arenas:** doubt meter and question banner for the Pitch, tug-of-war stake bar for the Hostile Rival.
- **Juice:** numbers count up/down with floating +/− pop-ups, SOLD / ACQUIRED / BROKEN UP / SEIZED stamps, screen shake when the bank takes a company. Respects reduced-motion settings.
- **QoL:** Undo for legal moves within a year; drag a card up onto a company to play it; − / + buttons on the borrowing slider; sale preview (paid out and return before → after) on every sell button; year-end report after every year; "End the year?" warning for unspent actions and companies in Danger; red dots on tabs (companies in Danger, open cases or heat 60+, new log entries); confirmations for break-ups, letting the bank take a company, backing out of an auction, folding to Kestrel, and going to trial; first-run tips on each screen (can be turned off or reset in Office); glossary of every explanation in Office.
- Save slot changed (v1.x saves don't carry over).

## v1.3 — 2026-10-22
- **Connections bar** in the top status panel: every connection is a chip; tap it to see what it does.
- **Info buttons on company stats:** Yearly profit, Growth, Multiple, Value, Debt, Debt load, Your stake, Breakup value and Stake return each open an explanation, like the top bar.
- Saves from v1.2 carry over.

## v1.2 — 2026-10-22
Response to second playtest notes.
- **Playbook viewer:** "Playbook" button shows hand, draw pile and discard pile (also works mid-boss).
- **Networking Lunch** plays instantly, no preview.
- **Card types:** every card is Operations, Finance, PR, Political or Shady. Types matter in boss fights.
- **Influence:** new "Call in a favor" panel every year (Government contract, Tip-off, Lean on a bank, Fast-track a deal, Cool things down). Each favor used costs +1 for the rest of the fund. Influence now only *delays* crime stories (evidence comes back, on hold for a year) and can't touch severe crimes.
- **Jail roll on every illegal act:** minor 0.5%, serious 1.5%, severe 3%, multiplied by heat (×1 at 0, ×1.6 at 30, ×2.2 at 60, ×2.8 at 90). Shown on every illegal card and choice. Getting caught ends the run.
- **Heat tiers force events:** 30+ a reporter digs up your worst evidence every year; 60+ yearly audit (fine, one fewer action next year); 90+ raid. Heat cools 5/year (was 8). Investors find 25% of your evidence at each fundraise (−0.1 each).
- **Investor Pitch** is now fought with your own deck: 5 cards a round, your normal actions, damage by card type and your real results. Investors telegraph their question and how much doubt it adds unless you play the right card type.
- **Black Monday (harder):** 6 scenes, crash −25% market and −15% profit, banks demand under 4.5×, new "Investors Panic" scene. You get one hand of 5 cards for the whole crisis; scenes have options that need a specific card type.
- **Hostile Rival (harder):** fought with your deck (each type has a takeover effect), Kestrel starts at 25% with a bigger war chest and buys 12–18 points a round, plus bluff, poison pill, read tells, fold.
- Save slot changed (v1.1 saves don't carry over).

## v1.1 — 2026-10-22
Response to first playtest notes.
- **Plain language:** EBITDA → Yearly profit, MOIC → Return, Carry → Your bonus, Equity → Your stake, Leverage → Debt load, Bandwidth → Actions, LPs → Investors, distributions → Paid out. Real term shown in small text. Fees, Multiple/Value and Diligence unchanged. Tap any ⓘ stat for an explanation.
- **Card previews:** selecting a card shows the exact before → after on each company (profit, growth, value, debt, stake, bank risk, cash, reputation, heat, evidence) plus odds for random effects.
- **Stats that matter:** Reputation tiers (Legendary/Respected/Known/Shady/Toxic) change prices, unlock private deals, and Toxic bars you from auctions. Influence is useful from Fund I (kill stories, drop investigations, calm banks, permits, antitrust) and earned at retreats and conferences.
- **Rates & market made readable:** market mood (Cold/Cool/Normal/Warm/Hot) and bank interest follow a visible cycle with a 2-year forecast on the map. Hot markets bring more auctions and exit windows; cold ones bring distressed sellers.
- **Debt trade-off:** interest rises with debt load (−1% up to +6%), yearly sector downturns, "chance the bank takes it" shown per company and live on the borrowing slider, low-debt companies grow 1% faster, "Safe hands" fundraise bonus.
- **New bosses:** Fund I The Investor Pitch (4-round card fight against a Doubt bar), Fund II Black Monday (5-scene branching crash story), Fund III The Hostile Rival (5-round takeover duel with bluffs and dirty tricks). Bosses are shown on the map from Year 1. Antitrust is now a regular event.
- **Illegal path as a gamble:** stronger illegal cards (Creative Accounting +40%, Insider Tip, Rig the Auction, Fake Buyer, Skim the Fund, Bribe a Pension Manager), evidence severity (minor/serious/severe, 3/5/8 years) with per-item odds shown, heat thresholds (30 reporters, 60 under watch with 20% caught on the spot, 90 raid that freezes fund cash), harsher fines (15–35% of your money), auction bans, company seizure, prison.
- Save slot changed (v1.0 saves don't carry over).

## v1.0 — 2026-10-22
First playable version (mechanics only, minimal UI).
- 3 funds x 7 years, Slay-the-Spire-style map: Deal, Auction, Distressed, Conference, Golf Retreat, Event, Exit Window
- Bosses: LP Annual Meeting, Rate Shock, Antitrust Review
- 2 founders: Ex-Investment Banker, Former Operator
- 8 sectors, failing/steady/thriving companies, 12 hidden traits, paid due diligence
- Debt slider, interest, covenants (7x), dividend recaps
- 31 playbook cards (legal / gray / illegal), bandwidth, deck drafting
- 16 connections (relics)
- Exits: sell to PE, strategic sale, break up; merge same-sector companies into platforms
- Fund close: fire sale or continuation fund; fundraise score vs target; 2% fees + 20% carry above 1.30x
- Heat, evidence with 5-year expiry, investigations (reporter > regulator > subpoena > trial/prison)
- Bribery with hidden official traits (Greedy, Unreliable, Already Bought, Honest, Wired, Escalator)
- Lobbying from Fund II: 3 laws, opposition, election repeals
- Autosave, Hall of Firms, end-of-run newspaper
