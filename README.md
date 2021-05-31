# FX Touch Option Introduction and Valuation Guide

Overview
A touch option is a transaction with one or two barriers. The buyer of the option will get a cash amount either if the barrier is touch or not touched.  Touch options are becoming increasingly popular because they pay much higher yields compared to high/low options. 
A touch option is the sort of option that promises a payout once the price of an underlying asset reaches or passes a predetermined level. Touch options allow investors to choose the target price, time to expiration, and the premium to be received when the target price is reached.  
There are only two possible outcomes. If the barrier is broken a trader will receive the agreed full payout. If the barrier isn’t broken, the trader will lose the premium paid to the broker. Unlike vanilla calls and puts, touch options allow investors to profit from a simplified yes-or-no market forecast. Like regular call and put options, most touch option trades can be closed before expiration for a profit or a loss depending on how close the underlying market or asset is to the target price. 
This type of option is popular with traders who believe the price of an underlying asset will pass a certain level in the future, and for those who aren’t sure whether the higher price level is a sustainable one. Speculative market participants like to use touch options as bets on a rising or falling exchange rate.
Clients, who prefer to hedge, trade touch options as a rebate in order to secure themselves compensation in case their strategy doesn’t work out. Touch options are also often integrated into structured products to increase returns on forward and interest rates. They become especially useful during times of market volatility when prices might be uncertain.
An investor who chooses no touch option type is trading on the assumption that the price of their selected asset will fail to reach a specific level before the end of the expiry period. The investor may trade touch options, if he believes that the price of their selected asset will reach a specific level before the end of the expiry period. This presentation provides an introduction to FX touch options valuation. 

	Introduction
	A touch option is the sort of option that promises a payout once the price of an underlying asset reaches or passes a predetermined level.
	Touch options allow investors to choose the target price, time to expiration, and the premium to be received when the target price is reached. 
	There are only two possible outcomes. If the barrier is broken a trader will receive the agreed full payout. If the barrier isn’t broken, the trader will lose the premium paid to the broker.
	Unlike vanilla calls and puts, one-touch options allow investors to profit from a simplified yes-or-no market forecast. 
	Like regular call and put options, most one-touch option trades can be closed before expiration for a profit or a loss depending on how close the underlying market or asset is to the target price. 
	Touch options are usually less expensive than double one-touch options, and are becoming very popular with commodity and Forex traders.

	The Use of FX Touch Option
	This type of option is popular with traders who believe the price of an underlying asset will pass a certain level in the future, and for those who aren’t sure whether the higher price level is a sustainable one.
	Speculative market participants like to use one-touch options as bets on a rising or falling exchange rate.
	Clients, who prefer to hedge, trade one-touch options as a rebate in order to secure themselves compensation in case their strategy doesn’t work out. 
	Touch options are also often integrated into structured products to increase returns on forward and interest rates
	They become especially useful during times of market volatility when prices might be uncertain.
	An investor who chooses no touch option type is trading on the assumption that the price of their selected asset will fail to reach a specific level before the end of the expiry period.
	The investor may trade touch options, if he believe that the price of their selected asset will reach a specific level before the end of the expiry period.


	Payoffs and Conditions.
	Depending on the barrier types, the touch option can be divided into the following categories: one touch up/down; no touch up/down; double one touch; double no touch; one touch down no touch up; one touch up no touch down.
	Barrier conditions for different types of touch options

	No touch up: 		S_t<B
	One touch up:		S_t≥B
	No touch down:		S_t>B
	One touch down:	S_t≤B
	Double no touch:	〖B_l<S〗_t<B_h
	Double one touch:	S_t≤B_l or S_t≥B_h
	One touch down no touch up:	S_t≤B_l or S_t<B_h
	One touch up no touch down:	S_t>B_l or S_t≥B_h
where
	B	the barrier
	B_l	the low barrier
B_h 	the high barrier
	The payoff currency could be either the cash (base) or the asset (underlying).

payoff=Nominal×S×1_condition	if the payout currency is asset
payoff=Nominal×1_condition	if the payout currency is cash

	Valuation
	Touch and no touch options are a great way for you to further customize your trading experience. Because there are only two different outcomes that can possibly occur, these are still considered to be binary options.
	The present value of a one touch option is given by

   
 






where
S 	the spot exchange rate
σ 	the annualized volatility of the underlying rate
r 	the domestic interest rate between spot date and delivery date
rf 	the foreign interest rate between spot date and delivery date
Te 	the expiry date
Td 	the delivery date
ε 	1 for a lower barrier, -1 for an upper barrier.   
N(x)	the standard normal cumulative distribution function
L	the barrier level
R	the domestic cash amount
w 	the rebate value

	A Real World Example
Delivery Type	Delivery	Barrier Level High	1.25
Buy Sell	Buy	Barrier Level Low	0
Call Put	Put	Barrier Option Type	Single Down And In
Currency One	CAD	Barrier Payment Time	At Maturity
Notional One	65000	Rebate Amount	0
Currency Two	USD	Barrier Window Start	1/17/2018
Notional Two	50000	Barrier Window End	1/17/2018
Strike Rate	1.3	Barrier Level High	1.25
Base Currency	USD	Barrier Level Low	0
Underlying Currency	CAD	Barrier Option Type	Single Down And In
Instrument	USD/CAD		
Trade Date	2/23/2017		
Maturity Date	1/17/2018		
Settlement Date	1/18/2018		
				

References:

https://finpricing.com/lib/EqBarrier.html

https://bitbucket.org/cmrm11/fxtouch/downloads/FxTouch-24.pdf


