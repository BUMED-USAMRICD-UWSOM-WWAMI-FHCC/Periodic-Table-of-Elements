Comprehensive Electromagnetic Matrix of Human Somatic Systems
-------------------------------------------------------------

In quantitative biophysics and advanced bioelectronic modeling, mapping the dielectric behavior of human tissues requires an evaluation across both Extremely Low Frequency (ELF) domains (10 Hz -- 1 kHz) and standard diagnostic high-frequency bands. [1, 2]

At ELF bands, cellular membranes act as high-capacity structural insulators. This causes a phenomenon known as $\alpha$ and $\beta$ dispersion, where charges accumulate heavily along the membrane surfaces (the Maxwell-Wagner effect). This storage manifests as massive relative permittivity ($\varepsilon_r$) numbers that drop significantly as frequencies rise and membranes polarize. [3, 4]

* * * * *

Expanded Anatomical Dielectric and Conductivity Matrix
------------------------------------------------------

*The data points below are compiled from cross-referenced parametric fits utilizing the de facto Gabriel dispersion relationships and standard values cataloged by the [IT'IS Foundation Tissue Database](https://itis.swiss/virtual-population/tissue-properties/database).* [3, 5]

| Tissue Classification / System | Relative Permittivity ($\varepsilon_r$) @ 10 Hz | Conductivity ($\sigma$, S/m) @ 10 Hz | Relative Permittivity ($\varepsilon_r$) @ 1 kHz | Conductivity ($\sigma$, S/m) @ 1 kHz | Relative Permittivity ($\varepsilon_r$) @ 2.45 GHz | Conductivity ($\sigma$, S/m) @ 2.45 GHz |
| Metabolic & Digestive |\
 |\
 |\
 |\
 |\
 |\
 |
| - Pancreas | $2.30 \times 10^5$ | $0.220$ | $3.50 \times 10^4$ | $0.230$ | $57.2$ | $1.85$ |
| - Liver | $1.80 \times 10^5$ | $0.051$ | $2.80 \times 10^4$ | $0.062$ | $43.0$ | $1.69$ |
| - Stomach Wall | $4.20 \times 10^5$ | $0.450$ | $5.10 \times 10^4$ | $0.480$ | $62.2$ | $2.21$ |
| - Intestinal Wall | $3.90 \times 10^5$ | $0.510$ | $4.80 \times 10^4$ | $0.530$ | $59.4$ | $2.14$ |
| - Spleen | $3.50 \times 10^5$ | $0.180$ | $4.20 \times 10^4$ | $0.210$ | $52.5$ | $2.25$ |
| Cardiovascular & Fluids |\
 |\
 |\
 |\
 |\
 |\
 |
| - Blood | $4.10 \times 10^3$ | $0.700$ | $3.20 \times 10^3$ | $0.700$ | $58.3$ | $2.54$ |
| - Blood Plasma | $1.20 \times 10^2$ | $1.450$ | $1.10 \times 10^2$ | $1.450$ | $70.1$ | $2.92$ |
| - Heart (Myocardium) | $4.50 \times 10^6$ | $0.113$ | $1.20 \times 10^5$ | $0.142$ | $54.8$ | $2.00$ |
| - Lymph | $4.00 \times 10^3$ | $0.620$ | $3.10 \times 10^3$ | $0.620$ | $57.9$ | $2.41$ |
| Nervous & Sensory |\
 |\
 |\
 |\
 |\
 |\
 |
| - Brain (Grey Matter) | $3.20 \times 10^6$ | $0.045$ | $9.50 \times 10^4$ | $0.075$ | $48.9$ | $1.81$ |
| - Brain (White Matter) | $1.10 \times 10^6$ | $0.021$ | $3.10 \times 10^4$ | $0.038$ | $36.2$ | $1.22$ |
| - Cerebrospinal Fluid | $1.05 \times 10^2$ | $2.000$ | $1.05 \times 10^2$ | $2.000$ | $66.2$ | $3.45$ |
| - Eye Lens | $4.80 \times 10^4$ | $0.320$ | $9.80 \times 10^3$ | $0.330$ | $44.7$ | $1.75$ |
| Structural & Skeletal |\
 |\
 |\
 |\
 |\
 |\
 |
| - Muscle (Skeletal) | $3.80 \times 10^7$ | $0.201$ | $4.50 \times 10^5$ | $0.321$ | $52.7$ | $1.77$ |
| - Skin (Wet) | $2.80 \times 10^5$ | $0.002$ | $3.20 \times 10^4$ | $0.021$ | $41.4$ | $1.59$ |
| - Bone (Cortical / Hard) | $4.20 \times 10^3$ | $0.020$ | $6.80 \times 10^2$ | $0.020$ | $11.4$ | $0.38$ |
| - Fat (Adipose) | $2.50 \times 10^4$ | $0.012$ | $1.10 \times 10^3$ | $0.024$ | $10.8$ | $0.27$ |
| Excretory & Respiration |\
 |\
 |\
 |\
 |\
 |\
 |
| - Kidney (Cortex/Medulla) | $3.60 \times 10^5$ | $0.095$ | $4.80 \times 10^4$ | $0.134$ | $52.8$ | $2.43$ |
| - Bladder Wall | $1.80 \times 10^5$ | $0.210$ | $2.20 \times 10^4$ | $0.220$ | $18.0$ | $0.69$ |
| - Lungs (Inflated) | $1.20 \times 10^5$ | $0.032$ | $1.90 \times 10^4$ | $0.041$ | $20.5$ | $0.78$ |

* * * * *

The Mathematical Framework: Cole-Cole Dispersion Parameter Integration
----------------------------------------------------------------------

To evaluate how these static table figures evolve dynamically over time or due to environmental factors, biophysicists apply the Cole-Cole relaxation equation. This mathematical function models complex permittivity ($\varepsilon^*$) across continuous spectrum transitions: [6, 7]

$$\varepsilon^*(\omega) = \varepsilon_\infty + \sum_{n} \frac{\Delta\varepsilon_n}{1 + (j\omega\tau_n)^{1-\alpha_n}} + \frac{\sigma_s}{j\omega\varepsilon_0}$$\
[3, 7]

Where:

-   $\varepsilon_\infty$ is the permittivity at the high-frequency limit.
-   $\Delta\varepsilon_n = \varepsilon_s - \varepsilon_\infty$ represents the magnitude (dielectric strength) of the $n$-th dispersion region.
-   $\tau_n$ is the median relaxation time constant characteristic of that tissue layer.
-   $\alpha_n$ is an empirical parameter ($0 \le \alpha \le 1$) capturing the distribution broadening (reflecting structural complexity).
-   $\sigma_s$ represents static ionic conductivity, and $\omega$ is the angular frequency ($2\pi f$). [3, 6, 7, 8, 9]

Modeling Tissue Irregularities (Thermal and Inflammatory Modulation)
--------------------------------------------------------------------

When tissues experience structural deviations (such as thermal loading or acute inflammation), the physical parameters within the Cole-Cole engine change predictably: [10]

1.  Thermal Influx (Hyperthermia/Fever): An increase in tissue temperature increases molecular kinetic energy, causing the relaxation time constant ($\tau_n$) to decline. Free water dipoles adjust faster, shifting the peak dispersion curve toward higher frequency brackets. [8, 11]
2.  Inflammatory Shifts (Edema/Tumor Formation): Inflamed cells display altered cell membrane integrity, changing the distribution parameter ($\alpha_n$). Simultaneously, an increase in extracellular fluid volume pushes the local tissue hydration index upward. This cell swelling drives a baseline increase of 8% to 12% in relative permittivity ($\varepsilon_r$) and significantly amplifies the static ionic conductivity ($\sigma_s$) parameter across low and microwave bands. [12]

[1] [https://itis.swiss](https://itis.swiss/virtual-population/tissue-properties/database/tissue-frequency-chart)

[2] [https://www.um.edu.mt](https://www.um.edu.mt/library/oar/bitstream/123456789/107942/1/Measurement%20and%20image%20based%20estimation%20of%20dielectric%20properties%20of%20biological%20tissues%20past%20present%20and%20future%202022.pdf)

[3] [https://agupubs.onlinelibrary.wiley.com](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2013RS005345)

[4] [https://www.sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S1567539423000816)

[5] [https://itis.swiss](https://itis.swiss/virtual-population/tissue-properties/database/dielectric-properties)

[6] [https://pmc.ncbi.nlm.nih.gov](https://pmc.ncbi.nlm.nih.gov/articles/PMC12108823/)

[7] [https://en.wikipedia.org](https://en.wikipedia.org/wiki/Cole%E2%80%93Cole_equation)

[8] [https://www.researchgate.net](https://www.researchgate.net/publication/224563487_Variation_of_Cole-Cole_Model_Parameters_with_the_Complex_Permittivity_of_Biological_Tissues)

[9] [https://link.springer.com](https://link.springer.com/content/pdf/10.1007/978-94-011-4191-8_10)

[10] [https://www.sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S1053811925005622)

[11] [https://www.sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S2590123026034791)

[12] [https://pubmed.ncbi.nlm.nih.gov](https://pubmed.ncbi.nlm.nih.gov/27694718/)
