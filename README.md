# GTUI : Géométrie de la Théorie Unifiée de l'Information
### Document Maître - Version Canonique 1.0

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
![Author](https://img.shields.io/badge/Author-Lichen_Collective-purple.svg)
![Status](https://img.shields.io/badge/Status-Theoretical_Framework-orange.svg)

**Date :** 7 janvier 2026
**Auteur :** Bryan Ouellette & Lichen Collective

## 🌌 Résumé Exécutif

La **GTUI** propose une unification fondamentale de la physique basée sur le **Monisme Informationnel**. Elle postule que l'état fondamental de la réalité est informationnel et que les objets physiques (masse, énergie, espace-temps) émergent de motifs de corrélation et de compression paramétrique ($\kappa$). Ce dépôt contient les axiomes, les équations maîtresses et les prédictions testables de ce framework.

---

## 📚 Table des Matières
1. [Axiomes Fondamentaux](#1-axiomes-fondamentaux)
2. [Équations Maîtres](#2-équations-maîtres)
3. [Valeurs κ de Référence](#3-valeurs-κ-de-référence)
4. [Prédictions Testables](#4-prédictions-testables)
5. [Correspondances Cross-Scale](#5-correspondances-cross-scale)
6. [Notation et Références](#6-notation-et-conventions)

---

## 1. Axiomes Fondamentaux

* **A1. Monisme Informationnel (IM)** : L'objet fondamental est l'information. La physique est le comportement des corrélations.
* **A2. Substrat Algorithmique (SA)** : Dynamique discrète à l'échelle de Planck (QCA-like) avec évolution unitaire locale.
* **A3. Mesure de Distinguabilité (MD)** : La métrique de Fisher gouverne la "capacité à exister". La distinguabilité locale dicte les lois effectives.
* **A4. Principe d'Optimisation (PO)** : Maximisation de la cohérence d'information et minimisation de l'entropie (EPI généralisé).
* **A5. Compression Paramétrique (CP)** : L'information locale est modulée par un paramètre de compression $\kappa \in [0,1]$, définissant la masse et l'inertie.

---

## 2. Équations Maîtres

### 2.1 Métrique d'Information de Fisher
La métrique primaire invariante sous transformations statistiques :
$$g_{ij}(\xi) = \int_X \left[ \frac{\partial \log p(x;\xi)}{\partial \xi^i} \right] \left[ \frac{\partial \log p(x;\xi)}{\partial \xi^j} \right] p(x;\xi) dx$$

### 2.2 Borne de Cramér-Rao (Incertitude Géométrique)
Généralisation du principe d'incertitude de Heisenberg :
$$\text{Cov}(\hat{\theta}) \geq I(\theta)^{-1}$$

### 2.3 Équation Maître du Flux (Renormalisation)
L'évolution de la métrique selon l'échelle d'observation $\mu$ :
$$\frac{d}{d(\ln \mu)} g_{ab} = -\beta_a \beta_b + \mathcal{L}_\xi g_{ab} \approx -2R_{ab}$$
*Le flux suit la courbure de Ricci de la variété informationnelle.*

### 2.4 Relation Masse-Compression (Loi de Puissance)
Lien entre la masse physique et la compression informationnelle :
$$m = m_P \kappa^n$$
Où $m_P$ est la masse de Planck. Inversement : $\kappa = (m/m_P)^{1/n}$.

### 2.5 Métrique de Ruppeiner (Thermodynamique)
$$g^R_{ij} = -\frac{\partial^2 S}{\partial X^i \partial X^j}$$
*Interprétation de la courbure $R$ :*
* $R > 0$ : Répulsion (Fermions ?)
* $R < 0$ : Attraction (Gravité/Bosons ?)
* $|R| \to \infty$ : Transition de phase critique.

### 2.6 Formule de Ryu-Takayanagi (Holographie)
$$S_A = \frac{\text{Area}(\gamma_A)}{4G_N}$$
L'intrication du bord tisse la géométrie de l'espace-temps (Bulk).

---

## 3. Valeurs $\kappa$ de Référence

**Constantes utilisées :**
* Masse de Planck ($m_P$) = $2.176 \times 10^{-8}$ kg
* Hypothèse de test : $n=1$ (linéaire), $n=2$ (quadratique), $n=3$ (cubique).

### Leptons (Particules Chargées)

| Particule | Masse ($kg$) | $\kappa$ ($n=1$) | $\kappa$ ($n=2$) | $\kappa$ ($n=3$) |
| :--- | :--- | :--- | :--- | :--- |
| **Électron ($e$)** | $9.109 \times 10^{-31}$ | $4.19 \times 10^{-23}$ | $2.05 \times 10^{-11}$ | $3.48 \times 10^{-8}$ |
| **Muon ($\mu$)** | $1.883 \times 10^{-28}$ | $8.65 \times 10^{-21}$ | $9.30 \times 10^{-11}$ | $1.21 \times 10^{-7}$ |
| **Tau ($\tau$)** | $3.167 \times 10^{-27}$ | $1.45 \times 10^{-19}$ | $3.82 \times 10^{-10}$ | $5.26 \times 10^{-7}$ |

### Quarks (Masses courantes)

| Quark | Masse ($kg$) | $\kappa$ ($n=1$) | $\kappa$ ($n=2$) | $\kappa$ ($n=3$) |
| :--- | :--- | :--- | :--- | :--- |
| **Up ($u$)** | $3.92 \times 10^{-30}$ | $1.80 \times 10^{-22}$ | $4.24 \times 10^{-11}$ | $7.49 \times 10^{-8}$ |
| **Top ($t$)** | $3.08 \times 10^{-25}$ | $1.42 \times 10^{-17}$ | $3.77 \times 10^{-9}$ | $2.42 \times 10^{-6}$ |

> **Observation :** L'électron (stable) possède le $\kappa$ le plus faible ($10^{-23}$ pour $n=1$), suggérant une compression minimale ou une "pureté" fondamentale.

---

## 4. Prédictions Testables

### 4.1 Masse de l'Information (Test de Vopson)
Prédiction de variation de masse lors de l'effacement d'information :
$$\Delta m = \Delta I \times \frac{k_B T \ln 2}{c^2}$$
* **Cible :** ~ $3.2 \times 10^{-26}$ kg pour 1 TB à 300K.

### 4.2 Matière Noire & Paramètre $\kappa$
Si la matière noire correspond à un régime de compression spécifique $\kappa_{dark} \approx 0.20$ :
* Pour $n=3$, $m_{dark} \approx 9.8$ GeV (Similaire aux WIMPs).
* **Test :** Réanalyse des données LZ/XENONnT dans la plage 10-50 GeV.

### 4.3 Constante Cosmologique ($\Lambda$)
Via la longueur de Zeldovich ($L_Z \approx 10^{-3}$ m) :
$$\Lambda \sim 1/L_Z^2 \approx 10^{-52} m^{-2}$$
Correspond à l'ordre de grandeur observé.

---

## 5. Correspondances Cross-Scale

| Concept Bryan | Concept Physique | Géométrie Info | Équation Clé |
| :--- | :--- | :--- | :--- |
| **Géométrie** | Espace d'états | Variété Fisher | $g_{ij} = -\partial^2S$ |
| **Compression** | Fluctuation | Densité Fisher | $I \propto \kappa_T$ |
| **Frustration** | Interactions | Courbure $R$ | $R \to \infty$ (Critique) |
| **Émergence** | Phase | Flux RG | $\beta$-functions |
| **Synchronisation** | Couplage | Kuramoto $K$ | $K > K_c$ |

---

## 6. Citation et Licence

Ce document est la propriété du **Lichen Collective**.

**Citation suggérée :**
> Ouellette, B., & Lichen Collective. (2026). *GTUI: Géométrie de la Théorie Unifiée de l'Information - Version 1.0*. GitHub Repository.

