# **nep-des**

<p>

  <img src="https://github.com/user-attachments/assets/795fe8a0-7e58-4298-b6ee-09089c0728d6"
       align="left"
       width="320"
       style="margin-right: 50px; margin-bottom: 10px;">
  This code produces <strong>period-radius diagrams</strong> with the population-based <strong>boundaries</strong> of the <strong>exo-Neptunian landscape</strong> as derived in 
  <a href="https://ui.adsabs.harvard.edu/abs/2024A%26A...689A.250C/abstract">
  Castro-González et al. (2024)</a>. It also generates plots showing the <strong>density trends</strong> for 
  super-Neptunes and sub-Saturns presented in
  <a href="https://ui.adsabs.harvard.edu/abs/2024A%26A...691A.233C/abstract">
  Castro-González et al. (2024b)</a> and Castro-González et al. (2026). 
  
  **No installation is required.** Simply **download** this repository and run [`nep_des.ipynb`](https://github.com/castro-gzlz/nep-des/blob/main/nep_des.ipynb). You can prepare the [User configuration](nep_des.ipynb#user-configuration) cell, run the (collapsed) cells in the main code block, and execute any of the **plotting cells**. In the following, we show **examples** covering the **three types of plots** that can be generated. The configuration cells for each example can be found [here](aux/config_examples.ipynb). For issues/suggestions, please feel free to [contact me](mailto:amadeo.castro-gonzalez@unige.ch).
                                                      
</p>


## 1. The exo-Neptunian landscape: desert, ridge, and savanna

In the left panel ([example#1](aux/config_examples.ipynb)), we contextualize several unusually short-period planets located within the core of the Neptunian desert. In the right panel ([example#2](aux/config_examples.ipynb)), we place a sub-Saturn in the broader exo-Neptunian landscape (desert, ridge, and savanna) and highlight it with a text box.

<img width="5390" alt="examples1 2" src="https://github.com/user-attachments/assets/6699d958-c044-42e4-80c5-5dce00abee5f" />


## 2. The exact boundaries

We can also generate the **exact KDE-derived desert boundaries**. These boundaries are broadly consistent with the approximate ones shown in the previous example, but are more appropriate to contrast with theoretical models.

<img width="5142" alt="examples3 4" src="https://github.com/user-attachments/assets/fadc271a-7491-468f-9417-e7bc3ed99f93" />


In the left panel ([example#3](aux/config_examples.ipynb)), we contextualize a desert planet. In the right panel ([example#4](aux/config_examples.ipynb)), we contextualize two ridge planets with legend labels. We also illustrate how to draw tidal boundaries for planets that underwent high-eccentricity tidal migration (HEM). **These boundaries closely reproduce the empirical desert boundary as well as the extension of the ridge** when adopting a single tidal-encounter parameter that sets the overall period offset, **suggesting a common HEM origin for the ridge and the desert** (see Castro-González et al. 2026).

## 3. The Neptunian density trends

In this **two-panel plot** ([example#5](aux/config_examples.ipynb)), we contextualize several planets along the **density trend** for super-Neptunes and sub-Saturns presented in [Castro-González et al. (2024b)](https://ui.adsabs.harvard.edu/abs/2024A%26A...691A.233C/abstract) (see Section 5.2). Planets in the savanna show low densities, typically below 1 g cm<sup>−3</sup>, whereas planets in the ridge and desert can reach densities up to ~2 g cm<sup>−3</sup>. The density transition aligns closely with the planet-occurrence break between the ridge and the savanna (at P<sub>orb</sub> ~ 6 days), suggesting that **desert and ridge planets may share common formation and/or evolutionary pathways distinct from those of Neptunes in the savanna** (see the papers for further discussion).

<img width="5540" alt="nep_dens_example5" src="https://github.com/user-attachments/assets/d9c7e081-6b18-4186-bf22-813d50391cdc" />

This plot can also incorporate the tidal boundary (i.e. survival limit) studied in Castro-González et al. (2026), which **closely follows the observed density distribution, simultaneously explaining both the scarcity of Neptunes in the desert and their accumulation along the ridge**. In this interpretation, the ridge emerges because there are not enough low-density Neptunes to be deposited significantly beyond it after HEM. In addition, we include the density histogram across the ridge and savanna regions (for convenience, the transition is set here at 8 days), **revealing an intriguing concentration of ridge Neptunes at densities of ~1.6–1.7 g cm<sup>−3</sup>**.

## Credits

If you use our population-based mapping of the exo-Neptunian landscape, please give credit to [this work](https://ui.adsabs.harvard.edu/abs/2024A%26A...689A.250C/abstract):

```bibtex
@ARTICLE{2024A&A...689A.250C,
       author = {{Castro-Gonz{\'a}lez}, A. and {Bourrier}, V. and {Lillo-Box}, J. and {Delisle}, J. -B. and {Armstrong}, D.~J. and {Barrado}, D. and {Correia}, A.~C.~M.},
        title = "{Mapping the exo-Neptunian landscape: A ridge between the desert and savanna}",
      journal = {\aap},
     keywords = {planets and satellites: atmospheres, planets and satellites: dynamical evolution and stability, planets and satellites: formation, planets and satellites: gaseous planets, planets and satellites: physical evolution, Astrophysics - Earth and Planetary Astrophysics},
         year = 2024,
        month = sep,
       volume = {689},
          eid = {A250},
        pages = {A250},
          doi = {10.1051/0004-6361/202450957},
archivePrefix = {arXiv},
       eprint = {2409.10517},
 primaryClass = {astro-ph.EP},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2024A&A...689A.250C},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

If you also use the super-Neptune / sub-Saturn density trend, please give credit to [this work](https://ui.adsabs.harvard.edu/abs/2024A%26A...691A.233C/abstract):

```bibtex
@ARTICLE{2024A&A...691A.233C,
       author = {{Castro-Gonz{\'a}lez}, A. and {Lillo-Box}, J. and {Armstrong}, D.~J. and {Acu{\~n}a}, L. and {Aguichine}, A. and {Bourrier}, V. and {Gandhi}, S. and {Sousa}, S.~G. and {Delgado-Mena}, E. and {Moya}, A. and {Adibekyan}, V. and {Correia}, A.~C.~M. and {Barrado}, D. and {Damasso}, M. and {Winn}, J.~N. and {Santos}, N.~C. and {Barkaoui}, K. and {Barros}, S.~C.~C. and {Benkhaldoun}, Z. and {Bouchy}, F. and {Brice{\~n}o}, C. and {Caldwell}, D.~A. and {Collins}, K.~A. and {Essack}, Z. and {Ghachoui}, M. and {Gillon}, M. and {Hounsell}, R. and {Jehin}, E. and {Jenkins}, J.~M. and {Keniger}, M.~A.~F. and {Law}, N. and {Mann}, A.~W. and {Nielsen}, L.~D. and {Pozuelos}, F.~J. and {Schanche}, N. and {Seager}, S. and {Tan}, T.-G. and {Timmermans}, M. and {Villase{\~n}or}, J. and {Watkins}, C.~N. and {Ziegler}, C.},
        title = "{TOI-5005 b: A super-Neptune in the savanna near the ridge}",
      journal = {\aap},
     keywords = {techniques: photometric, techniques: radial velocities, planets and satellites: composition, planets and satellites: detection, planets and satellites: individual: TOI-5005 b, stars: individual: TOI 5005 (TIC 282485660), Earth and Planetary Astrophysics},
         year = 2024,
        month = nov,
       volume = {691},
          eid = {A233},
        pages = {A233},
          doi = {10.1051/0004-6361/202451656},
archivePrefix = {arXiv},
       eprint = {2409.18129},
 primaryClass = {astro-ph.EP},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2024A&A...691A.233C},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

If you make use of `nep-des` in your research, please include the following sentence in the acknowledgements:

> This research made use of \texttt{nep-des} (available in \url{https://github.com/castro-gzlz/nep-des})

Please also give credit to the catalogue(s) used in each plot: NASA Exoplanet Archive ([Christiansen et al. 2025](https://ui.adsabs.harvard.edu/abs/2025PSJ.....6..186C/abstract)) for plots 1 and 3 when using `catalog = "NEA"`; Exoplanet.eu ([Schneider et al. 2011](https://ui.adsabs.harvard.edu/abs/2011A%26A...532A..79S/abstract)) for plots 1 and 3 when using `catalog = "Exoplanet.eu"`; and Kepler DR25 ([Thompson et al. 2018](https://ui.adsabs.harvard.edu/abs/2018ApJS..235...38T/abstract)) for plot 2.
