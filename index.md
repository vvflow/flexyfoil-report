---
layout: page
---

## Locomotion of the fish-like foil under own effort

### The fish-like model

The moment of force `Mf` is applied between the first and second
sections by harmonic law, resulting in the bending of the fish body.
This simulates the muscular effort of a fish. The second hinge is elastic
and passive. The flow-structure task is solved.

![]({{site.baseurl}}/images/a-1.png)

### Numerical method of Viscous Vortex Domains

Governing equations:

![]({{site.baseurl}}/images/a-2.png)

Diffusion velocity:

![]({{site.baseurl}}/images/a-3.png)

### Boundary conditions

Biot-Savart law:

![]({{site.baseurl}}/images/a-4.png)

The equations of motion of the sections:

![]({{site.baseurl}}/images/a-5.png)

### The expression of force and moment via the vortex flux from the surfaces

Substituting these expressions into the equations of motion of bodies,
we obtain the equations, which, together with the equations of the
boundary conditions, form a closed linear system of equations. The
solution of this system gives us the values ​ of the velocities of all
sections and circulations of new particles simultaneously.

![]({{site.baseurl}}/images/a-6.png)

### The numerical results

![]({{site.baseurl}}/images/a-7.png)

<!-- ![]({{site.baseurl}}/images/a-8.png) -->
<iframe width="100%" height="390" src="https://www.youtube.com/embed/aul8yfJHu5o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/>

### Rigid tail

![]({{site.baseurl}}/images/a-9.png)

<iframe width="100%" height="390" src="https://www.youtube.com/embed/Tgguhu8G-PA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/>

### Floppy tail

![]({{site.baseurl}}/images/a-10.png)

<iframe width="100%" height="390" src="https://www.youtube.com/embed/aZoNvn7rGjE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/>

### Parametric research

![]({{site.baseurl}}/images/a-11.png)
![]({{site.baseurl}}/images/a-12.png)

### Piecewise-linear `sin()` approximation

![]({{site.baseurl}}/images/lsin.png)

δ = 0.03

<iframe width="100%" height="390" src="https://www.youtube.com/embed/zW2rwcQGvKg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
