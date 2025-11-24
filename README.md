# **nep-des**
This code generates **period–radius diagrams** together with the **population-based boundaries** of the **Neptunian** **desert**, **ridge**, and **savanna**, as derived in [Castro-González et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...689A.250C/abstract). It also generates two-columns plots with the **density trend** for super-Neptune and sub-Jovian planets identified in [Castro-González et al. (2024b)](https://ui.adsabs.harvard.edu/abs/2024A%26A...691A.233C/abstract).

![Spice Dune Exo-Neptunian 3-01](https://github.com/user-attachments/assets/0ab75a3f-bbb7-429c-a9fe-8d5b3f2b4ed1)
<sup> © Elsa Bersier / ERC project SPICE DUNE </sup>

## Usage

No installation is required. Simply **clone** or **download** this repository and run [`nep_des.ipynb`](https://github.com/castro-gzlz/nep-des/blob/main/nep_des.ipynb). The code is designed to be **straightforward** and **intuitive** to use – just choose your preferred configuration. If you encounter any issues or would like to suggest improvements, please [open an issue](https://github.com/castro-gzlz/nep-des/issues), submit a [pull request](https://github.com/castro-gzlz/nep-des/pulls), or contact me.

## Output example 1. Approximate desert boundaries

In the left panel, we contextualize some of the best-known planets located in the middle of the Neptunian desert: TOI-849 b ([Armstrong et al. 2020](https://ui.adsabs.harvard.edu/abs/2020Natur.583...39A/abstract)), TOI-1853 b ([Naponiello et al. 2023](https://ui.adsabs.harvard.edu/abs/2023Natur.622..255N/abstract)), LTT 9779 b ([Jenkins et al. 2020](https://ui.adsabs.harvard.edu/abs/2020NatAs...4.1148J/abstract)), TOI-3071 b ([Hacker et al. 2024](https://ui.adsabs.harvard.edu/abs/2024MNRAS.532.1612H/abstract)), TOI-674 b ([Murgas et al. 2021](https://ui.adsabs.harvard.edu/abs/2021A%26A...653A..60M/abstract)), and K2-45 b ([Crossfield et al. 2016](https://ui.adsabs.harvard.edu/abs/2016ApJS..226....7C/abstract)). 

In the right panel, we contextualize the planet HATS-17 b ([Brahm et al. 2016](https://ui.adsabs.harvard.edu/abs/2016AJ....151...89B/abstract)) within the exo-Neptunian landscape and highlight it with a text box. Additional planets can be depicted in the same way.

In the left-hand plot, we used the *NASA Exoplanet Archive* catalogue, and in the right-hand plot, we used the *Exoplanet.eu* catalogue. The *planetS* catalogue for planets with precise masses and radii can also be used. 

<img width="5712" height="2437" alt="image" src="https://github.com/user-attachments/assets/7c4f4399-5f33-4061-9d92-142b9bf0f652" />


## Caution

The contour map represents the **observed** density of planets in the selected catalogue, which is subjected to different **observational** and **selection** **biases**, and hence it **does not represent** the *true planet occurrence* from which the boundaries were derived. We note, however, that there is a quite good (visual) agreement between the observed distribution and the population-based boundaries so it is reasonable to plot them together for visualization purposes. 

## Credits

If you use our population-based mapping of the exo-Neptunian landscape, please give credit to [this work](https://ui.adsabs.harvard.edu/abs/2024A%26A...689A.250C/abstract):

```
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

If you make use of *nep-des* to implement the exo-Neptunian boundaries in your research, please also include the following sentence within the acknowledgements section:

> This research made use of \texttt{nep-des} (available in \url{https://github.com/castro-gzlz/nep-des})

Please also give credit to the catalogue(s) used: Nasa Exoplanet Archive ([Akeson et al. 2013](https://ui.adsabs.harvard.edu/abs/2013PASP..125..989A/abstract); [Christiansen et al. 2025](https://ui.adsabs.harvard.edu/abs/2025PSJ.....6..186C/abstract)), Exoplanet.eu ([Schneider et al. 2011](https://ui.adsabs.harvard.edu/abs/2011A%26A...532A..79S/abstract)), and/or PlanetS ([Otegi et al. 2020](https://ui.adsabs.harvard.edu/abs/2020A%26A...634A..43O/abstract); [Parc et al. 2024](https://ui.adsabs.harvard.edu/abs/2024A%26A...688A..59P/abstract)).


