Spilker et al. (2019), ApJ, 883, 81
===================================

[ADS](https://ui.adsabs.harvard.edu/abs/2019ApJ...883...81S/abstract) | [arXiv](https://arxiv.org/abs/1908.02294)

![Inside-out quenching](Fig5_radprofs.png)

This file contains the radial profiles for the z=2.3 compact galaxy COSMOS 27289, including
the profiles of Mstar (from HST F160W imaging), MH2 (from VLA CO(1-0)) and SFR (from ALMA 870um),
along with combinations of these to get profiles of sSFR = SFR/Mstar, fH2 = MH2/Mstar, and tdep = MH2/SFR.
These can be used to recreate Figures 4 and 5 in the paper (I can also provide the simulation profile
from Figure 6 on request).

The uncertainties come from Monte Carlo resampling the profiles within the uncertainties and
recalculating the profiles. The uncertainties are asymmetric, so there are three columns per value
in the above, one that gives the median (50th percentile) of the trials, and two uncertainties, where
the `_m` and `_p` subscripts give the lower (15.17th percentile) and upper (84.13th percentile) 
bounds on the uncertainty (i.e. the 1sigma / 68percent interval), respectively. So for example, 
to reproduce Figure 5 in the paper (shown above), you would plot the `fH2` curve as a line, and 
then fill between the values for `fH2_m` and `fH2_p`, which trace out the lower and
upper edges of the blue shaded region in the image above.


Citation
--------

    @ARTICLE{2018ApJ...860..103S,
           author = {{Spilker}, Justin and {Bezanson}, Rachel and {Bari{\v{s}}i{\'c}}, Ivana and
             {Bell}, Eric and {Lagos}, Claudia del P. and {Maseda}, Michael and
             {Muzzin}, Adam and {Pacifici}, Camilla and {Sobral}, David and
             {Straatman}, Caroline and {van der Wel}, Arjen and
             {van Dokkum}, Pieter and {Weiner}, Benjamin and {Whitaker}, Katherine and
             {Williams}, Christina C. and {Wu}, Po-Feng},
            title = "{Molecular Gas Contents and Scaling Relations for Massive, Passive Galaxies at Intermediate Redshifts from the LEGA-C Survey}",
          journal = {\apj},
         keywords = {galaxies: evolution, galaxies: high-redshift, galaxies: ISM, Astrophysics - Astrophysics of Galaxies},
             year = 2018,
            month = jun,
           volume = {860},
           number = {2},
              eid = {103},
            pages = {103},
              doi = {10.3847/1538-4357/aac438},
    archivePrefix = {arXiv},
           eprint = {1805.02667},
     primaryClass = {astro-ph.GA},
           adsurl = {https://ui.adsabs.harvard.edu/abs/2018ApJ...860..103S},
          adsnote = {Provided by the SAO/NASA Astrophysics Data System}
    }



