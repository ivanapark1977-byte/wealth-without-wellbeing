# Wealth Without Wellbeing

**Comparative Governance & Quality of Life Analysis**

A data-driven investigation into why Gulf States — and Qatar in particular — systematically underperform on quality of life despite extraordinary wealth.

---

## 📊 Overview

This report analyzes quality-of-life outcomes for 28 high-income countries across ten indicators, with all scores adjusted for GDP per capita to isolate the contribution of governance from the raw effect of national wealth.

**Scope:** 28 high-income countries  
**Metrics:** 10 composite indicators  
**Method:** GDP-adjusted percentile residuals  
**Data Period:** 2022–2024

---

## 🔍 Key Findings

1. **Gulf Cooperation Council states are the worst performers** in a 28-country, GDP-adjusted quality-of-life analysis, occupying the bottom four positions without exception.

2. **Qatar ranks last** despite being the wealthiest country in the dataset ($114,000 GDP per capita), falling 50–75 percentile points below predicted scores on governance-controlled metrics.

3. **Government type is the primary driver** of wellbeing performance. Social democracies occupy every top position; authoritarian monarchies occupy every bottom position.

4. **These outcomes reflect deliberate governance choices**, not resource constraints or cultural inevitability.

---

## 📈 Metrics Analyzed

| Metric | Source | Year |
|--------|--------|------|
| Happiness score (0–10) | World Happiness Report | 2024 |
| Life expectancy (years) | WHO Global Health Observatory | 2022 |
| Human Development Index (0–1) | UNDP Human Development Report | 2023/24 |
| Social trust (%) | World Values Survey Wave 7 | 2017–22 |
| Road deaths per 100,000 | WHO Road Safety Report | 2023 |
| Gini coefficient | World Bank / OECD | 2019–23 |
| Healthcare Access & Quality Index | IHME Global Burden of Disease | 2022 |
| Environmental Performance Index (0–100) | Yale Center for Environmental Law | 2022 |
| Press Freedom Index (0–100) | Reporters Without Borders | 2023 |
| Corruption Perceptions Index (0–100) | Transparency International | 2023 |

---

## 🌍 Country Coverage

**Gulf States (GCC):**
- Qatar
- United Arab Emirates
- Saudi Arabia
- Kuwait

**Comparator Countries (24):**
- **Nordic/N.Europe:** Finland, Denmark, Norway, Sweden, Iceland, Netherlands, Germany
- **Liberal Democracies:** Switzerland, Ireland, Australia, New Zealand, Canada, UK, Japan, Austria, Belgium, France
- **Flawed Democracies:** USA, Spain, Italy, South Korea, Israel
- **Hybrid Regimes:** Singapore
- **Authoritarian:** China

---

## 📉 The Qatar Deficit

Qatar's actual percentile rank vs. GDP-predicted performance:

| Metric | Actual | Predicted | **Deficit** |
|--------|--------|-----------|-------------|
| Press freedom | 4th percentile | ~80th | **−76 pts** |
| Environment (EPI) | 7th percentile | ~82nd | **−75 pts** |
| Social trust | 4th percentile | ~75th | **−71 pts** |
| Healthcare (HAQ) | 11th percentile | ~80th | **−69 pts** |
| Road safety | 18th percentile | ~85th | **−67 pts** |

---

## 🔬 Methodology

### GDP-Adjusted Residual Method

1. Each metric is **z-score normalized** across the 28-country dataset
2. **Linear regression** fitted between normalized GDP per capita and each metric's z-score
3. **Residual = actual score − GDP-predicted score**
4. Positive residuals = overperformance relative to wealth
5. Negative residuals = underperformance relative to wealth

For the composite ranking:
- Ten z-scored metrics are equally weighted and averaged
- Regression applied to composite score
- Results color-coded by government type (EIU Democracy Index 2023)

---

## 🏛️ Government Type Classification

| Type | Avg. Rank | All Positive Residuals? |
|------|-----------|------------------------|
| Social democracy | 4th | ✅ Yes |
| Liberal democracy | 13th | ✅ Yes |
| Flawed democracy | 17th | ⚠️ Mixed |
| Hybrid regime | 19th | ⚠️ Borderline |
| Authoritarian monarchy | 26th | ❌ No |
| One-party state | 24th | ❌ No |

---

## 🇳🇴 Norway vs 🇶🇦 Qatar: The Oil Wealth Comparison

Both are oil-rich states. The governance choices diverge completely:

