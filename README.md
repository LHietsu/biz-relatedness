# biz-relatedness
A general interindustry relatedness index

Here is my R code for the general interindustry relatedness index of (Bryce & Winter, 2009). The code can be very easily converted into the time-variant relatedness index of Cetorelli, Jacobides and Stern, 2021. In my research, to compute this measure I make use of Finnish Patent and Registration Office's data on Finnish corporate groups. The dataset shows all the corporate group links between limited liability companies in Finland reported in official annual accounts. Based on these links, I calculate the frequency of joint occurrence of all two-digit NACE Rev.2 pairs in a corporate group and apply the frequency scores to portfolio ventures in my venture dataset. For portfolios of more than two ventures, I compute the average of all frequency scores of the different pairings in the portfolio.
