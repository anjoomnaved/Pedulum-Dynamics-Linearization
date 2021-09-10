# Pedulum-Linearization
Using the linearization approach to dynamically reduce the dependent and independent variables while solving a practical pendulum. Practical pendulum refers to the takeoff angle to be more than 10 degrees but less than 90 degrees(acute angles only)

*Motivation:*

**a.>** Given a nonlinear differential equatiion, we obtain an equivalent linear dynamics around a **given Operating Point**

**b.>** Obtain an s-domain(Laplace Domain) representation using the linearized model and thus obtain the system's Transfer Function(TF)

This will allow us to reduce the number of dynamic variables in the systems
We start this project with an assumption that the systems has:

**a.>** **No chaotic behaviour** at/around that operating point 

**b.>** Has enough energy to retain its momemtum around the operating point 

**c.>** Has takeoff angles less than 90 degrees, although an angle greater than 90 degrees will work the same way,with an additional jerk at theta=zero degrees which might trigger Chaotic Behaviour

We will also obtain a **Transfer Function Block at the end so as to describe the transfer process of the linearized system.**
