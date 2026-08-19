# Research Methodology

## Purpose

This document describes the methodology I currently use to design, test, evaluate and improve algorithmic trading systems.

My approach is experimental. A strategy is treated as a hypothesis that must be tested rather than as a trading idea assumed to be profitable.

## 1. Strategy Hypothesis

The process begins with a clearly defined market hypothesis.

The objective is to translate a trading idea into explicit rules that can be tested systematically.

These rules may concern:

- market trend;
- market structure;
- technical indicators;
- price action;
- entry conditions;
- exit conditions;
- stop-loss placement;
- take-profit logic;
- position sizing;
- risk management.

## 2. Rule Formalization

Before testing, discretionary observations must be converted into rules that can be executed consistently.

The objective is to reduce ambiguity between what I believe a strategy should do and what the system actually executes.

## 3. Historical Backtesting

The strategy is then evaluated on historical market data.

I analyze several dimensions, including:

- number of trades;
- win rate;
- profit factor;
- drawdown;
- risk/reward characteristics;
- performance stability;
- behaviour across different instruments and market conditions.

A strong historical result is treated as evidence for further investigation, not as proof of future profitability.

## 4. Forward Testing

Strategies that justify further evaluation can be tested in a demo trading environment.

Forward testing allows me to observe behaviour on market data that was not available during the historical development process.

I pay particular attention to differences between expected behaviour and actual execution.

## 5. Audit

When forward performance differs significantly from expectations, I investigate the trades rather than immediately changing the strategy.

The audit may examine:

- signal generation;
- execution timing;
- market conditions;
- trend filters;
- support and resistance;
- repeated entries;
- position concentration;
- volatility;
- risk management;
- differences between historical and forward behaviour.

The objective is to identify a specific failure mechanism before proposing a modification.

## 6. Improvement

A modification should address an identified problem.

Whenever possible, I avoid changing several major components simultaneously because this makes it difficult to determine which modification affected the results.

## 7. Retesting

Modified systems must be tested again.

The research cycle therefore becomes:

**Hypothesis → Rules → Backtest → Forward Test → Audit → Improvement → Retest**

This cycle may be repeated multiple times.

## Research Principle

The objective of my research is not to eliminate losing trades.

The objective is to determine whether a system can demonstrate sufficiently consistent behaviour, controlled risk and robustness to justify further evaluation.

## Current Limitations

My current algorithmic trading work remains experimental.

Forward testing is currently conducted in a demo environment, and the research documented here should not be interpreted as evidence of profitable real-money trading.
