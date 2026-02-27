# 🛒 SuperStore Analytics Dashboard

A premium, fully responsive business intelligence dashboard built from the Superstore dataset. Designed with **color psychology** so anyone — even a non-data person — can instantly understand the insights.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `superstore_responsive_dashboard.html` | ⭐ Main interactive dashboard — open in any browser |
| `superstore_charts.py` | Python script to auto-generate 12 chart PNGs from your CSV |
| `Superstore_PowerBI_Dashboard_Guide.docx` | Complete Power BI build guide with DAX measures |
| `charts/` | 12 pre-generated chart PNGs from real data |

---

## 🚀 Quick Start

### Option 1 — Open the HTML Dashboard (No install needed)
```bash
# Just download and open in browser
open superstore_responsive_dashboard.html
```

### Option 2 — Generate Charts with Python
```bash
# Install dependencies
pip install matplotlib seaborn pandas

# Run with your CSV
python superstore_charts.py --csv Sample_-_Superstore.csv --out ./charts
```

---

## 📊 Dashboard Pages

| Page | Focus | Color |
|------|-------|-------|
| 💰 Revenue & Sales | Total revenue, annual growth, category breakdown | **Gold** = money |
| 📊 Profit & Losses | Margins, loss-makers, discount impact | **Green** = profit · **Red** = loss |
| 🗺️ Regional Map | West vs East vs Central vs South | Each region = its own color |
| 👥 Customers | Consumer, Corporate, Home Office segments | **Blue / Green / Purple** |

---

## 🎨 Design Philosophy

Every color has **one psychological job**:
- 🟡 **Gold** → Sales, Revenue (money, aspiration)
- 🟢 **Green** → Profit, Growth (safe, go)
- 🔴 **Red** → Loss, Alert (danger, stop)
- 🔵 **Blue** → Information, Regional data (trust, geography)
- 🟣 **Purple** → Premium segments (niche, quality)

---

## 📱 Responsive Breakpoints

| Device | Layout |
|--------|--------|
| Desktop (1200px+) | 4-column KPIs, side-by-side charts |
| Tablet (768–1200px) | 2-column KPIs, stacked charts |
| Mobile (480–768px) | Single column, scrollable tabs |
| Small phone (<360px) | Emoji-only tabs, full single column |

---

## 🔑 Key Insights from the Data

- 📈 **$2.30M total revenue** across 2014–2017, growing every year
- ⚠️ **Tables lost $17,725** despite $207K in sales — discount problem
- 🚨 **Texas lost $25,729** — biggest state-level loss
- 🏆 **West region** leads with $725K sales and 14.9% margin
- 🏠 **Home Office** has the best profit margin at 14.0%
- 💡 Discounts above 30% consistently destroy profit margins

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (CSS Variables, Grid, Flexbox, clamp()), Vanilla JS
- **Charts:** Chart.js 4.4.1
- **Python Charts:** matplotlib, seaborn, pandas
- **Fonts:** Playfair Display + Outfit + JetBrains Mono
- **Data:** Superstore CSV (9,994 rows)

---

## 📋 Power BI Setup

See `Superstore_PowerBI_Dashboard_Guide.docx` for:
- Column type configuration
- 20+ DAX measures (Sales YoY, Profit Margin, Loss Orders, etc.)
- 4-page report architecture
- Cross-slicer sync setup
- Conditional formatting rules

---

*Built with real Superstore data · Designed for clarity at first glance*
