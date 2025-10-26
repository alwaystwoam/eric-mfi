# 💎 ERIC MFI — Beginner’s Guide (for Robinhood Noobs)

### Goal  
Catch quick, high-probability bounces using **Money Flow Index (MFI)** and volume.  
You’re buying **in-the-money (ITM) calls** when momentum turns — and selling fast.

---

## 🧭 1. When to Trade
Only trade when:
- The stock is **big, popular, and liquid** (AAPL, NVDA, MSFT, SPY, QQQ).  
- The market is **stable or slightly up**, not crashing or reacting to news.  
- The **stock itself is trending up or flat**, not dropping hard.  
  *(If price is below VWAP or in a sharp downtrend, skip it.)*

🚫 **No trades** during market-wide drops, halts, or breaking news.

---

## 📊 2. Chart Setup
Use **1-minute**, **3-minute**, and **5-minute** charts with:
- **MFI (Money Flow Index)**
- **Volume bars**

> **1-min = entry and exit**  
> **5-min = trend confirmation (local pullback)**  
> **3-min = noise filter**

---

## ✅ 3. Entry Checklist

**Gate 0 — Session Context:**  
- The overall session must be **up or flat** — price above or near VWAP, or EMA20 on 5-min chart sloping flat/up.  
- Skip trades on full downtrend days.

**Step 1 — Entry Setup (1-min):**  
- **1-min MFI ≤ 20** (on a closed bar) → stock is oversold, bounce setup forming.

**Step 2 — Local Pullback Confirmation (5-min):**  
- **5-min EMA20 sloping downward** (the lower, the better).  
- **At least 3 consecutive red volume bars** (the more, the better).  
  → This confirms a **temporary pullback** inside an overall up/flat session.

**Step 3 — Trigger to Buy (1-min):**  
- On the 1-min chart, **MFI starts to rise** (mfi[0] > mfi[1]) **or** the **first small green candle** appears.  
- Avoid chasing **large reversal candles** — wait for a normal-sized bar or a tiny pullback if the first green candle is huge.

---

## 💵 4. Which Call Option to Buy

### For stocks **above $100:**
- Look about **$5 below** the current stock price (±$2).  
- Among those, choose the one with the **lowest premium / lowest % to breakeven.**  
  (This means you’re buying the most cost-efficient ITM call.)  
- It’ll usually have **0.70–0.80 delta**.

### For stocks **below $100:**
- Pick an ITM strike **2–3% below** the stock price.  
- Under $20? Go about **$1 below.**  
- Again, pick the **lowest premium / lowest % to breakeven.**

💡 *Example:*  
NVDA = $465 → check $460, $455, $450 calls → choose the one with **lowest premium % to breakeven.**

---

## 💰 5. How to Set Your Limit Order

### **A. Tight Spread (Ideal)**
- If bid = $4.50 and ask = $4.60 → **Limit Buy = $4.55** (midpoint).  
- This is the best and safest fill.

### **B. Wide Spread (Acceptable Exception)**
- If spread > ~5% and the stock is trending up → **Limit Buy = bid + $0.05**.  
- If it **doesn’t fill**, **skip the trade.**  
- Never chase up to the ask.

---

## 🎯 6. Exit Rules (Quick & Simple)

- **Primary exit:** Sell when **1-min MFI goes above 60.**  
  - If you’re **green**, take the profit.  
  - If you’re **not green**, cut it — failed bounce.  
- **Bonus exit:** If you’re up **8% or more**, **just sell and move on** — don’t overthink it.  
- **If MFI spikes near 80 but price goes sideways, exit immediately.**  
- **Stop loss:** still being refined. 20–30% drawdown is a **gauge**, not a hard rule.  
  Eric’s current view: *“Stop losses shouldn’t be automatic or based purely on percentage. That’s how people get trapped out of winning trades.”*

---

## ⏱ 7. Time Stop (Dynamic Rule)

You’re not exiting by a timer — you’re exiting by **momentum behavior**.

- If **after 5 minutes** the MFI hasn’t started rising → exit (setup failed).  
- If MFI is **rising from 20 → 40**, stay in — let it develop.  
- Keep holding while **MFI keeps climbing** and **price holds recent lows.**  
- If MFI **stalls (flat ±5)** for **3+ bars** → exit.  
- If MFI **crosses 60** or **spikes to 80**, sell immediately.  
- Never stay in longer than **20 minutes** total — theta will eat your profits.

✅ *Think of it this way:*  
Stay in **while momentum is alive**, exit the moment it dies — or if you’re already up 8%, just take it and move on.

---

## 📈 8. Position Size
- Use about **5% of your buying power per trade.**  
  (Ex: $30k account → $1,500 per trade.)  
- If the setup is very strong (5+ big red 5-min bars and clean trend) → you can **size up to 2x.**

---

## 🔁 9. Reset Before Next Trade
Wait until:  
- 1-min MFI drops back to **≤ 20**, and  
- 5-min shows **new red bars** in an up/flat session.

Then repeat.

---

## ⚠️ 10. Hard Don’ts
- ❌ Don’t buy when the market or stock is **crashing**.  
- ❌ Don’t chase fills above your limit.  
- ❌ Don’t trade options with **>5% spread** unless using the **bid+0.05** rule.  
- ❌ Don’t hold past MFI roll-over or 20-minute cap.

---

## 🧩 Example
- NVDA = $465  
- 1-min MFI = 18  
- 5-min EMA20 sloping down with 4 red bars, still above VWAP  
- You buy **$460 call**, this week expiry  
- Limit = **mid ($4.55)** or **bid+0.05** if spread wide  
- MFI rises → 1-min MFI hits 60 → **sell** (profit or cut).  
- Or if you’re already **+8%**, sell right there.  
- Total time: 5–12 minutes, one clean bounce.  

---

**Summary:**  
Buy efficient ITM calls when 1-min MFI ≤ 20, 5-min EMA20 slopes down with 3+ red bars inside an up/flat session.  
Exit when 1-min MFI > 60, you’re up 8%, or momentum stalls.  
Stop losses are currently **manual and discretionary**, used only as guidance — not automated.  
Stay disciplined, never chase, and never fight a falling stock.



---

## 🧠 Stop Loss Refinement (In Progress)
The stop loss logic for ERIC MFI is still being developed. The current 20–30% drawdown range is used only as a **visual gauge**, not an automated trigger.

Eric’s philosophy:
> “Stop losses shouldn’t be automatic or based purely on percentage. That’s how people get trapped out of winning trades.”

### Current Thinking:
- The stop mechanism should rely on **market structure and momentum**, not arbitrary numbers.  
- Better candidates being tested:
  1. **MFI behavior:** exits when 1-min MFI keeps falling or fails to recover for several bars after entry.  
  2. **Candle structure:** exits when price closes below the **last swing low** or breaks structure on 1-min.  
  3. **Volume exhaustion:** if volume surges again while MFI stays low → signal failed bounce.  
  4. **Dynamic trailing logic:** scaling out on partial recoveries, cutting remaining size if MFI rolls back down.

Once refined, this section will define a **single unified exit rule** combining MFI, structure, and price confirmation — replacing the percentage-based guideline.

