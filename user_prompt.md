Current Time: {{ $now.toISO() }}

---

## MARKET DATA (Top 10 Gainers)

The following is Binance 24h top gainers data for short-selling screening:

{{ JSON.stringify($json.marketData) }}

---

## CURRENT POSITIONS

The following are current short positions held. Skip these symbols:

{{ JSON.stringify($json.positions) }}

---

Analyze the above data according to system instructions. Output pure JSON only.
