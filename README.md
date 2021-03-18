# livemap-pioneer

This is a project to write a live map to the pioneer space simulator:
 http://pioneerspacesim.net/

## Initial objectives:

### Understand pioneer's physics: (inspect src/DynamicBody.cpp and src/Ship.cpp)

- [ ] src/DynamicBody.cpp
- [ ] src/Ship.cpp
- [ ] src/Space.cpp
- [ ] src/collider/\*

### Find ways to expose the relevant data, preferably without touching the pioneer source (lua?)

Suggestion from sturnclaw: use SDL\_net updated inside GameLoop::Update() to
export game data.

## Future goals:

- [ ] Plot current player and main system objects position on a web interface
- [ ] Calculate player future trajectory based on current data
- [ ] Plan future manouvers and plot the initial, current and planned trajectories
