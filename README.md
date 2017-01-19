# missing-transits
*Making sure all the Kepler transits are accounted for*

The project is straight forward:

- get light curves for all transiting planets found in *Kepler* and K2 w/ no known TTV or other weirdness
- use the best-fit emphemeris (*t_0*) and orbital period (*P*)
- for the entire light curve, make sure the transit is present and accounted for
- any light curve with good data, but a missing transit is a candidate for:
  - a [SETI signal](https://arxiv.org/abs/1603.08928)
  - a very weird resonance or extra planet monkey business
  - revising the period and ephemeris

These might all get filtered out by the transit validating pipeline, so would be worth doing this for all transit *candidates*
