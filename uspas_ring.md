# Components of the Compact Ring:

**Ring:**
* radius to be defined depending on the energy and the magnet technology.
* Aperture selection, it probably makes most sense to have asymmetric aperture, wide in horizontal, narrow in vertical
  * ~ 1 cm in vertical, horizontal primarily driven by dispersion once dp/p is determined.
* Drift sections that do not have the wiggler or injection do not have to be the same length.

**Focusing Doublet:**
Necessary gradients of the quads depend on beam energy and the divergence. The maximum beam size will influence the aperture and hence the achievable gradient.  The solution we came up with collectively as a homework task is good for the $L + d = 1$ situation, but should be relaxed a bit as we categorize our process/assumptions.  
* Aakash raises the point that the energy variation in design may feed back strongly into this concern.  
* Doesn't necessarily need to be symmetric focus structure.  
* Laser can be inserted between the poles of the magnet.  Certainly if it's NC, probably possible if SC

**Weak focusing considerations**
need to be handled formally (tapered dipole edge)
Dispersion function calculation in dipoles (can ignore edge taper)

**Synchrotron loss per turn:**

is dependent on the beam energy and the radius of curvature in the bending magnets. The wiggler will cause additional energy loss. The characteristic energy emitted also depends on the beam energy and the bending radius.

**Laser/plasma concerns, injection, etc.**

The laser has to be bigger than a0 > 2 in order to have self-injection. The laser wavelength should be chosen in such a way that the dephasing length is lower than we need for acceleration. It also must be ensured that the laser can propagate in the plasma.  The laser depletion has to be longer than the plasma longitudinal size.

The plasma density needs to be chosen so that we can achieve 1 or 3 GeV/c2 within the dephasing length.

## Questions about setup:

* Why use a gas jet rather than a capillary? Doesn’t this produce a larger energy spread?
Andrei/Aakash: time

## Wiggler/undulator
* Energy of emitted radiation ~ 10 keV
* Calculation of value of K
* Can an undulator be used?

### Andrei's remarks during lecture: 
better spectral bandwidth with an undulator, so it would be helpful to have this, if our choice of magnet technology makes this feasible.
If the other parameters work out, let's use undulator instead of wiggler, so that we can take advantage of resonance condition.

## Injector
* What are the clearances like?
* time for the gas to clear?
* laser/plasma parameters?
* Leemans had 9 cm of plasma, we would need ~ 7 cm for 3 GeV with the same density, can a gas jet do this?
  * A real-world set of gas jet parameters should be chosen from a reference gun

## Parameter tables
|                                          | 1.5 T, 1 GeV               | 10T, 1 GeV                | 10 T, 3 GeV          |
|------------------------------------------|----------------------------|---------------------------|----------------------|
| $\rho$                                   | 2.23 m                     | 0.34 m                    | 1.02 m               |
| $L_{quad}$                               | 3.5 m                      | 5.25 m                    | 1.6 m                |
| $G_{quad}$                               | 48 T/m, 95 T/m             | 48 T/m, 95 T/m            | 144 T/m, 285 T/m     |
| Synchrotron losses per turn, $\Delta U$  | 36 keV                     | 260 keV                   | 7.02 MeV             |
| Characteristic energy $\hbar \omega_c$   | 0.99 keV                   | 6.57 keV                  | 59.1 keV             |

## Realistic laser parameters (inspired by Leemans 4 GeV paper)
### Plasma parameters to be decided from these
|                                          |                            |
|------------------------------------------|----------------------------|
| Laser wavelength                         | 0.78 um (Ti-sapphire)      |
| Laser power                              | 300 TW                     |
| Laser pulse length (FWHM)                | 50 fs                      |
| a_0                                      | >= 2 (self-injection)      |
