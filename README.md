# biz-relatedness
A general interindustry relatedness index

Here is my R code for the general interindustry relatedness index of Bryce & Winter, 2009. The code can be just as well used to generate the time-variant relatedness index of Cetorelli, Jacobides and Stern, 2021. In my research, to compute this measure I make use of Finnish Patent and Registration Office's data on Finnish corporate groups. The dataset shows all the corporate group links between limited liability companies in Finland reported in official annual accounts. Based on these links, I calculate the frequency of joint occurrence of all two-digit NACE Rev.2 pairs in a corporate group and apply the frequency scores to portfolio ventures in my venture dataset.

References:

Bryce, D. J., & Winter, S. G. (2009). A general interindustry relatedness index. Management Science, 55(9), 1570-1585.

Cetorelli, N., Jacobides, M. G., & Stern, S. (2021). Mapping a sector's scope transformation and the value of following the evolving core. Strategic Management Journal.
