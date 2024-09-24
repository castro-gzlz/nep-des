# **nep-des**
This [Jupyter Notebook](https://jupyter.org/) creates **period-radius diagrams** with the **population-based boundaries** of the Neptunian **desert**, **ridge**, and **savanna** derived in [Castro-González et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024A%26A...689A.250C/abstract). 

![Spice Dune Exo-Neptunian 3-01](https://github.com/user-attachments/assets/0ab75a3f-bbb7-429c-a9fe-8d5b3f2b4ed1)
<sup> © Elsa Bersier / ERC project SPICE DUNE </sup>

## Installation and usage

**You do not need to install anything**. You can simply **clone** or **download** the repository and run all cells of the [nep_des.ipynb](https://github.com/castro-gzlz/nep-des/blob/main/nep_des.ipynb) file. The code is very **straightforward** and **intuitive** to use, so it does not have detailed documentation. If you find any problem or would like to propose an update do not hesitate to [drop me an issue](https://github.com/castro-gzlz/nep-des/issues), make a [pull request](https://github.com/castro-gzlz/nep-des/pulls), or contact me at [acastro@cab.inta-csic.es](acastro@cab.inta-csic.es).

## Output example

In the left panel, we contextualize some of the most well-known and rare planets in the middle of the Neptunian desert: TOI-849 b ([Armstrong et al. 2020](https://ui.adsabs.harvard.edu/abs/2020Natur.583...39A/abstract)), TOI-1853 b ([Naponiello et al. 2023](https://ui.adsabs.harvard.edu/abs/2023Natur.622..255N/abstract)), LTT 9779 b ([Jenkins et al. 2020](https://ui.adsabs.harvard.edu/abs/2020NatAs...4.1148J/abstract)), TOI-3071 b ([Hacker et al. 2024](https://ui.adsabs.harvard.edu/abs/2024MNRAS.532.1612H/abstract)), TOI-674 b ([Murgas et al. 2021](https://ui.adsabs.harvard.edu/abs/2021A%26A...653A..60M/abstract)), and K2-45 b ([Crossfield et al. 2016](https://ui.adsabs.harvard.edu/abs/2016ApJS..226....7C/abstract)). 

In the right panel, we contextualize a planet in the Neptunian savanna, HATS-17 b ([Brahm et al. 2016](https://ui.adsabs.harvard.edu/abs/2016AJ....151...89B/abstract)), and highlight it with a text box. More planets can be depicted similarly. 

In the left-hand plot, we used the NASA Exoplanet Archive catalogue, and in the right-hand plot, we used the Exoplanet.eu catalogue. The planetS catalogue for planets with precise mass and radii can be also used. 

![image](https://github.com/user-attachments/assets/c51efa26-17a3-41ad-946e-f4a50f0e842d)


## Precaution

The contour map represents the **observed** density of planets in the selected catalogue, which is subjected to different **observational** and **selection** **biases**, and hence it does not represent the *true planet occurrence* from which the boundaries were derived. Still, there is a quite good (visual) agreement between the observed distribution and the population-based boundaries, so it is reasonable to plot them together. 

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

Please also give credit to the catalogue(s) used: Nasa Exoplanet Archive ([Akeson et al. 2013](https://ui.adsabs.harvard.edu/abs/2013PASP..125..989A/abstract)), Exoplanet.eu ([Schneider et al. 2011](https://ui.adsabs.harvard.edu/abs/2011A%26A...532A..79S/abstract)), and PlanetS ([Otegi et al. 2020](https://ui.adsabs.harvard.edu/abs/2020A%26A...634A..43O/abstract); [Parc et al. 2024](https://ui.adsabs.harvard.edu/abs/2024A%26A...688A..59P/abstract)).










