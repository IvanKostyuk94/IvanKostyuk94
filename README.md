# Hi, I'm Ivan 👋

I'm a computational astrophysicist at the [Scuola Normale Superiore](https://www.sns.it/en), Pisa, working on the physics of cosmic reionization — the epoch when the first stars and galaxies flooded the universe with ionizing radiation and re-ionized the intergalactic hydrogen.

## Research

My work centres on understanding what fraction of ionizing (Lyman-continuum) photons produced by young stars actually escape their host galaxies — the **escape fraction** (*f*<sub>esc</sub>). I study this using cosmological hydrodynamical simulations ([IllustrisTNG](https://www.tng-project.org/)) and build models that connect *f*<sub>esc</sub> to observable galaxy properties like stellar mass, gas mass, metallicity, and redshift.

I'm also interested in applying **machine learning** to cosmological simulations — in particular, using neural networks to super-resolve large simulation boxes, recovering small-scale structure without the cost of running a full high-resolution simulation.

## Repositories

| Repo | What it does |
|---|---|
| [semianalytic_fesc](https://github.com/IvanKostyuk94/semianalytic_fesc) | Semi-analytic pipeline for computing *f*<sub>esc</sub> cell-by-cell on IllustrisTNG galaxies, plus a polynomial fitting model |
| [outflows](https://github.com/IvanKostyuk94/outflows) | GMM-based identification and characterisation of galactic outflows in TNG50 and SERRA — mass, kinematics, metallicity, and orientation effects |
| [SuperResolution](https://github.com/IvanKostyuk94/SuperResolution) | `cosmoSR` — a Python/TensorFlow toolkit for training neural networks to super-resolve gridded cosmological simulations |
| [f_esc](https://github.com/IvanKostyuk94/f_esc) | LyC escape fractions of TNG50 galaxies post-processed with the CRASH radiative-transfer code — figure notebooks for Kostyuk+2023 |

## Get in touch

Open an issue on any of the repos, or find my papers on [arXiv](https://arxiv.org/search/?searchtype=author&query=Kostyuk%2C+Ivan).
