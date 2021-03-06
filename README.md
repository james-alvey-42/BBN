# DarkBBN

> The synthesis of light elements in the early universe is a complex process, and provides much insight into the thermodynamic state of each particle species that is present. The agreement between precise measurements of the light element abundances such as Hydrogen, Helium and Lithium provides strong evidence for a Hot Big Bang. Nonetheless, it is known that new physics is required both in the Standard models of particle physics and cosmology. The precision of these light element abundances can place tight constraints on the type of new physics that can be at play.

This repository is relevant to two articles written in October 2019 with colleagues at King's College London. Links to the webpages and PDF documents can be found below. Also included is a link to a presentation given by myself at the recent DMUK meeting at the University of Manchester.

### Refined Bounds on MeV-scale Thermal Dark Sectors from BBN and the CMB, *N. Sabti, J. Alvey, M. Escudero, M. Fairbairn, D. Blas*

*Summary:* We place a **lower bound** on the thermal dark matter mass of 3.7 MeV, independent of spin or coupling to neutrinos or photons. We expect this to improve by an order of magnitude with future CMB experiments such as the Simons Observatory and CMB-S4.

* <a href="https://arxiv.org/pdf/1910.01649.pdf" target="blank_">PDF</a> 

* <a href="http://inspirehep.net/record/1757525" target="blank_">Inspire-HEP Record</a>

* <a href="https://james-alvey-42.github.io/assets/pdf/DMUK.pdf" target="blank_">DMUK Presentation</a>

### Improved BBN Constraints on the Variation of the Gravitational Constant, *J. Alvey, N. Sabti, M. Escudero, M. Fairbairn*

*Summary:* We find that G does not vary by more than 3% from its current value at 95.8% confidence level. In other words, we find that BBN is a very sensitive probe of gravitational physics in the early Univesre, and is concurrent with the statement that G did not vary from its value today.

* <a href="https://arxiv.org/pdf/1910.10730.pdf" target="blank_">PDF</a> 

* <a href="http://inspirehep.net/record/1760725" target="blank_">Inspire-HEP Record</a>

## What happens in the Standard Model?

Within the Standard Model, Big Bang Nucleosynthesis has only one free parameter, the baryon-to-photon ratio or equivalently the baryon density. The dependence of the key primordial abundances is shown below;

![bbnsm](img/bbn.png)

Here, the blue band represents the best measurement of the baryon density from the Planck satellite. Besides the lithium abundance, which is a far from solved theoretical problem, there is very strong agreement between nuclear physics predictions within the Standard Models of Particle Physics and Cosmology and measurements. This ensures that new physics, be it in the form of new particles, or varying constants, cannot alter this picture too much.

In the works linked above we consider two ways in which new physics might be manifest:

1. A new particle species that is thermally coupled to the Standard Model plasma at the time of nucleosynthesis.
2. The prospect that Newton's gravitational constant might vary with cosmic time.

In both cases we find that we can derive some strict bounds on either the mass of the new particle, or the variation of G.

## Freeze-Out

A key concept in Big Bang Nucleosynthesis is that of *freeze-out*, which can be explained as follows:

> The early universe was (and still is) expanding at a rate denoted by the Hubble parameter. Consider a given particle physics process with interactions at some other rate, for example protons being converted into neutrons. This process is said to "freeze-out", or become inefficient, when the expansion rate is larger than the interaction rate.

## Key Events

To understand how BBN physics can be altered, we first should understand three major events in the cosmic history.

![cosmichistory](img/cosmichistory.png)

1. **Neutrino Decoupling** - This happens around 1 second after the Big Bang when the relevant weak rates become small compared to the expansion rate. After this the temperatures of neutrinos and photons evolve differently.
2. **Neutron Freeze-out** - At around 0.7 MeV, the weak reactions decouple from the expansion, fixing the initial neutron to proton ratio.
3. **Start of BBN** - Approximately 300 seconds after the Big Bang, the formation of the light elements begins via the nuclear reaction network.

## What if we add new light particles?

The addition of new light thermal particles in the early Universe has a number of effects which can be used to explain the variation in the primordial abundances from their Standard Model values.

![neweffects](img/neweffects.png)

* **Freeze-Out** - Relevant nuclear and weak interaction processes freeze out at different times.
* **Expansion Rate** - The comsic time between neutron freeze-out and nucleosynthesis changes.
* **Sector Temperatures** - The temperatures of the neutrino/photon sectors can be altered by new particles.
* **Baryon Dilution** - Decreases in the baryon-to-photon ratio can occur after nucleosynthesis, diluting the primordial abundances.

We can see the effect of a new particle with some mass coupled to either neutrinos ("Neutrinophilic") or electrons/photons ("Electrophilic") in the following plots;

![abundances](img/abundances.png)

