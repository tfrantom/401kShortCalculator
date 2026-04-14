# 401kShortCalculator
An overly smart tool for an incredibly dumb idea. Entirely vibe-coded

# The Idea
## What if you could use your 401k to "short" the market, mostly tax-free?
In most 401k contribution plans, you can take out a loan against your account, which (usually) works the following way:
* You take out a loan for some amount against your 401k.
* That amount of underlying stocks owned by the account is liquidated and payed to you as a disbursment.
* You pay back the amount as monthly payments (or lump sums), at which time stocks are re-purchased for your account at the price when the payment processes. Interest is post-tax, but also buys stocks on payment.

So, what if you take out a loan against your 401k, _with the intention that the stock price will **drop**?_ Depending on several parameters, you might even _make_ money by doing this vs. continuing normal contributions during an expected economic downturn. 

## This calculator/simulation tool was born out of that incredibly stupid idea. 
This was built in a single night, entirely vibe coded, with minimal testing. No results of using this tool should be used to make financial decisions, **ever**.

## Running
* download `401kShortCalculator.html` and run it in your browser.

This project may get flushed out further with more robust tests and baseline simulations,  TBD.

## Potential future ideas:
* Be able to give it some real market data and play a simulation across that as the model. Move the buyback date around to see what-if impacts
* Add in an even dumber idea, "what if you take the money from that loan and _buy_ other stocks with it?". Leveraged trading with these loans could make for some fun graphs
* Do some robust simulations by "hand" and compare to the tool. It's not been very well tested at this point, and the unit tests were also vibe-coded.


