# Monte Carlo Simulation: the interaction between mid-energy gamma rays and water

- **Physical Interactions**:
  - **Photoelectric Effect**: This interaction is predominant at lower energies, especially below 100 keV. In the photoelectric effect, a gamma ray photon is completely absorbed, and its energy is transferred to an electron, which is then ejected from the atom. The probability of the photoelectric effect decreases rapidly with increasing photon energy.

  - **Compton Scattering**: In this scattering process, a gamma ray photon collides with an outer shell electron, loses part of its energy, and changes direction. The energy of the photon after scattering depends on the scattering angle. Compton scattering becomes significant when the energy of the gamma rays is sufficient to interact with the loosely bound or free electrons but not high enough for more energy-intensive processes like pair production. This interaction is typically most significant from about 100 keV to a few MeV.

  - **Pair Production**: This occurs when the energy of the gamma ray photon is above the threshold of 1.022 MeV (twice the rest mass energy of an electron). In this process, a gamma ray photon is converted into an electron and a positron in the field of a nucleus. The importance of pair production increases with increasing photon energy, becoming more significant above several MeV.

In energy range of 100 keV to 1 MeV, compton scattering is most dominant for gamma rays.


#### Energy and Angle Relationship

The energy of the scattered photon can be determined using the formula:

\[ E' = \frac{E}{1 + \frac{E}{m_e c^2} (1 - \cos(\theta))} \]

where:
- \( E \) is the original energy of the photon.
- \( E' \) is the energy of the photon after scattering.
- \( \theta \) is the scattering angle.
- \( m_e c^2 \) is the rest mass energy of the electron (approximately 0.511 MeV).

#### Klein-Nishina Formula

The Klein-Nishina formula provides the differential cross-section for Compton scattering as a function of the scattering angle \( \theta \) and the incident photon energy \( E \). It is crucial for understanding the probability distribution of the scattering angle:

\[ \frac{d\sigma}{d\Omega} = \frac{r_e^2}{2} \left( \frac{E'}{E} \right)^2 \left( \frac{E'}{E} + \frac{E}{E'} - \sin^2(\theta) \right) \]

where \( r_e \) is the classical electron radius. This formula shows that the probability of scattering at an angle \( \theta \) depends non-linearly on \( \theta \) and the photon's energy.



### Formula Revisited
The mean free path (λ) for gamma rays in water can be calculated using:
\[ \lambda = \frac{1}{n \sigma} \]
where:
- \( n \) is the number density of water molecules.
- \( \sigma \) is the total interaction cross-section in cm² per molecule (not cm²/g).
