<div align="center">

# Hey, I'm Sourabh 👋

### I build things to understand them.

I'm an **IPM student at IIM Bodh Gaya** building around **quantitative finance, financial modelling, markets, research, and software**.

I like taking something that looks complicated on paper, understanding the machinery underneath it, and turning it into software that makes the idea easier to explore.

<p>
<a href="https://www.sourabhpradhan.in/">Portfolio</a>
&nbsp;•&nbsp;
<a href="https://www.sourabhpradhan.in/writing">Writing</a>
&nbsp;•&nbsp;
<a href="https://linkedin.com/in/sourabh-pradhan07">LinkedIn</a>
&nbsp;•&nbsp;
<a href="mailto:karbburn@gmail.com">Email</a>
</p>

</div>

---

## What I Build

Most of my work sits somewhere between **mathematics, finance, research, and software engineering**.

I'm particularly interested in:

- **Quantitative finance**: options, volatility, fixed income, factor models, valuation
- **Financial modelling**: DCFs, transaction models, forecasting, scenario analysis
- **Research software**: turning datasets and statistical methods into usable tools
- **Market systems**: understanding how assets, factors, rates, and macro events interact
- **Applied software**: building the APIs, data pipelines, engines, dashboards, and infrastructure around the analysis

A recurring principle across my projects:

> **Understand the model. Implement the machinery. Make the result explorable.**

---

# 🚀 Selected Projects

## 💼 Accord

**Corporate finance & M&A transaction analysis**

