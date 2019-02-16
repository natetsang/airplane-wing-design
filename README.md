# Airplane wing design using ML to improve simulation time

The design of mechanical systems is the foundation for nearly all physical engineering creations--- from simple structures like a kitchen table to complex systems such as a commercial aircraft. The development of these systems undergo a significant series of steps, beginning with defining initial specifications, generating, analyzing, and selecting the optimal solution, and finally testing and implementing this solution.

An example of this process is in the aerodynamic design of airplane wing structures. Airplane wings operate on the theory of flight, in which a wing will undergo a lift force and a drag force. In the development of a wing, an engineer or company will set a lift and drag requirement for the structure, which necessitates proper design and analysis procedures.

Engineers rely on physics simulation and analysis tools to guide the work flow for meeting certain criteria. One such tool to simulate the lift and drag of an airplane is through Computational Fluid Dynamics (CFD). While these tools produce highly accurate models and results, simulations are computationally demanding, especially if an engineer is iterating through various designs with subtle tweaks between each one.

Rapidly evolving machine learning tools have unveiled new methods to predict the behavior of certain parameters. Using lift results from CFD software, we investigated the prospect of using machine learning (ML) models to predict the performance (i.e. lift) of an airfoil depending on the airfoil's geometry and test environment.
