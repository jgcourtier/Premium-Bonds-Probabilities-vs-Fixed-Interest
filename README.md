# Premium-Bonds-Probabilities-vs-Fixed-Interest

This is an attempt to model the multinomial probabilities of UK NS&I Premium Bonds vs a standard taxable fixed rate savings account. The first cell shows the variance of differing bond sizes and their expected annual returns depending on where in the distribution your luck lands. This is an important aspect of premium bonds that people struggle to wrap their heads around - the variance of the prizes at low bond sizes makes it a poor cash savings vehicle, while the smaller variance and tax free returns of larger bond sizes make it a very appealing cash savings vehicle.

The second cell assumes there is a mathematical break point for this relationship, the point at which that entire amount of cash savings should be moved from a fixed rate taxable account to premium bonds. The break point is calculated using the median expected return from the specified bond size vs the post-tax annual return of a fixed rate saver. As this only uses the median, there's obviously a real possibility of under or overpeforming the fixed annual return beyond the breakpoint. As such, the shaded area shows the interquartile range of expected returns, in order to give a range of likely outcomes.

Some assumptions are made but of course are editable; a comparable interest rate of 3.8% AER, a higher rate tax payer, one year of savings returns, and that the comparable savings account is not a cash ISA and therefore taxable.

The probabilities of each prize value has been derived from the October 2026 draw. I will try to keep it somewhat up to date but the probabilities don't change drastically. For the purposes of this modelling, the jackpot values (2x £1,000,000) have been removed from the probabilities.