[Live](https://accord.sourabhpradhan.in)

An India-focused transaction modelling platform connecting the workflow from company analysis and valuation to deal structure, financing, synergies, pro forma statements, and EPS accretion.

- Driver-based financial forecasting
- DCF, WACC/CAPM, and trading comparables
- Transaction structure and Sources & Uses
- Debt financing and purchase price allocation
- Synergy modelling and phasing
- Three-statement pro forma analysis
- EPS accretion / dilution
- Scenario analysis and full-model sensitivities
- Deal-specific valuation and financing solvers
- Calculation lineage and model diagnostics

**Stack:** Python · FastAPI · Next.js · TypeScript · PostgreSQL · Supabase

---

## 📊 Valence

**Equity valuation & financial modelling workbench**

[Live](https://valence.sourabhpradhan.in)

A financial modelling platform connecting financial data, forecasting, assumptions, valuation, accounting checks, and model outputs.

- Multi-source financial data ingestion
- Driver-based 5-year forecasting
- Base, Bull, and Bear scenarios
- CAPM-based WACC
- FCFF DCF with multiple terminal value methods
- Reverse DCF growth solver
- Public trading comparables
- Football-field valuation
- PE exit returns and IRR waterfall
- Automated accounting and model QA
- Dynamic 30-tab Excel model generation
- Real-time web modelling dashboard

**Stack:** Python · FastAPI · Pydantic · OpenPyXL · SQLite · Next.js · React · TypeScript

---

## 📐 PathPricer

**Option pricing, volatility, and risk**

[Live](https://pathpricer.sourabhpradhan.in) · [Source](https://github.com/karbburn/PathPricer)

What started as a Monte Carlo vs Black-Scholes comparison grew into a broader options research platform.

- Black-Scholes-Merton pricing and Greeks
- Five Monte Carlo estimators
- Variance reduction techniques
- Implied volatility solvers
- P&L attribution across risk factors
- Multi-leg strategy analysis
- Scenario stress testing
- Heston stochastic volatility and calibration
- SVI volatility surface fitting
- Model validation
- Black-Scholes vs Heston delta-hedging comparison

**Stack:** Python · FastAPI · NumPy · SciPy · Next.js · TypeScript · Tailwind · Recharts

---

## 📈 BondFactor

**Fixed-income risk analytics for Indian Government Securities**

[Live](https://bondfactor.sourabhpradhan.in) · [Source](https://github.com/karbburn/BondFactor)

A fixed-income analytics platform for fitting yield curves, measuring bond risk, and studying portfolio behaviour under curve scenarios.

- Nelson-Siegel-Svensson yield-curve fitting
- Zero-coupon bootstrapping
- Parallel shift scenarios
- Steepener / flattener
- Twist and butterfly shocks
- Duration and convexity
- DV01
- Key Rate Duration
- Portfolio-level scenario P&L

**Stack:** Python · FastAPI · SciPy · Next.js · TypeScript · Supabase

---

## 🌏 MacroPulse

**Event-driven macro analysis for Indian markets**

[Live](https://macropulse.sourabhpradhan.in) · [Source](https://github.com/karbburn/macropulse-in)

A research platform for studying how Indian financial markets behave around major macroeconomic events.

Tracks:

**RBI MPC · CPI · IIP · NIFTY 50 · USD/INR · India VIX · 10Y G-Sec**

Combines event windows, surprise analysis, market reactions, and research-oriented visualisation.

**Stack:** Python · FastAPI · Next.js · Supabase · Recharts

---

## 💊 DistrictDx

**Pharmaceutical market attractiveness across India**

[Source](https://github.com/karbburn/DistrictDx)

A district-level framework for evaluating pharmaceutical market attractiveness across **all 785 Indian districts**.

Combines demographic, health, economic, and geospatial data to construct market attractiveness measures and distinguish present conditions from future potential.

**Stack:** Python · Pandas · SciPy · Next.js · D3.js · Tailwind CSS

---

## 📉 Factor Exposure Analyzer

**What is actually driving a stock?**

[Live](https://factor-analyzer.sourabhpradhan.in) · [Source](https://github.com/karbburn/factor-exposure-api)

Rolling factor regressions across the **NIFTY 500**.

Measures exposure to:

**Market · Value · Momentum · Size · Volatility**

The computationally heavy analysis is pre-computed through GitHub Actions and served through a FastAPI backend for fast interactive exploration.

**Stack:** Python · Pandas · Statsmodels · Scikit-learn · FastAPI · Next.js · Supabase · GitHub Actions

---

## 📉 NIFTY Gap Lab

**From market observations to a testable options strategy**

[Source](https://github.com/karbburn/NIFTY-Gap-Lab)

A research project studying NIFTY 50 opening gaps by weekday, mapping those observations into an ATM options strategy, and testing the result through historical backtesting.

The emphasis is on explicit assumptions, transparent methodology, and clearly stated limitations.

**Stack:** Python · FastAPI · Black-Scholes · yfinance · Chart.js

---

## 🔗 CorrShift

**Detecting changing relationships across markets**

[Live](https://corrshift.sourabhpradhan.in) · [Source](https://github.com/karbburn/correlations-anomaly-detector)

Rolling correlation and anomaly detection across:

**NIFTY 50 · USD/INR · Gold · Brent Crude · 10Y G-Sec Yield · FII Net Flows**

The idea is simple: relationships that usually behave a certain way sometimes stop doing so. CorrShift tries to surface those changes.

**Stack:** Python · FastAPI · Next.js · D3.js

---

## 📱 ClassWidget

**Your timetable, on your home screen.**

[Source](https://github.com/karbburn/ClassWidget)

A Flutter Android scheduling app built around a simple idea: your next class should be visible without opening the app.

- Excel / CSV timetable import
- Three home-screen widget sizes
- Live "Up Next" countdown
- Unified classes and tasks timeline
- SQLite persistence
- Kotlin Android bridge
- Material 3 UI

**Stack:** Flutter · Dart · Kotlin · SQLite · Riverpod · Android

[MIT License](https://github.com/karbburn/ClassWidget/blob/main/LICENSE)

---

# ✍️ Research & Writing

I write technical notes to understand the mathematics behind the models I use.

The current sequence moves from the basic mechanics of derivatives into stochastic processes, stochastic calculus, and the foundations of modern option pricing:

**Options → Brownian Motion → Geometric Brownian Motion → Itô Calculus → Black-Scholes → Risk-Neutral Pricing**

### The current notes

- **What Exactly Is an Option?**  
  The mechanics of calls, puts, payoffs, intrinsic value, time value, and why uncertainty matters.

- **The Language of Fluctuation**  
  Random walks, Brownian motion, and the foundations of modelling continuous uncertainty.

- **The Geometry of Fluctuation**  
  Bachelier vs Geometric Brownian Motion, multiplicative price dynamics, and the volatility correction.

- **The Extra Term**  
  Quadratic variation and the derivation of Itô's Lemma from Brownian motion.

- **The Frontier of Certainty**  
  Dynamic replication, delta hedging, the Black-Scholes PDE, and the heat-equation transformation.

- **The Measure of Arbitrage**  
  Girsanov's theorem, risk-neutral pricing, martingale measures, and market completeness.

### [Read my writings →](https://www.sourabhpradhan.in/writing)

I generally prefer understanding what sits underneath a model before treating the model as a black box.

---

# 🛠️ Toolbox

### Languages
`Python` `TypeScript` `Dart` `SQL`

### Quant & Data
`NumPy` `Pandas` `SciPy` `Statsmodels` `Scikit-learn`

### Quantitative Finance
`Black-Scholes` `Monte Carlo` `Stochastic Calculus` `Factor Models` `Fixed Income` `DCF` `Financial Modelling`

### Backend
`FastAPI` `PostgreSQL` `Supabase` `REST APIs`

### Frontend
`Next.js` `React` `Tailwind CSS` `Recharts` `D3.js`

### Mobile
`Flutter` `Kotlin` `SQLite` `Android`

### Infrastructure
`Git` `GitHub Actions` `Docker` `Vercel` `Render`

---

# 🌱 Currently Exploring

**Quantitative finance**  
Volatility modelling, fixed income, market regimes, and factor behaviour

**Financial systems**  
Valuation infrastructure, transaction modelling, and research workflows

**Mathematical finance**  
Stochastic calculus, derivative pricing, arbitrage, and risk-neutral valuation

**AI & software**  
Agents, automation, and better ways to turn analysis into useful products

---

<div align="center">

### Build something. Break it. Understand why.

<p>
<a href="https://www.sourabhpradhan.in/">Portfolio</a>
&nbsp;•&nbsp;
<a href="https://github.com/karbburn">GitHub</a>
&nbsp;•&nbsp;
<a href="https://linkedin.com/in/sourabh-pradhan07">LinkedIn</a>
&nbsp;•&nbsp;
<a href="mailto:karbburn@gmail.com">Email</a>
</p>

</div>
