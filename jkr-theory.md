# Johnson-Kendall-Roberts (JKR) Theory

The JKR contact area between two elastic spheres is larger than predicted by Hertzian theory.
This is because adhesive forces act to pull the surfaces together, effectively increasing the contact radius.
The JKR model applies when the surfaces are relatively soft and the adhesion is significant.
Adhesion causes the contact area to grow even under zero applied load.
The key insight is that the contact area in JKR theory depends on both the elastic properties and the surface energy of the materials.

## Fundamental Equations

The JKR contact radius `a` under an applied load `P` is given by:

$$a^3 = rac{3R}{4E^*} \left( P + 3\pi\gamma R + \sqrt{6\pi\gamma R P + (3\pi\gamma R)^2} ight)$$

where:
- `R` is the reduced radius of the two spheres: `1/R = 1/R₁ + 1/R₂`
- `E*` is the reduced elastic modulus: `1/E* = (1-ν₁²)/E₁ + (1-ν₂²)/E₂`
- `γ` is the work of adhesion (surface energy per unit area)

## Pull-off Force

One of the most important predictions of the JKR theory is the pull-off force — the tensile force required to separate two adhered elastic bodies:

$$P_{c} = -rac{3}{2}\pi\gamma R$$

This is independent of the elastic modulus and depends only on the surface energy and the geometry.

## Contact Area at Zero Load

Even when no external load is applied (`P = 0`), the JKR theory predicts a finite contact area:

$$a_0^3 = rac{3R}{4E^*} \cdot 6\pi\gamma R$$

This contrasts sharply with Hertzian theory, which predicts zero contact area at zero load.

## Comparison with Hertzian Theory

| Property | Hertzian | JKR |
|---|---|---|
| Adhesion | Ignored | Included |
| Contact area at P=0 | Zero | Finite |
| Pull-off force | Zero | (3/2)πγR |
| Contact radius | Smaller | Larger (due to adhesion) |

## Applicability

The JKR model is most applicable when:
- The materials are relatively soft (low elastic modulus)
- The surface energy (adhesion) is high
- The dimensionless Tabor parameter `μ > 5`

For stiffer materials with weaker adhesion (`μ < 0.1`), the Derjaguin-Muller-Toporov (DMT) model is more appropriate. The Maugis-Dugdale model provides a unified framework that bridges the JKR and DMT limits.

## References

1. Johnson, K.L., Kendall, K., & Roberts, A.D. (1971). "Surface Energy and the Contact of Elastic Solids." *Proceedings of the Royal Society of London A*, 324(1558), 301–313.
2. Maugis, D. (1992). "Adhesion of Spheres: The JKR-DMT Transition Using a Dugdale Model." *Journal of Colloid and Interface Science*, 150(1), 243–269.
3. Tabor, D. (1977). "Surface Forces and Surface Interactions." *Journal of Colloid and Interface Science*, 58(1), 2–13.
