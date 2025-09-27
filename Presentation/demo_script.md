# Demo Walkthrough — TradeMorph StrategyLab

## Overview
- **Duration:** ~12 minutes  
- **Audience:** prospective users, product mentors, and early investors  
- **Objective:** Showcase how TradeMorph helps a manual trader convert rules into a working algo skeleton.  
- **Format:** Semi-live walkthrough using prototype screens and prepared backtest results.  

---

## Setup (before the session)
- ✅ Browser-ready demo account with sample dataset  
- ✅ 3 pre-configured example strategies (momentum, mean reversion, breakout)  
- ✅ Screenshot/video backups for each critical screen  
- ✅ Stable internet connection + fallback offline deck  

---

## Script Outline

### 1. Opening context (1 min)
**Narrative:**  
“Meet Aarti, a retail trader who has traded successfully with a moving-average checklist but feels exhausted watching charts daily. TradeMorph gives her a bridge: turn those checklists into algo code without learning to program.”

**Stats to mention:**  
- ~3 million active retail traders in India  
- Fewer than 15% have adopted any form of automation  
- Top barrier: coding complexity + fear of losing control  

---

### 2. Step One — Capturing a strategy (3 min)
- **Action:** Show the “Strategy Wizard” opening screen.  
- **Demo:** Fill in fields: “Momentum Breakout,” select NIFTY futures, timeframe = 15m.  
- **Message:** “Feels like filling out a trading journal — not coding.”  

---

### 3. Step Two — Rule building (3 min)
- **Action:** Drag “Price crosses 20-day high” into canvas → Add volume confirmation filter.  
- Add risk module: stop-loss at 2%, target 6%, position size = 2% of equity.  
- **Show:** Auto-generated preview on the side (“if SMA20 > SMA50 … order_target_percent(…)”).  
- **Message:** “Every block creates both a visual flow and readable code — transparency builds trust.”  

---

### 4. Step Three — Backtesting (3 min)
- **Action:** Click “Run Backtest.”  
- **Show:** Progress indicator then summary panel:  
  - Return: +94% (3 years)  
  - Sharpe: 1.9  
  - Max drawdown: -14%  
  - Win rate: 71%  
- **Visuals:** Equity curve vs manual benchmark, monthly P&L heatmap.  
- **Message:** “In under a minute, Aarti sees if her rules really held up historically.”  

---

### 5. Step Four — Transition modes (2 min)
- **Action:** Navigate to Execution dashboard.  
- **Modes shown:**  
  1. Manual log  
  2. Semi-auto (alerts + approve/skip)  
  3. Auto (fully hands-free)  
- **Simulation:** Show alert for RELIANCE breakout with confidence score → click “Approve.”  
- **Message:** “Traders choose their pace of automation — no cliff jump required.”  

---

## Anticipated Q&A (with prepared answers)
- **Accuracy?** “We validate with multiple datasets; preview always shows underlying math.”  
- **What if strategy decays?** “Performance monitor flags degradation; user can pause or edit.”  
- **How different from Streak/Tradetron?** “Focus is on *conversion workflow + code export*, not just drag-drop or social copy.”  
- **Learning curve?** “Most testers built and tested first strategy in <1 hour.”  

---

## Contingency Plan
- If demo fails live → switch to backup video.  
- If time short → skip to backtest summary and execution modes.  

---

## Closing (1 min)
Reinforce:  
1. **Simple**: checklist-to-algo in minutes  
2. **Trustworthy**: transparent code export  
3. **Gradual**: manual → hybrid → auto  

**Call to action:** “With early support, we can bring thousands of manual traders into algorithmic trading safely and confidently.”
