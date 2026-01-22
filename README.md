# 📈 Ichimoku-Trading-Strategy

Quantitative Researcher | [Mustafa MAJJI](https://www.linkedin.com/in/mustafa-majji-meng-msc-3a59861a2/)

***
## 🚀 Project Overview

This project aims to develop a systematic trading strategy based exclusively on Ichimoku indicators.  
The strategy is applied to the S&P 500, with additional confirmation filters derived from gold prices, reflecting the observed correlation between equity markets and gold.

The Ichimoku-based strategy relies on the following core components:

---

## 📐 Ichimoku Indicator Formulas

Let:
- \( H_n \) = highest price over the last \( n \) periods  
- \( L_n \) = lowest price over the last \( n \) periods  

### 1. Tenkan-sen 

\[
\text{Tenkan-sen} = \frac{H_{9} + L_{9}}{2}
\]


### 2. Kijun-sen 

\[
\text{Kijun-sen} = \frac{H_{26} + L_{26}}{2}
\]


### 3. Senkou Span A

\[
\text{Senkou Span A} = \frac{\text{Tenkan-sen} + \text{Kijun-sen}}{2}
\quad \text{(plotted 26 periods ahead)}
\]
 

### 4. Senkou Span B

\[
\text{Senkou Span B} = \frac{H_{52} + L_{52}}{2}
\quad \text{(plotted 26 periods ahead)}
\]



### 5. Kumo (Cloud)

The **Kumo** is the area between **Senkou Span A** and **Senkou Span B**:

\[
\text{Kumo} = \left[ \text{Senkou Span A}, \text{Senkou Span B} \right]
\]

 ### 6. Chikou Span (Lagging Span)

\[
\text{Chikou Span} = \text{Closing Price}_{t}
\quad \text{(plotted 26 periods backward)}
\]


