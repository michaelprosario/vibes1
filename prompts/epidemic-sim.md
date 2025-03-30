Write a simulator using the following user stories.
- Create a file called epidemic.html
- use p5.js to visualize the major simulation events, locations, and people involved
- use colors to visualize the types of events and people.
- Please use classes to organize the code.


Epidemic Simulator User Stories
Here are user stories for an epidemic simulator that incorporates Monte Carlo simulation techniques and visualizes major events over a multi-year timespan in Orlando:
Core Simulation Functionality

As a public health official, I want to initialize a simulation with Orlando's demographic data, so that the model accurately reflects the local population distribution.
As an epidemiologist, I want to set pathogen parameters (R0, incubation period, infectious period, mortality rate), so that I can model different disease types.
As a researcher, I want to run Monte Carlo simulations with randomized variables, so that I can account for uncertainty and generate probability distributions of outcomes.
As an analyst, I want to set the simulation timescale to span multiple years, so that I can observe long-term epidemic patterns including seasonality effects.

Location-Based Features

As a city planner, I want to import Orlando's geographical data including neighborhoods, business districts, and transportation hubs, so that the simulation reflects realistic movement patterns.
As a public health strategist, I want to designate specific high-traffic locations (theme parks, airports, convention centers) as potential transmission hotspots, so that I can model Orlando's unique urban characteristics.
As an emergency manager, I want to model hospital and healthcare facility capacities across Orlando, so I can predict and visualize potential system overloads.

Visualization Requirements

As a decision-maker, I want to visualize infection spread across an Orlando map over time, so I can identify neighborhood-level patterns and at-risk areas.
As a stakeholder, I want to see animated timeline visualizations of key epidemic metrics (cases, hospitalizations, deaths), so I can understand the progression of the outbreak.
As a health official, I want visual indications when significant events occur (first case, hospital capacity reached, vaccine deployment), so I can mark important milestones.

Intervention Modeling

As a policy planner, I want to implement and visualize the effects of various interventions (masks, social distancing, closures) at different points in the timeline, so I can compare intervention strategies.
As a public health director, I want to model and visualize vaccine/treatment deployment across Orlando neighborhoods with customizable distribution strategies, so I can optimize resource allocation.
As a researcher, I want intervention effectiveness to vary based on realistic compliance rates using Monte Carlo sampling, so that the model captures behavioral uncertainty.

Analysis Tools

As an analyst, I want to compare multiple simulation runs with different parameters side-by-side, so I can identify which variables most significantly impact outcomes.
As a public health communicator, I want to generate reports highlighting key statistics and visualizations from the simulation, so I can share findings with stakeholders.
As a researcher, I want to extract probability distributions for key outcomes (peak infection date, total cases, mortality) based on multiple Monte Carlo runs, so I can communicate uncertainty in predictions.
As a planner, I want to identify the optimal timing and location for intervention deployment based on simulation results, so I can maximize intervention effectiveness.

