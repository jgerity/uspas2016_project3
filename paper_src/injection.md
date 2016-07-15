A laser wakefield acceleration/injection stage provides the electron beam for the compact ring. Here, we present a rough set of parameters and conditions for the setup based on existing experiments and analytic approximations.

In this setup an intense laser pulse from a Ti:Sapphire laser impinges upon a gas jet, subsequently ionizing the gas and injecteing electrons from the background plasma. This class of setup was chosen in part because of our ring strucutre: the injection setup is located inside the ring to reduce the physical footprint, and as such, we need to ensure that any associated structures for the setup will not interfere with the re-circulating beam. A capillary structure or similar small gas cell thus complicates the task, as it must be moved out of the way very quickly. Hence, a gas jet design was chosen, as by the time the beam recirculates it will mostly be interacting with neutral gas. The choice of gas is not specified here.

The parameters for the setup are as follows. Here, we assumed a sufficiently high laser power and intensity such that self-guiding, self-focusing, and self-injection were possible. With a given laser power of 379 TW, a laser wavelength of 780 nm, and a pulse duration of 50 fs, and a spot size of 3.8 nm, we obtain a laser intensity of approximately 9.9*10^18 W/cm^2, a0 of about 2.1 for a Gaussian radial laser distribution, and an energy per pulse of 20 J. The laser spot size and duration were chosen to be typical for this class of laser along with the plasma parameters to ensure that these were matched. The plasma density was chosen to be below the approximate critical density. After calculating the plasma wavelength we ensured that the laser pulse duration was less than the pi/plasma angular frequency.  The depletion and dephasing lengths were calculated to be approximately 17 cm and 35 cm respectively, thus bounding our total possible acceleration length to 17 cm. Using our target energies of 1 GeV and 3 GeV, we then calculate how long our acceleration stage needs to be based on a conservative estimate of the magnitude of the gradient in the plasma (0.42 GeV/cm). This results in acceleration stages of 2.4 cm and 7.2 cm respectively. More optimistic empirically-based estimates of the gradient yield 0.88 GeV/cm, thus reducing the necessary acceleration length to get to 1 and 3 GeV. Under the conservative estimate, the long acceleration length may require a novel gas jet setup or gas chamber of some kind that would be out of the way of the beam and could be cleared quickly. Further assessment will require simulations of the setup.

Finally, we imagine topping off the beam 

###output beam characteristics??? Need help with this.

##NEW TABLE CONSISTENT WITH USPAS_20160701_Plasma_Calculations_Updated.ipynb:
### Laser Parameters
|                                          |                            |
|------------------------------------------|----------------------------|
| Laser wavelength                         | 780 nm (Ti-sapphire)       |
| Laser power                              | 379 TW                     |
| Spot size                                | 3.8e-9 m^2                 |
| Intensity                                | 9.9e18 W/cm^2              |
| a_0                                      | 2.1                        |
| Laser pulse length (FWHM)                | 50 fs                      |
| Rep rate                                 | ~ 1 Hz                     |
| Energy per pulse                         |  20 J                      |

### Plasma parameters
|                                          |                            |
|------------------------------------------|----------------------------|
| Critical density                         | ~1.5e21 cm^-3              |
| Plasma density                           | 1.75e17 cm^-3              |
| Plasma wavelength                        | 76 um                      |
| Plasma frequency                         | 3.97e12 Hz                 |
| Plasma angular frequency                 | 2.49e13 s^-1               |
| Accelerating gradient                    | 0.42 GeV/cm                |
| Bubble size                              | 38 um                      |
| Depletion length                         | 16.9 cm                    |
| Dephasing length                         | 33.5 cm                    |
| Acceleration length for 1 GeV            | 2.4 cm                     |
| Acceleration length for 3 GeV            | 7.2 cm                     |




## OLD TABLE FROM CLASS:

### Realistic laser parameters (inspired by [Leemans 4 GeV paper](http://link.aps.org/doi/10.1103/PhysRevLett.113.245002))
|                                          |                            |
|------------------------------------------|----------------------------|
| Laser wavelength                         | 780 nm (Ti-sapphire)       |
| Laser power                              | 379 TW                     |
| Spot size                                | 3.8e-9 m^2                 |
| Intensity                                | 9.93e18 W/cm^2             |
| a_0                                      | 2.1                        |
| Laser pulse length (FWHM)                | 50 fs                      |
| Rep rate                                 | ~ 1 Hz                     |


### Plasma parameters
|                                          |                            |
|------------------------------------------|----------------------------|
| Plasma density                           | 1.75e17 cm^-3              |
| Plasma wavelength                        | 76 um                      |
| Plasma frequency                         | 2.49e13 s^-1               |
| Maximum accelerating field $E_{max}$     | 0.88 GV/cm                 |
| Bubble size                              | 38 um                      |
| Depletion length                         | 16.9 cm                    |
| Dephasing length                         | 3.5 cm                     |