| Dimension | Norway | Qatar |
|-----------|--------|-------|
| **Political system** | Parliamentary social democracy | Absolute monarchy |
| **Press freedom** | 87.5 / 100 (world-leading) | 14.7 / 100 (dataset-worst) |
| **Social trust** | 73% | 19% |
| **Road deaths** | 1.9 / 100k | 12.1 / 100k (6.4× worse) |
| **CO₂ per capita** | ~6 tonnes | ~32 tonnes |
| **Taxation** | Yes — accountability follows | None — no accountability |
| **Migrant rights** | Full legal rights | Kafala system |

**Norway's GDP:** $82,000  
**Qatar's GDP:** $114,000

Qatar is 39% richer yet delivers measurably worse outcomes across every governance-controlled dimension.

---

## 📚 Structure

### Report Sections

1. **Executive Summary** — Central findings
2. **Methodology** — Country selection, metrics, GDP-adjustment method
3. **The Gulf States Paradox** — Why extraordinary wealth fails to produce wellbeing
4. **Qatar: A Case Study in Governance Failure** — Migrant worker system, environmental failure, press freedom crisis
5. **The Role of Religion and Culture** — Wahhabist doctrine, gender exclusion, rentier dynamics
6. **Government Type as the Primary Driver** — Democracy premium, authoritarian mechanisms
7. **UAE vs Qatar: Divergent Paths** — Cosmopolitan integration vs. insularity
8. **Norway and the Nordic Model** — Deliberate institutional choices
9. **Conclusions** — Implications for Gulf states and international community

### References

24 academic and institutional sources including:
- World Happiness Report
- WHO Global Health Observatory
- UNDP Human Development Report
- World Values Survey
- Transparency International
- Reporters Without Borders
- Yale Environmental Performance Index
- Research by Putnam, Norris & Inglehart, Beblawi & Luciani

---

## 🎨 HTML Template

The report uses **The Anglophone Blind Spot** custom template featuring:

### Design System
- **Colors:** Warm palette (ink `#1a1a18`, red `#A32D2D`, background `#fafaf7`)
- **Typography:** Playfair Display (headings), Source Serif 4 (body), JetBrains Mono (data)
- **Layout:** Sticky masthead, numbered sections, heavy dividers

### Components
- Executive summary boxes (dark background, numbered findings)
- Stat cards (colored values: red/green/amber)
- Data tables with hover states and highlighted cells
- Callout boxes (standard/amber/green variants)
- Glossary grids
- Reference list with footnote linking

### Responsive Features
- Mobile-optimized (breakpoint at 768px)
- Collapsing navigation
- Stacked stat grids on mobile
- Readable typography at all screen sizes

---

## 🚀 Usage

### View the Report

Open `wealth-without-wellbeing.html` in any modern web browser.

### Host on GitHub Pages

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select **main** branch as source
4. Access at `https://[username].github.io/wealth-without-wellbeing/`

### Customize

The template is documented with clear instructions:
- Replace `[BRACKETED]` content with your own data
- Use existing CSS classes (never modify the `<style>` block)
- Follow the component examples for tables, callouts, and stat cards

---

## 📖 Citation

If you reference this analysis, please cite as:

```
Park, Ivana (2026). Wealth Without Wellbeing: Why Gulf States — and Qatar 
in Particular — Systematically Underperform on Quality of Life Despite 
Extraordinary Wealth. The Anglophone Blind Spot.
```

---

## 📄 License

This report is published under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to:
- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit to The Anglophone Blind Spot

---

## 🔗 Links

- **Publication:** [The Anglophone Blind Spot on Substack](https://ivanapark1.substack.com)
- **Live Report:** [View HTML](wealth-without-wellbeing.html)
- **Data Sources:** See [References](#-structure) section in report

---

## 🤝 Contributing

This is a published report, but feedback is welcome:

1. **Data corrections:** Open an issue with source documentation
2. **Methodology questions:** Use GitHub Discussions
3. **Typos/formatting:** Submit a pull request

Please note: Core findings and analysis reflect the author's research and will not be modified based on political disagreement.

---

## 📧 Contact

**The Anglophone Blind Spot**  
Independent investigative journalism covering geopolitics, energy, and governance.

- Substack: [ivanapark1.substack.com](https://ivanapark1.substack.com)
- Subscribe: [Get new reports via email](https://ivanapark1.substack.com/subscribe)

---

## ⚠️ Disclaimer

All estimates are presented as ranges and clearly labeled where they are not directly sourced. Methodology for statistical calculations is fully disclosed in the report. This analysis reflects research conducted through April 2026 using the most recent available data for each metric.

---

<p align="center">
  <strong>The Anglophone Blind Spot</strong><br>
  Investigative journalism • Data analysis • Geopolitics
</p>

<p align="center">
  © 2026 The Anglophone Blind Spot
</p>
