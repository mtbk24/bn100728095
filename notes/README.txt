This is a very long burst.  Very long bursts appear to be washed out at BGO energies.  Not enough emission later on in the burst for the BGO to be good.  This will make it hard to assess a rsp1 vs rsp2 file comparison.


grbm:   good.  the BGO data dives downward and the LAT data goes upward.  Thinking maybe a copl+lpow might be better.

sbpl:  same as grbm.  better BIC.

copl:  not a good fit at high energies but had just as good of a BIC as grbm.

grbm+lpow:  not sure why the BIC was worse than grbm.  grbm+lpow looks better than grbm.  has just as good as an aic as grbm.

sbpl+lpow:  PL insignificant because it's at such a steep angle -0.573871 and the amplitude is 3E-10.  Not a good fit because of this.  Although stats are better than grbm+lpow, this is not a good fit.  THe PL in grbm+lpow was acceptable as it is not here.

copl+lpow:  no errors because the fit would change and give a steep PL with a bad stat fit.  The PL slope of -1.95801 i believe is best.


grbm+blackb:  good fit.  Best AIC so far.

copl+blackb:  good fit and errors.  Best AIC and 2nd best BIC after sbpl.

grbm+blackb+lpow:  all params were reasonable.  Errors on PL and band's beta had issues as expected for a complex model.

sbpl+blackb+lpow:  all params were reasonable.  There was a T flag in just about every parameter.  Program had a hard time getting errors for this fit.  Things like this happened: Apparent non-monotonicity in statistic space detected.
Current bracket values -0.928447, -0.915642
and delta stat 2.29437, 671570
but latest trial -0.922045 gives 949243
Suggest that you check this result using the steppar command.
     1     -1.10947    -0.922045    (-0.0909807,0.0964418)


copl+blackb+lpow:  only 1 sigma errors possible.  The PL had bad errors.




