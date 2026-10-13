# Epidemic Modelling Using SIR Models

## Summary

In this project, we explore the modelling and simulation of an epidemic using the **SIR (Susceptible–Infectious–Recovered) model**, a mathematical model used in epidemiology to represent three categories of people:

- **S — Susceptible:** People who are capable of contracting the disease if they come into contact with an infected individual.
- **I — Infectious:** People who are infected and capable of transmitting the disease to susceptible individuals.
- **R — Recovered:** People who have recovered from the infection and are assumed to be immune to reinfection in the basic model. This category can also include individuals who have died from the infection, as they can no longer contract it.

We defined two key parameters, `beta` and `gamma`, representing the contact rate and recovery rate, respectively. We also established the mathematical equations that describe how each category changes over time.

We began with a **basic SIR model**, using fixed values of `beta` and `gamma` to examine how these parameters influence the proportion of infected individuals within a fixed and closed population.

Next, we explored the model using a range of parameter values to understand the uncertainty involved in choosing `beta` and `gamma`, and how different choices can affect the simulation results.

Finally, we extended the model by introducing a fourth category, **V — Vaccinated**, along with a new parameter, `alpha`, representing the vaccination rate. We modified the model equations accordingly and used a fixed value of `alpha` to simulate how vaccination can help control the spread of an epidemic.

Through this project, we explore epidemic dynamics, parameter sensitivity, and the potential impact of vaccination using Python-based mathematical modelling and simulation.


#Aditya Prasad Jena
