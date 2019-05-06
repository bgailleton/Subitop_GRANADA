# Subitop_GRANADA

**I am at the registration desk right now fi you scan my QR code and want more info**

Support git-hub repository for my poster in TopoEurope Conference, Granada, May 2019. It contains the animations correspondng to the figures on the right side. *Apparently the gif does not show up on mobile automatically, you can either download them or switch your internet browser to computer mode. (You can also call me and I'll have my computer.)*

## Model outputs

Model has been running for 2 millions years: Builduing the mountain range to steady-state and then ponding the northern forland basin. It get filled by sediments and slightly uplifted, before being captured.

**Evolution of the topography:**

![Alt Text](https://github.com/bgailleton/Subitop_GRANADA/raw/master/topo.gif)

**Topographic Slope:**

![Alt_Text](https://github.com/bgailleton/Subitop_GRANADA/raw/master/slope.gif)

**k_sn and river evolution:**

![Alt_Text](https://github.com/bgailleton/Subitop_GRANADA/raw/master/ksn_evolution.gif)

**Long river profile of the central basins:**

This shows the evolution of the rivers in the central basins. The northern river gets aggraded and then captured by the south one.
Note how the knickpoint is stationnary despite the abscence of lithologic contrasts.

![Alt_Text](https://github.com/bgailleton/Subitop_GRANADA/raw/master/long_profile_captured.gif)

## Method 

The model uses Yuan et al., 2019 and Braun et Willett, 2013 to simulate erosion, continental deposition and linear hillslope processes. I'll upload the model parameters if anyone wants. I used an homemade python bindings to `fastscapelib-fortran` and `lsdtopytools` respectively for the modelling and topographic analysis of the output. All the code are open-source but early-development so just contact me if interested.

If you want to use fastscapelib-fortran:
[fastscapelib-fortran](https://fastscape-lem.github.io/fastscapelib-fortran)











## Test to display gif on github

Ignore that:

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)
