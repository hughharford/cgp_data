---
status:
date:
decision-makers:
consulted:
informed:
---

# <!-- short title, representative of solved problem and found solution -->

## Context and Problem Statement

CondorGP is a fintech AI project using Genetic Programming (GP).
The project needs organised, date partitioned data, to run numerous backtests.
The aim is to trade on the stockmarket, fully autonomously.

Backtesting is the first stage.
Paper trading follows once solid backtest results are achieved.
Live trading, successfully to make profit is the end goal.

The GP algorithm runs repeated backtests, as the algorithm is evolved.
Each backtest will run on 1 month's data.
The granularity of the data will be initially daily, and then hourly.

COSTS
Minimising cost is very important.

DATA LEAKAGE
Ability to keep track of what data has been tested on is important.
Data leakage between train and test datasets is critical.

The initial requirements are for financial index data (S&P 500, FTSE 100), and
the requirement is for OHLCV (Open High Low Close Volume) data.

Other data requirements will be defined once the first month of data from
both S&P500 and FSTE100 is available.

## Decision Drivers

* <!-- decision driver -->

## Considered Options

* <!-- option -->

## Decision Outcome

Chosen option: "", because

### Consequences

* Good, because
* Bad, because

### Confirmation



## Pros and Cons of the Options

### <!-- title of option -->

* Good, because
* Neutral, because
* Bad, because

## More Information
