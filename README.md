java c
BU.232.620 Empirical Project 1 (Linear Econometrics for Finance)
Introduction In   this   empirical   work   we   aim   to   explore   the   factors   that   drive   the   returns   on   stock   portfolios,   according   to   the   seminal   work   of Fama   and   French   (   1993).   Same   as   the   Fama   and   French   (   1993),   combing   with   the   asset-pricing   model,   time-series   regression   is   applied.   Monthly   returns   on   stocks   and bonds   are regressed   on the returns to   a   market   portfolio   of stocks   and   mimicking   portfolios   for size, book-to-market equity   (BE/ME), and term-structure risk   factors   in returns.   Our   findings   reveal   that market excess return plays a substantial role in   explaining the   variations   in returns,   although the   explanatory power varies among different portfolios.
Data Description In   this   work,   data   including   monthly   return   series   of the   25   stock   portfolios,   as   well   as   the   market excess   return   factor,   are   all   from   Ken   French’s   Data   Library.   Specifically,   Monthly   market   excess   return   (Mkt-RF),   size   factor   (SMB),   and   book-to-market   factor   (HML),   Risk-Free   Rate   (RF)   is   defined   as   the   Monthly   returns   of a   one-month   Treasury   bill.   Moreover,   Returns   on   25   portfolios   formed   on   the   intersections   of   five   size   groups   (ME1   to   ME5)   and   five   book-to-market   equity   groups   (BM1 to   BM5).
Following tables present the Mean,   Standard Deviation and T-Statistics of   the portfolio intersections, which is applied to further discussion.

Table   1 ：Mean of   Portfolio Intersections

Table   2: Standard   Deviation   of   Portfolio   Intersections

Table   3: T-Statistics   of   Portfolio   Intersections

Figure   1: OLS Regression ResultsIn this case, because the lowest T-statistics (2.38)   is   larger than   the   2.064,   which   is   the   critical   value   at   95%   significance   level   and   24   degree   of freedom,   the   null   hypothesis:   the   means   equal   to   zero   will    be    rejected    at    95%    significnace      level.    And      accoding      to      the      OLS      Regression      Model,      the skewness   equals to   0.329   and kurtosis   equals to    13.884, which   shows these   returns   do   not   follow   a   normal distribution.
Models and Findings 
To analyze the impact of   market factors on the 25 portfolios, we   employed   a   time-series   regression   model:
Rt−Rf= α+β(Mkt-RF)+ϵt 
Where   Rt   is   the   return   of   the   portfolio   at   time   t, Rf   is   the   risk-free   rate   at   time   t代 写BU.232.620 Empirical Project 1 (Linear Econometrics for Finance)Prolog
代做程序编程语言,   Mkt-RF   is   the       market excess return, α is the intercept, β   is the   coefficient   of   the portfolio to   the   market   excess return.
Following tables present the result from regression about these parameters:

Table 4:β the coefficient
All 25 portfolios have positive Beta coefficients, indicating strong and positive   sensitivity to market   excess returns.

Table 5: T-Statitics   on   βBecause    all    the    T-statistics    on    β      is    larger    than      the      2.064,      which      is      the      critical      value      at      95%   significance   level   and   24   degree   of freedom,   the   null hypothesis:   The   loadings   of the   25 portfolios   on the market portfolio significantly equal to zero should be rejected   at   95%   significnace   level.Table6: R² Goodness   offitThe   R² values   suggest that the market   factor   explains   a   large   portion   of   their   return   variation.   Most   of   the intersections   ’   R² value is larger than 0.7, and all   intersections   ’   R²   is   larger than   0.5,   showing   a   great   explanation   power   of   our   regression   model. R² indicates   how   much   of   the   time   series   variation in   the   return   of each   portfolio   is   explained   by   the   market   excess   return   (MKT   -   RF),   for   example,   Portfolio ME1 BM1 has   an R²   of 0.511, meaning   that   51.1%   of   its   return   variation   is   accounted   for by the market excess return.
Conclusion According to the empirical study especially from the time-series regression,   it   is   comfirmed   that      the   market    excess    return      explains       a      significant    proportion      of    the      variation      in      returns      for      many   portfolios.   However,   evethough   all   portfolios   have   over   0.5   goodness   of fits,       some   of them   with   ralatively   R²   values   indicate   the   potential   for   additional   explanatory   variables.   After   reading   the   Fama   and   French   (   1993),   factors   such   as   size   (SMB)   and   book-to-market   (HML)   are   expected   to   incorprate into the regression model to better capture the variations in returns.In   summary,   this   project   indicated   the   importance   of market   factors   in   explaining   portfolio   returns   while   also   emphasizing   the   limitations   of   using   the    single-factor   model,   as   only   market   excess   return   (MKT   -   RF)   is   considered   .   Further   enhancements   could   improve the   explanatory power, by   adding more varaibles in the model to better explain the returns   ’   variations.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
