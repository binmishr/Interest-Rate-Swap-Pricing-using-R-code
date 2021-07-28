# Interest-Rate-Swap-Pricing-using-R-code

A fixed versus floating interest rate swap exchanges a stream of cash flows determined by 1) a predetermined fixed rate and 2) floating rates which will be determined periodically in the future respectively. Since we don’t know exactly the evolution of floating rates in the future, forward rate is used for the alternative variable coupon rate, which is implied in the market forward looking information. Market participants expect the forward rate to be the expected future rate in the perspective of fair pricing. 

It is worth noting that floating rates are determined at refixing dates before its corresponding interest periods in advance. Whenever we price a swap, its first variable cash flow is always known but remaining cash flows are unknown. For this unknown future variable rates, we use forward rates for its corresponding interest periods, which are implied in the current market yield curve. 

Swap pricing is to calculate the net present value (NPV), which is the difference between the sum of present values of fixed legs and floating legs.

we can calculate the price of Libor IRS. In this process, we discount cash flows by using Libor discount factors which is implied in Libor curve. But this approach is pre-crisis approach (prior to 2008 global financial crisis). These days Libor discounting is replaced by OIS (overnight indexed swap) discounting which is the post-crisis approach (after 2008 GFC). Next post will consider the same 5-year Libor IRS using OIS discounting. \(\blacksquare\) 

The R code is included in the .docx files. Please clone the repository and make .r extension file of the code included.
