<div align="center">

# Hey, I'm Sourabh 👋

### I build analytical software that makes markets, data, and ideas easier to explore.

I'm an **IPM student at IIM Bodh Gaya** building around **quantitative finance, financial modelling, markets, and data**.

I enjoy taking ideas that usually live inside research papers, spreadsheets, or trading terminals and turning them into systems people can actually interact with.

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

## Why I Build

Most of my projects start with a question.

How should an option be priced?  
What happens when the yield curve moves?  
What is actually driving a stock?  
How does a macroeconomic event transmit through markets?  
What does a real transaction model look like?

I like going underneath the interface, understanding the mathematics and assumptions, building the engine, and then making the result explorable.

> **Understand the model. Build the machinery. Make the result explorable.**

---

# 🚀 Things I've Been Building

## 💼 Accord

**Corporate finance & M&A transaction analysis**

[Live](https://accord.sourabhpradhan.in)

An India-focused transaction modelling platform connecting company analysis, valuation, deal structure, financing, synergies, pro forma statements, and EPS accretion in one connected model.

- Driver-based forecasting and DCF valuation
- WACC/CAPM and trading comparables
- Sources & Uses, debt financing, purchase price allocation
- Synergy modelling and three-statement pro forma analysis
- EPS accretion / dilution and credit metrics
- Scenario analysis, sensitivities, and deal-specific solvers
- Calculation lineage and model diagnostics

**Stack:** Python · FastAPI · Next.js · TypeScript · PostgreSQL · Supabase

---

## 📊 Valence

**Equity valuation & financial modelling workbench**

[Live](https://valence.sourabhpradhan.in)

A financial modelling platform connecting data ingestion, normalization, forecasting, valuation, accounting QA, and Excel model generation.

- Driver-based 5-year three-statement forecasts
- Base, Bull, and Bear scenarios
- CAPM-based WACC and FCFF DCF
- Reverse DCF and valuation sensitivities
- Public comps and football-field valuation
- PE exit returns and IRR waterfall
- Automated accounting and model QA
- Dynamic 30-tab Excel model exporter

**Stack:** Python · FastAPI · Pydantic · OpenPyXL · SQLite · Next.js · React · TypeScript

---

## 📐 PathPricer

**Option pricing, volatility, and risk**

[Live](https://pathpricer.sourabhpradhan.in) · [Source](https://github.com/karbburn/PathPricer)

What started as a Monte Carlo vs Black-Scholes comparison grew into a broader options research platform.

- Black-Scholes-Merton pricing and Greeks
- Five Monte Carlo estimators
- Implied volatility solving
- P&L attribution and multi-leg strategies
- Scenario stress testing
- Heston calibration and stochastic volatility
- SVI volatility surface fitting
- Delta-hedging and model comparisons

**Stack:** Python · FastAPI · NumPy · SciPy · Next.js · TypeScript · Tailwind · Recharts

---

## 📈 BondFactor

**Fixed-income analytics for Indian Government Securities**

[Live](https://bondfactor.sourabhpradhan.in) · [Source](https://github.com/karbburn/BondFactor)

An interactive fixed-income platform for fitting the yield curve, measuring risk, and studying portfolio behaviour under curve scenarios.

- Nelson-Siegel-Svensson yield-curve fitting
- Zero-coupon bootstrapping
- Parallel shifts, steepeners, flatteners, twists, and butterflies
- Duration and convexity
- DV01 and Key Rate Duration
- Portfolio scenario P&L

**Stack:** Python · FastAPI · SciPy · Next.js · TypeScript · Supabase

---

## 🌏 MacroPulse

**Event-driven macro analysis for Indian markets**

[Live](https://macropulse.sourabhpradhan.in) · [Source](https://github.com/karbburn/macropulse-in)

A research platform for studying market behaviour around major Indian macroeconomic events.

**RBI MPC · CPI · IIP · NIFTY 50 · USD/INR · India VIX · 10Y G-Sec**

Combines event windows, surprise analysis, market reactions, and interactive visualisation.

**Stack:** Python · FastAPI · Next.js · Supabase · Recharts

---

## 💊 DistrictDx

**Pharmaceutical market attractiveness across India**

[Live](https://districtdx.sourabhpradhan.in) · [Source](https://github.com/karbburn/DistrictDx)

A statistical framework covering **all 785 Indian districts**, combining demographic, health, economic, and geospatial data to evaluate pharmaceutical market attractiveness.

Produces district-level **Overall, Chronic, and Acute** indices with current-state and future-trajectory views.

**Stack:** Python · Pandas · SciPy · Next.js · D3.js · Tailwind CSS

---

## 📉 Factor Exposure Analyzer

**What's really driving your returns?**

[Live](https://factor-analyzer.sourabhpradhan.in) · [Source](https://github.com/karbburn/factor-exposure-api)

Rolling factor regressions across the **NIFTY 500**.

**Market · Value · Momentum · Size · Volatility**

The heavy analysis is pre-computed through GitHub Actions and served through a FastAPI backend for interactive exploration.

**Stack:** Python · Pandas · Statsmodels · Scikit-learn · FastAPI · Next.js · Supabase

---

## 📉 NIFTY Gap Lab

**From weekday gap probabilities to an options strategy**

[Live](https://nifty-opt-sim.onrender.com) · [Source](https://github.com/karbburn/nifty-option-simulator)

A research and backtesting tool studying weekday-to-weekday NIFTY 50 gaps and turning those probabilities into systematic CE/PE trade rules.

- Weekday-pair gap probability analysis
- Wilson confidence intervals and sample guards
- Black-Scholes option pricing
- GTT-style premium exit ladder
- In-sample vs out-of-sample diagnostics
- Interactive trade and equity-curve dashboard

**Stack:** Python · FastAPI · Black-Scholes · yfinance · Chart.js

---

## 🔗 CorrShift

**Detecting changing relationships across markets**

[Live](https://corrshift.sourabhpradhan.in) · [Source](https://github.com/karbburn/correlations-anomaly-detector)

Tracks rolling relationships across:

**NIFTY 50 · USD/INR · Gold · Brent Crude · 10Y G-Sec Yield · FII Net Flows**

Uses rolling correlations and anomaly detection to surface periods where historically stable relationships begin behaving differently.

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
- Native Kotlin Android integration
- Material 3 interface

**Stack:** Flutter · Dart · Kotlin · SQLite · Riverpod · Android

---

# ✍️ Research & Writing

I write technical notes alongside the software.

The current series follows a progression through the foundations of mathematical finance:

**Options → Brownian Motion → Geometric Brownian Motion → Itô Calculus → Black-Scholes → Risk-Neutral Pricing**

### The series

**What Exactly Is an Option?**  
The mechanics of calls, puts, payoffs, intrinsic value, and time value.

**The Language of Fluctuation**  
Brownian motion and the mathematical language of continuous uncertainty.

**The Geometry of Fluctuation**  
Geometric Brownian Motion and multiplicative asset-price dynamics.

**The Extra Term**  
Quadratic variation and the emergence of Itô's Lemma.

**The Frontier of Certainty**  
Dynamic replication, delta hedging, the Black-Scholes PDE, and its transformation.

**The Measure of Arbitrage**  
Girsanov's theorem, risk-neutral pricing, martingale measures, and market completeness.

### [Read my writings →](https://www.sourabhpradhan.in/writing)

---

# 🛠️ Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,ts,react,nextjs,tailwind,postgres,flutter,dart,kotlin,docker,git,githubactions,vercel&perline=7" />

</div>

<p align="center">
NumPy · Pandas · SciPy · Statsmodels · Scikit-learn · FastAPI · Supabase · Recharts · D3.js
</p>

---

# 🌱 Currently Curious About

Quantitative finance, volatility modelling, fixed income, market microstructure, financial modelling infrastructure, mathematical finance, and AI systems that are actually useful.

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
