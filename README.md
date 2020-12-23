# Radioactive-Decay
This programme describes the radioactive decay of a large number of atoms using the Monte Carlo technique, and then does the same for the daughter atoms. Following this the programme then describes the absorption of atoms by reactor shielding.

The radioactive decay formula:

$${N(t)} = {N_0}{e}^{-\lambda t}$$

Probability of decay is given by:

$${\lambda} = {ln}{(\frac{1}{1-p})}$$

The number of grandaughter atoms is calculated from the formula:

$$ {G(t)} = {N_0} - {N(t)} - {D(t)} $$


---

1. Create Monte Carlo Function part 1
2. Calculate the number of daughter atoms from simulation
3. Plot Populations of Parents and Daughters
4. Use np.interp to find time taken for N to half
5. Create Monte Carlo Function part 2
6. Calculate the number of daughter and grandaughter atoms from simulation
7. Plot Populations of Parents, Daughters and Grandaughters
8. Find the maximum daughter count
9. Find the time corresponding to the maximum daughter count
10. Find no. of layers to absorb 50% of neutrons emitted
11. Plot the number of of transmitted neutrons as shield thickness is varied
12. Use np.interp to find shield thickness count at 1%
13. Calculate fraction of of transmitted neutrons as shield thickness is varied
14. Plot fraction of transmitted neutrons as shield thickness is varied
