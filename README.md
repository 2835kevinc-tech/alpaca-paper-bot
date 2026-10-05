# Project A: Webull Alert Bot (REAL money, flag-only)

Authority: research and notify ONLY.
- NEVER call any Webull place_*/order tool. NEVER fund, transfer, buy or sell.
- Read-only data tools only (quotes, bars, earnings calendar, positions).
- Max 3 positions. Account about $38 now (may grow to $75-$100 after Alpaca proves out).
- Flag format: ticker | why | entry zone | stop price | sell target | max shares/dollars.
- Flag times: ~5:00 AM, ~3:30 PM, weekend review (user works 5:30am-2:40pm).
- Cash account: sale proceeds settle next business day; do not count them as spendable same day.
- Own files only: portfolio.csv, watchlist.md, flags-log.md. No Alpaca keys or data here.
- Stop rule: pause alerts if user says "pause"; stop-out = total dollars deposited, not just balance.
