---
{"dg-publish":true,"permalink":"/astronomy/cosmology/introduction-to-cosmology-1-daniel-baumann/"}
---

# Course Outline 
![Lecture1_page-0001.jpg](/img/user/Astronomy/Cosmology/Lecture1_img/Lecture1_page-0001.jpg)

![Lecture1_page-0002.jpg](/img/user/Astronomy/Cosmology/Lecture1_img/Lecture1_page-0002.jpg)

![Lecture1_page-0003.jpg](/img/user/Astronomy/Cosmology/Lecture1_img/Lecture1_page-0003.jpg)


# Introduction


![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-02.jpg?height=1303&width=1737&top_left_y=1510&top_left_x=165)

### Main Goal

- **Objective:**  
    To derive and ultimately solve the fundamental equation that describes the evolution of the entire universe.

- At first glance, modeling the entire universe may seem even more daunting than, for example, predicting the weather a week from now on Earth—something known to be notoriously difficult.

- However, at very large (cosmic) scales, and especially as we look back in time (to the early universe), the universe becomes increasingly smooth and homogeneous.
        
- By averaging over all small-scale complexities, the overall description of the universe is drastically simplified.

- **Key Insight:**
    - On these scales, the universe can be characterized by a **single function of time**.
        
    - The evolution of this function is governed by a **differential equation**, which we will derive in this lecture.

Thus, while the microscopic physics is complex, the mathematics governing the large-scale evolution of the universe is surprisingly straightforward.

![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-03.jpg?height=761&width=1614&top_left_y=619&top_left_x=227)

## Hubble's Law (1)

In 1929, Hubble discovered the velocity-distance relation of galaxies:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-03.jpg?height=638&width=814&top_left_y=1800&top_left_x=244)
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-03.jpg?height=638&width=712&top_left_y=1797&top_left_x=1106)

Inferred from redshifts
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-03.jpg?height=184&width=1021&top_left_y=2518&top_left_x=780)



### Historical Context

- The story of the expanding universe, at the **observational level**, begins in **1929** with **Edwin Hubble’s discovery** of a relationship between the velocities and distances of galaxies.

### Hubble’s Original Data and Methods

- **Hubble’s Plot:**
    
    - Plotted the **velocity** of individual galaxies (**y-axis**, measured in kilometers per second, km/s) against their **distance** (**x-axis**, measured in “megaparsecs”).
        
    - **Parsec (pc):** Astronomical distance unit; 1 parsec ≈ 3.26 light years; 1 megaparsec = 1 million parsecs.
        
    - The use of megaparsecs may seem unusual, but it’s standard in astronomy.
        
- **Data Collection:**
    
    - **Velocity measurements**: Obtained from redshift data provided by another astronomer (notably Slipher).
        
    - **Distance measurements:**
        
        - Hubble used **Cepheid variable stars** within galaxies.
            
        - Cepheids provide a measure of **absolute luminosity**.
            
        - By comparing **apparent luminosity** (as observed) and **absolute luminosity** (known from Cepheid properties), he could infer **distances** to galaxies.
            
    - **Note:**
        
        - Measuring **velocities** (via redshift) is relatively easy.
            
        - **Distance measurement** in cosmology remains challenging and debated even today.
            

### The Hubble Law

- **Initial Results:**
    
    - Hubble’s original 1929 plot (left side of the referenced figure) showed a **correlation**: galaxies with higher velocities tend to be farther away.
        
    - The correlation wasn’t striking with the original (limited) dataset.
        
- **Further Data (1932):**
    
    - Additional measurements (red points in later plots), at greater distances and higher redshifts, revealed a much clearer **linear relationship** between galaxy velocity and distance.
        
- **Formulation:**
    
    - Hubble formalized this as the **Hubble Law**: $$
v=H_0 d
$$where $v$ is galaxy velocity, $d$ is distance, and $H_0$ is the Hubble constant (the slope of the line).

**Key Takeaway:**  
Hubble’s work provided the first strong observational evidence that the universe is **expanding**—the farther away a galaxy is, the faster it is receding from us.


