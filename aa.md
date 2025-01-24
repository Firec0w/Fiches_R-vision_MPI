# Formulaire de mécanique

### Définition initiale
Δ est un axe fixe, **D** est un point appartenant à Δ, \( O, O', M \) sont des points de l'espace, et \( H \) est le projeté orthogonal de \( M \) sur Δ.

---

## Référentiels non Galiléens

| **Nom de la formule**                                   | **Expression mathématique**                                                                                                         |
|---------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Formule de dérivation composée                         | \( \frac{\mathrm{d}\vec{U}}{\mathrm{d}t}\Big|_{\mathcal{R}} = \frac{\mathrm{d}\vec{U}}{\mathrm{d}t}\Big|_{\mathcal{R}'} + \vec{\Omega}_{\mathcal{R'}/\mathcal{R}} \wedge \vec{U} \) |
| Vitesse                                                 | \( \vec{v}_{\mathcal{R}}(M) = \vec{v}_{\mathcal{R}'}(M) + \vec{v}_e(M) \)                                                        |
| Vitesse d'entraînement                                 | \( \vec{v}_e(M) = \vec{v}_{\mathcal{R}}(O') + \vec{\Omega}_{\mathcal{R}'/\mathcal{R}} \wedge \vec{O'M} \)                        |
| Vitesse en translation uniforme                        | \( \vec{v}_{\mathcal{R}}(M) = \vec{v}_{\mathcal{R}'}(M) + \vec{v}_e(M) = \vec{v}_{\mathcal{R}}(O') + \vec{v}_{\mathcal{R}}(O') \) |
| Vitesse en rotation uniforme d'axe fixe               | \( \vec{v}_{\mathcal{R}}(M) = \vec{v}_{\mathcal{R}'}(M) + \vec{\Omega}_{\mathcal{R}'/\mathcal{R}} \wedge \vec{HM} \)            |
| Accélération en translation uniforme                   | \( \vec{a}_{\mathcal{R}}(M) = \vec{a}_{\mathcal{R}'}(M) + \vec{a}_{\mathcal{R}}(O') \)                                           |
| Accélération en rotation uniforme d'axe fixe          | \( \vec{a}_{\mathcal{R}}(M) = \vec{a}_{\mathcal{R}'}(M) + \vec{a}_c(M) + \vec{a}_e(M) \)                                         |
| Accélération de Coriolis                               | \( \vec{a}_e(M) = 2\vec{\Omega}_{\mathcal{R}'/\mathcal{R}} \wedge \vec{v}_{\mathcal{R}'}(M) \)                                   |
| Accélération d'entraînement                            | \( \vec{a}_c(M) = -\Omega^2_{\mathcal{R}'/\mathcal{R}} \vec{HM} \)                                                              |
| Théorème de la résultante dynamique                    | \( \vec{a}_{\mathcal{R}'} = \sum \vec{F_{\text{ext}}} - m\vec{a}_e - m\vec{a}_c = \sum \vec{F_{\text{ext}}} + \vec{F}_{ie} + \vec{F}_{ic} \) |
| Théorème du moment cinétique                           | \( \frac{\mathrm{d}\vec{\mathcal{L}}_{A/\mathcal{R'}}}{\mathrm{d}t}\Big|_{\mathcal{R}} = \sum \vec{\mathcal{M}}_A(\vec{F}_{\text{ext}}) + \vec{\mathcal{M}}_A(\vec{F}_{ie}) + \vec{\mathcal{M}}_A(\vec{F}_{ic}) \) |

---

## Énergétique

| **Nom de la formule**               | **Expression mathématique**                                                                 |
|-------------------------------------|-------------------------------------------------------------------------------------------|
| Puissance d'une force               | \( \mathcal{P}(\vec{f}) = \vec{f} \cdot \vec{v} \)                                        |
| Travail élémentaire                 | \( \delta W(\vec{f}) = \mathcal{P}(\vec{f}) \mathrm{d}t = \vec{f} \cdot \mathrm{d}\vec{OM} \) |
| Force conservative                  | \( \exists E_p \text{ tel que } \delta W(\vec{f}) = -\mathrm{d}E_p \)                    |
| Travail d'une force                 | \( W(\vec{f}) = \int_{M \in \overset{\curvearrowright}{AB}} \delta W(\vec{f}) \)          |
| Condition pour qu'une force dérive d'une énergie potentielle | \( \nabla \wedge
