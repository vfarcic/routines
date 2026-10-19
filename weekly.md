## GitHub Repositories

I would like to know how well my repos are doing in terms of usage and adoption (e.g., stars, forks, etc.). I want to know how well they are performing overall, and especially during the last 30 days compared with historical data.

The repos are:

- vfarcic/dot-agent-deck
- vfarcic/dot-ai-website 
- vfarcic/dot-ai-stack 
- vfarcic/dot-ai 
- vfarcic/dot-ai-infra 
- vfarcic/dot-ai-cli
- vfarcic/dot-ai-headlamp
- vfarcic/dot-ai-controller

## Upcoming trips

I would like to know which upcoming trips within the next 15 days I have pending. The information is in my Google Calendar (viktor@farcic.com).

## Upcoming non-recurring meetings

I would like to know which meetings I have scheduled during the week.

## Stocks

I am interested only in tech or tech-adjacent stocks from US or EU. I want to know which stock you would recommend and that specific moment in time by doing deep analysis.

My profile (use these defaults — don't ask again):
- Time horizon: long-term (3+ years)
- Risk tolerance: balanced
- Objective: capital growth
- Base currency: EUR. I buy US stocks by converting euros to dollars, so my US holdings carry EUR/USD currency risk (a stronger euro lowers my euro-denominated returns on them); my EU holdings are priced in EUR and have no such conversion effect.

For every stock analyzed, include its P/E ratio (both trailing and forward), and
state whether each figure is GAAP or non-GAAP/adjusted. Data sites commonly mix the
two (trailing GAAP, forward non-GAAP consensus), which makes them not directly
comparable — say so when they are mixed.

Where trailing and forward P/E diverge by more than ~30%, verify the cause against
the actual income statement and report it: one-off gains or losses, acquisition
amortisation, or genuine expected earnings growth. Do not assert a cause you have
not checked.

The stocks you should analyze should be a combination of stocks from my list, as well as other stocks on the market you recommend are good investments.

My current list:
- ASME (ASML)
- SND.DE (Schneider Electric; on Xetra)
- MSFT (Microsoft)
- NVDA (NVIDIA)
- GOOGL (Alphabet Class A)
- AMZN (Amazon)
- AVGO (Broadcom)
- SAP (SAP SE; on Xetra)
- ENR.DE (Siemens Energy; on Xetra)
- AEU (Prysmian; on Xetra)

For stocks in that list, I want to know whether I should sell them, buy more, or hold.

For other stocks, I want to know whether it is a good moment to buy.

Screen at least 15 candidates from across the tech and tech-adjacent universe, then
do full deep analysis on the 8 most promising and give a clear buy / wait / avoid
call on each. List the screened-but-cut names one line each with the reason they
were cut, so I can see what was considered and not just what survived.

Spread the candidates across different parts of the stack — semiconductors and
equipment, software, data-centre power and cooling, networking, EU-listed names —
rather than returning several versions of the same bet. State explicitly whether the
recommendations would all fail in the same scenario, and if they would, say so
rather than presenting them as diversified.

Stocks I'm NOT interested in (exclude these — do not analyze or recommend them):
- META (Meta Platforms)
- TSM (TSMC) — and more broadly any company whose main production is in Taiwan
  (invasion/blockade tail risk is too binary for my profile; my holdings already carry
  it indirectly through NVDA, AVGO, and ASML)

Do deep analysis.

Distinguish what you verified from a primary source from what you inferred. If you
have not checked something, say so rather than offering a plausible explanation.

After completing all of the above, pick the single best buy right now — considering both my current list and your additional recommendations together — and explain in detail why it is the top pick over the alternatives (weigh valuation including trailing and forward P/E, growth, risk, EUR/USD exposure, and fit with my profile). Make a clear, decisive single choice rather than a shortlist.

Every call (buy / sell / hold / wait / avoid, and the top pick) must be actionable on the
day of the report. Do not defer a decision to a future event ("buy after Q3 results",
"upgrade if earnings confirm"). Upcoming earnings are a risk to weigh in today's call,
not a reason to postpone it; next week's report re-evaluates with the new information.
If a stock is not a buy today, say so plainly.

Before naming the top pick, run a dedicated verification pass on the top pick and the
runner-up yourself (do not just relay a research subagent's summary). For each, check:
- Multi-year price trend (at least 3–5 years, not only distance from the 52-week high),
  and the cause of each major leg down. A large drawdown is a question to investigate,
  not an entry signal — say whether the decline came from a falling multiple while
  earnings grew, or from deteriorating fundamentals.
- Whether any "guidance raised" is organic or only from acquisitions or currency.
- Multi-year revenue and EPS growth trend (accelerating or decelerating), margin and
  capex direction, free cash flow, and beta/volatility versus my balanced profile.
- Concentration and tail risks: what single event (geopolitical, customer, regulatory)
  would impair the investment, and how much of that risk my holdings already carry.

If the pick fails this pass, demote it and verify the next candidate the same way.

If I decide to buy or sell stocks, the list in this prompt should be updated.

---

Output the report here and also send it to Telegram via the `telegram` MCP (`send_message`) with chat_id `8356372653` (bot @dot_agent_deck_bot). Always pass the explicit chat_id — do not rely on the "most recent chat" default. Note: Telegram chats don't render Markdown tables, so send a concise, chat-friendly version (HTML `parse_mode` with bold headers and bullet lists, not tables).