## Hubble's Law (2)

In General Relativity, this can be interpreted as the expansion of space:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-04.jpg?height=575&width=1501&top_left_y=438&top_left_x=321)

$$
V \equiv \dot{R}=\frac{\dot{a}}{a} R \equiv \underbrace{H}_{\text {Hubble parameter }} R
$$








## Hubble's Law

The observed value of the Hubble constant is

$$
H_{0}=(68 \pm 2) \mathrm{km} \mathrm{~s}^{-1} \mathrm{Mpc}^{-1}
$$

where $\mathrm{Mpc}=3.2 \times 10^{6}$ light-years.

The corresponding Hubble time and Hubble distance are

$$
\begin{aligned}
t_{H} \equiv H_{0}^{-1}=(14.38 \pm 0.42) \mathrm{Gyrs} \\
d_{H} \equiv c H_{0}^{-1}=(4380 \pm 130) \mathrm{Mpc} \sim 10^{26} \mathrm{~m}
\end{aligned}
$$

These are the characteristic age and size of the universe.

Let us now determine the evolution of the scale factor.
We will do this using Newtonian gravity (but comment on GR corrections).

Consider a spherical region in a homogeneous universe:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-05.jpg?height=512&width=997&top_left_y=572&top_left_x=535)

The force on a test particle on the surface of the sphere is

$$
F=-\frac{G M m}{R^{2}}
$$

## Friedmann Equation

The acceleration of the test particle is

$$
\frac{d^{2} R}{d t^{2}}=-\frac{G M}{R^{2}}
$$

![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-05.jpg?height=350&width=507&top_left_y=1581&top_left_x=1374)

Integrating this gives the conservation of energy:

$$
\frac{1}{2}\left(\frac{d R}{d t}\right)^{2}-\frac{G M}{R}=U=\mathrm{const}
$$

Substituting $M=\frac{4 \pi}{3} R^{3} \rho$ and $R(t)=a(t) R_{0}$, we find
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-05.jpg?height=315&width=754&top_left_y=2421&top_left_x=551)

$$
\left(\frac{\dot{a}}{a}\right)^{2}=\frac{8 \pi G}{3} \rho+\frac{2 U}{R_{0}^{2}} \frac{1}{a^{2}}
$$

There are three different cases:

In GR, these correspond to:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-06.jpg?height=258&width=326&top_left_y=919&top_left_x=388)
negatively curved
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-06.jpg?height=255&width=338&top_left_y=929&top_left_x=836)
positively curved
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-06.jpg?height=226&width=336&top_left_y=932&top_left_x=1294)
flat
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-06.jpg?height=341&width=497&top_left_y=189&top_left_x=1382)
$U>0$
expands forever
er
$U<0$
stops and recollapses
$U<0$
and recollapses
$U=0$
limiting case
$U=0$
ter the the

Observations favor a flat universe.

## Friedmann Equation

For a flat universe, the Friedmann equation reduces to

$$
H^{2}=\frac{8 \pi G}{3} \rho
$$

From the measured value of the Hubble constant, we infer the average density of the Universe today:

$$
\begin{aligned}
\rho_{0}=\frac{3 H_{0}^{2}}{8 \pi G} & =0.8 \times 10^{-29} \mathrm{grams} \mathrm{~cm}^{-3} \\
& =1.3 \times 10^{11} M_{\odot} \mathrm{Mpc}^{-3} \\
& =5.1 \text { protons } \mathrm{m}^{-3}
\end{aligned}
$$

## Friedmann Equation

In GR, the Friedmann equation is derived from the Einstein equation:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-07.jpg?height=249&width=1457&top_left_y=381&top_left_x=331)

$$
H^{2}=\frac{8 \pi G}{3} \rho
$$

where the mass density is replaced by the energy density $\varepsilon \equiv \rho c^{2}$.
(In natural units ( $c \equiv 1$ ), we use $\rho$ and $\varepsilon$ interchangeably.)

To solve the Friedmann equation, we need to know how the energy density evolves as the Universe expands.

## Cosmic Inventory