Here, the top panel denotes the number of relativistic degrees of freedom. This plays an important role in controlling the expansion rate, and will be very precisely measured in future CMB experiments. The middle panel is the primordial helium abundance, and the lower panel contains the corresponding deuterium predictions.

## How do we constrain new physics?

Once we have understood qualitatively the effect of adding a new particle via the effects above, we need to be more quantitative. In order to constrain new physics we need to account for the following factors;

* **Modelling** - Measurements of the primordial abundances of helium and deuterium are now increasingly good. We need to match this accuracy in our predictions of the primordial abundances. To do so, we modified a code called [PRIMAT](https://arxiv.org/abs/1801.08023), written in Mathematica.
* **Incomplete Neutrino Decoupling** - Part of this modelling needs to account for the fact that our description above was a little simplistic. Neutrinos do not instantaneously decouple from the electron/photon plasma. Instead they receive some of the energy transferred during electron-positron annihilation, heating them slightly.
* **Baryon Density** - The Planck satellite measures the baryon density from the Cosmic Microwave Background. We would like to derive a cosmologically independent lower bound on the dark matter mass however. To do so, we then have to marginalise over this baryon-to-photon ratio, the only free parameter in Standard Model BBN.
* **Latest Cosmological Data** - We should of course use the most up-to-date CMB data and astrophysical measurements of the primordial helium and deuterium abundances. These can be put into a test statistic to decide whether to rule out given new physics at a certain significance level.

An example of the exclusion plots that result in the case of Majorana dark sector particles is shown below,

![exclusion](img/exclusion.png)

The ultimate result of the study is that we can rule out masses below 0.4 MeV/3.7 MeV (BBN only/BBN+Planck). This starts to close the lower end of the mass window avaiilable for WIMP dark matter.

## Future Measurements

What can we expect to do in the future? Future CMB experiments and determinations of the helium and deuterium abundances can improve these bounds. We investigated these effects using a Fisher analysis for the Simons observatory and CMB-S4 and a parameter scan for the astrophysical measurements. The results are shown below,

![futurecmb](img/futurecmb.png)

![futurehd](img/futurehd.png)

There are a couple of conclusions we can draw from this,

1. CMB-S4 and the Simons Observatory will be able to significantly strengthen the bounds.
2. They will also provide a far more precise determination of the baryon density.
3. Better measurements of the deuterium abundance **will not** substantially improve the mass bounds, only the determination of the baryon density.
4. On the other hand, improved measurements of the helium abundance can have a large effect.

## Conclusions: How consistent are new particles during BBN?

We have presented a subset of the findings when it comes to new thermal particles during the BBN epoch, as well as some of the analysis methods. There are some key conclusions to draw;

![conclusions](img/bbnconclusions.png)

* Nucleosynthesis measurements strongly constrain additional light thermal species. Indeed, we rule out light thermal WIMPs for masses below 0.4 MeV (BBN only) and 3.7 MeV (BBN + Planck).
* These bounds apply to **any** particle that has been in thermal equilibrium with the plasma (including mediators that are not the dark matter).
* Future experiments such as CMB-S4 will be able to greatly improve these bounds.

## Gravitational Physics during BBN

The second example where we use BBN to constrain new physics is in the gravitational sector. This is a lot cleaner than the above discussion in the sense that a change in the gravitational constant G really only varies the expansion history. This is a consequence of the Friedmann equation where the Hubble rate is proportional to the square root of the gravitational constant.

As mentioned above, a key concept in nucleosynthesis is freeze-out. In this case, a change in the expansion rate affects the time at which various processes decouple. This leads to modifications to the initial neutron-to-proton ratio, as well as the time that neutrons have to decay after neutron freeze-out. Generically we can expect that an increase in the expansion rate (equivalently an increase in the value of G) compared to the standard case will lead to an increase in both the helium and deuterium abundances. Running the simulations, this is indeed what we find,

![Gabundances](img/Gabundances.png)

It is then a simple matter to use the measurements and their uncertainties illustrated by the grey bands to rule out variations in the gravitational constant. Following a very similar methodology to that given above, we find the following exclusion limits,

![Glimits](img/Glimits.png)

Reading the relevant parameters off, we concluded that primordial nucleosynthesis is consistent with a value of the gravitational constant that is the same as that measured (very accurately) today.

Links
---

You can find links to the relevant papers/presentations below,

* <a href="https://arxiv.org/pdf/1910.01649.pdf" target="blank_">Light Thermal Particles</a> (<a href="http://inspirehep.net/record/1757525" target="blank_">Inspire-HEP Record</a>)

* <a href="https://arxiv.org/pdf/1910.10730.pdf" target="blank_">Variations in the Gravitational Constant</a> (<a href="http://inspirehep.net/record/1760725" target="blank_">Inspire-HEP Record</a>)

* <a href="https://james-alvey-42.github.io/assets/pdf/DMUK.pdf" target="blank_">DMUK Presentation</a>