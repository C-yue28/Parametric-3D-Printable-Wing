# A Parametric and Fully 3D-Printable Wing

## Basic design parameters
- Chord Length: $c$ - default 100 mm
- Aspect Ratio: $AR$ - default 10
- Wingspan: $b=AR*c$

## Advanced aerodynamic parameters
- Taper ratio: $\lambda$ ($0-1$) - default 0.5
- Sweep angle: $\phi$ (measured from a horizontal axis) - default 0 degrees
- Dihedral angle: $\beta$ - default 0 degrees

## Mechanical parameters
- Rib angle: $\theta$ - default 45 degrees
- Rib offset: $D_{rib} = \frac{2c \cos\theta}{3 \sin\theta}$
- Rib count: $N_{rib} = floor\left(\frac{b}{2D_{rib}}\right)$
- Rib thickness: - default 2 mm
- Surface thickness - default 0.5 mm
- Spar diameter (cylindrical) - default 4 mm

## Interface parameters
- Width/placement - default 20% of chord length starting from leading edge
- Pin length - default 10 mm
- Fillet radius - default 2 mm