The Universe is filled with four different types of energy:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-07.jpg?height=535&width=1058&top_left_y=1857&top_left_x=502)

We need to determine how each of these components evolves and sources the expansion of the Universe.

## Fluid Equation

Consider a fluid in a box:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-08.jpg?height=404&width=406&top_left_y=392&top_left_x=731)

The energy density is

$$
\rho=E / V
$$

How does this evolve with increasing scale factor?

This can be derived from the First Law of thermodynamics (see appendix), or we can guess it.

## Matter

For a pressureless fluid (= matter), we get

$$
\rho \equiv \frac{E}{V} \propto a^{-3}
$$

![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-08.jpg?height=324&width=326&top_left_y=1611&top_left_x=1416)

Most of the matter in the Universe is non-luminous dark matter.
Ordinary matter is less than $5 \%$.

Feeding $\rho \propto a^{-3}$ into the Friedmann equation, we find

$$
\left(\frac{\dot{a}}{a}\right)^{2} \propto \rho \propto a^{-3} \longrightarrow a \propto t^{2 / 3}
$$

## Radiation

For a relativistic fluid (= radiation), we get

$$
\rho \equiv \frac{E}{V} \propto a^{-4}
$$

![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-09.jpg?height=324&width=324&top_left_y=215&top_left_x=1414)

Most of the radiation in the Universe are photons from the early universe (= cosmic microwave background). Starlight is less than $0.1 \%$.

Feeding $\rho \propto a^{-4}$ into the Friedmann equation, we find

$$
\left(\frac{\dot{a}}{a}\right)^{2} \propto \rho \propto a^{-4} \longrightarrow a \propto t^{1 / 2}
$$

## Matter and Radiation

The Universe was first dominated by radiation, then by matter:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-09.jpg?height=903&width=1405&top_left_y=1807&top_left_x=334)

In 1998, it was discovered that the Universe is accelerating. The source of the acceleration is unknown. We call it dark energy.
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-10.jpg?height=515&width=1526&top_left_y=459&top_left_x=305)
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-10.jpg?height=364&width=1226&top_left_y=989&top_left_x=301)

## Dark Energy

In 1998, it was discovered that the Universe is accelerating.
The source of the acceleration is unknown. We call it dark energy.
The simplest form of dark energy is a cosmological constant:

$$
R_{\mu \nu}-\frac{1}{2} R g_{\mu \nu}+\Lambda g_{\mu \nu}=8 \pi G T_{\mu \nu}
$$

Moving this term to the RHS, it becomes a vacuum energy:

$$
\rho \equiv \frac{E}{V}=\text { const }
$$

![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-10.jpg?height=326&width=329&top_left_y=2093&top_left_x=1509)

Feeding this into the Friedmann equation gives

$$
\left(\frac{\dot{a}}{a}\right)^{2} \propto \rho=\mathrm{const} \longrightarrow a \propto e^{H_{0} t}
$$

Today, the Universe is dominated by dark energy (Why now?):
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-11.jpg?height=924&width=1389&top_left_y=406&top_left_x=342)

## Cosmological Constant Problem

The observed value of the dark energy density is much smaller than our (naive) theoretical expectation:

$$
\rho_{\mathrm{QFT}} \sim \int_{0}^{\Lambda_{\mathrm{UV}}} \frac{\mathrm{~d} k^{3}}{(2 \pi)^{3}} \frac{1}{2} \hbar \sim \Lambda_{\mathrm{UV}}^{4} \ggg \rho_{\mathrm{obs}}=\left(2 \times 10^{-3} \mathrm{eV}\right)^{4}
$$

Sum over wavelengths
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-11.jpg?height=290&width=340&top_left_y=2225&top_left_x=1155)

Explaining the observed dark energy density remains one of the most important open questions in fundamental physics.

# Questions? 

## The Hot Big Bang

The Universe started in a hot and dense state:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-12.jpg?height=406&width=1203&top_left_y=1850&top_left_x=392)

As the Universe expands, it cools.
Many interesting things happened.
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-12.jpg?height=195&width=1580&top_left_y=2587&top_left_x=278)

