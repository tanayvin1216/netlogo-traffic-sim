# NetLogo Traffic Simulation

This project is an agent-based traffic simulation built in NetLogo. Cars travel along a single-lane road, obey traffic lights, maintain safe following distances, and record travel metrics.

## Model Behavior
- Cars spawn from the left edge at a configurable rate
- Vehicles stop for red lights within a fixed stopping distance
- Cars decelerate and accelerate smoothly
- Traffic lights use staggered timing to create a green wave

## Metrics
- Average travel time
- Average number of stops per vehicle

## How to Run
1. Open the `.nlogo` file in NetLogo
2. Click `setup`
3. Click `go`
4. Adjust sliders such as `traffic`, `num-lights`, `cycle-length`, and `green-fraction`

## Sample Model Run Through 
![SciProgFinalProjectGIF](https://github.com/user-attachments/assets/33467386-c655-4228-a2f4-4f129a1fbaea)

## Future Work
This model could be expanded to explore how individual human behaviors scale into larger societal outcomes, such as traffic congestion, evacuation flow, or emergency response. Simulations like this provide a low risk way to test assumptions and interventions before applying them in real world settings, making them useful tools for understanding and managing complex social systems.
