# Challenge XIV | Fintech <img src="https://instructure-uploads-pdx.s3.us-west-2.amazonaws.com/account_150420000000000001/attachments/590996/columbia.png" height="48" width="48">
---
This project is the fourtheen challenge in the Columbia Fintech Bootcamp.

This challenge deals with Trading algorithms, trading algorithms backtesting and machine learning with trading algorithms


The source data includes: 

* [OHLCV - Emerging Markets Index](./Resources/emerging_markets_ohlcv.csv) - An index that tracks emerging markets stocks.

The objective was to test a trading algorithms and the different predictions with Support Vector Machines and LogisticRegrssion

--

## Results



### Baseline Performance

The results for the baseline performance, (predicting whether the price increases or decreases), via Support Vector Machine, shows that when using the Predictions (shifted one timeslot), it would outperform the standard percent change in the given timeslot.
<img src="./assets/cummulative_return.png" >


--

## Technologies

The main language is Python, with the following auxiliary modules/libraries.
Python version is 3.7, developed in an independent conda virtual environment

### pandas
This module handles DataFrames (dynamic tables), to maniupulate, store data, do automatic calculations and adding dynamic data.

And also Pandas DateOffset for time calculations

### pathlib
This module helps abstracting the OS discrepancies between folder structures and files.

### numpy
Library for generic Math calculations (in this case average)


### skleark

Library for machine learning model creation, processing, testing, evaluation and reporting, in this case SVC (support vector machine), Logistic Regression and classification report metrics

---


### Clone repository
```bash
git clone https://github.com/lumiroga/fintech-challenge14.git`
```
---

## Usage

Open the terminal

Go to solution folder in your local computer

```bash
cd ./fintech-challenge14
jupyter machine_learning_trading_bot.ipynb
```


---

## Contributors

[lumiroga](https://github.com/lumiroga)

---

## License

* mpl-2.0 | Mozilla Public License 2.0