The Universe is filled with almost equal amounts of matter and antimatter
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-13.jpg?height=437&width=1518&top_left_y=424&top_left_x=226)

As the universe cools, matter and antimatter annihilate.

For some mysterious reason, there was initially a fraction more matter than antimatter. This matter survived the annihilation.

Without this asymmetry we wouldn't exist.
$t=10^{-5} \mathrm{~s}$ Quarks and gluons condense into nuclei:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-13.jpg?height=1063&width=1594&top_left_y=1696&top_left_x=268)
$t=1 \mathrm{~s} \quad$ Neutrinos decouple and neutrons freeze out:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-14.jpg?height=1094&width=1594&top_left_y=281&top_left_x=274)
$t=3 \mathrm{~min} \quad$ Light elements (H, He, and Li) form:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-14.jpg?height=1074&width=1594&top_left_y=1693&top_left_x=271)
$t=370000 \mathrm{yrs} \quad$ Atoms form and the first light is released:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-15.jpg?height=1080&width=1603&top_left_y=285&top_left_x=266)

This afterglow of the Big Bang is still seen today:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-15.jpg?height=1004&width=1657&top_left_y=1711&top_left_x=208)
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-16.jpg?height=1094&width=1609&top_left_y=281&top_left_x=258)

This history of the Universe is an observational fact:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-16.jpg?height=540&width=1683&top_left_y=1689&top_left_x=184)

- The basic picture has been confirmed by many independent observations.
- Many precise details are probed by measurements of the CMB.


## Where did it all come from?

Appendix

## Fluid Equation

Consider a fluid in a box:
![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-18.jpg?height=406&width=409&top_left_y=391&top_left_x=732)

The First Law of thermodynamics implies

$$
\mathrm{d} E=\mathrm{d} Q-P \mathrm{~d} V
$$

Homogeneity doesn't allow any heat flow $(\mathrm{d} Q=0)$, so that $\frac{d E}{d t}=-P \frac{d V}{d t}$

## Fluid Equation

Using $E=\rho V$ and $V \propto a^{3}$, we find

$$
\frac{d E}{d t}=-P \frac{d V}{d t} \quad \longrightarrow \quad \frac{d \rho}{d t}=-3 \frac{\dot{a}}{a}(\rho+P) \quad \begin{aligned}
& \text { Fluid } \\
& \text { Equation }
\end{aligned}
$$

Cosmological fluids are described by a constant equation of state:

$$
w \equiv P / \rho
$$

The fluid equation then becomes

$$
\frac{\dot{\rho}}{\rho}=-3(1+w) \frac{\dot{a}}{a} \longrightarrow \quad \longmapsto \quad \rho \propto a^{-3(1+w)}
$$

## Equation of State

- For a pressureless fluid (= matter), we get

$$
w=0 \quad \longrightarrow \quad \rho \propto a^{-3}
$$

- For a relativistic fluid (= radiation), we get

$$
w=1 / 3 \quad \longrightarrow \quad \rho \propto a^{-4}
$$

- For the vacuum energy, we have

$$
w=-1 \quad \longrightarrow \quad \rho \propto a^{0}
$$

![](https://cdn.mathpix.com/cropped/2025_05_27_50cd43eba748c8e58b7eg-19.jpg?height=255&width=255&top_left_y=1072&top_left_x=1494)

## Acceleration Equation

Combining the Friedmann equation with the fluid equation

$$
\frac{d}{d t}\left[\left(\frac{\dot{a}}{a}\right)^{2}=\frac{8 \pi G}{3} \rho\right] \quad+\quad \frac{d \rho}{d t}=-3 \frac{\dot{a}}{a}(\rho+P)
$$

we get $\quad$| $\frac{\ddot{a}}{a}=-\frac{4 \pi G}{3}(\rho+3 P)$ |
| :--- |
| Acceleration |
| Equation |

There are two different cases:

$$
P>-\frac{1}{3} \rho \quad P<-\frac{1}{3} \rho
$$

Expansion slows down

$$
\ddot{a}<0
$$

Expansion speeds up

$$
\ddot{a}>0
$$

