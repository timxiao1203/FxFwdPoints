# FX Forward Curve 

Overview

	FX forward curve is also called FX implied forward curve or FX derived curve. It is derived from USD zero rate curve and FX forward spreads and used to value FX trades. 

	Market standard is to use FX quoted forward spreads and USD zero rate curve to generate FX implied forward curve. In other words, FX curve construction generates an interest rate curve of the quoting currency from the interest rate curve of the base currency. The construction methodology is based on the arbitrage-free relationship between forward FX rates and the discount rates of the two currencies.

	Summary

	FX Forward Curve Introduction
	FX Forward Curve Construction
	Market Inputs and Curve Outputs

FX Forward Curve Introduction

	The term structure of FX forward curve, also known as FX implied forward curve, is defined as the relationship between the currency zero rate and maturity.
	The settlement dates for the given underlying tenors.
	Application of the market conventions for O/N and T/N points. O/N is overnight rate and T/N is tomorrow next.

FX Forward Curve Construction

	FX forward cure is derived using the arbitrage-free relationship between forward FX rates and the discount rates of two currencies. It is also called interest rate parity.
	D_Q=S/F D_B 	where S is the spot foreign exchange rate, F is the forward foreign exchange rate, D_Q the discount factor of the quoted currency, and D_B the discount factor of the base currency.
	Forward foreign exchange rate is determined by FX forward spreads. A forward spread is the difference between spot rate and forward rate. It is quoted as the number of basis points.

Inputs and Outputs

	Spot FX rate
	USD zero rate curve or discount curve.
	FX forward spread:
	
Quote Name	Forward Spread
USD/CNH O/N	9.0
USD/CNH T/N	5.75
USD/CNH 1W	41.0
USD/CNH 1M	154.0

	Outputs
	
Tenor	Zero Rate
6/27/2014	0.00989
7/7/2014	0.01013
8/27/2014	0.01085
9/27/2014	0.01126



References:

https://finpricing.com/lib/EqConvertible.html

https://bitbucket.org/timxiao1203/fxforwardpoint/downloads/FxForwardCurve-8.pdf

