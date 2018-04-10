# SpaceGame AI
Simple examples of space game AI, core part of a new game

# Important AI Behaviour Tests

## General Ship Steering

### Wander
* *Description:* The ship will wander aimlessly around an area
* *Expected Behaviours:* Given a certain radius, the ship will gradually drift. The ship should stay within the radius and not get near the edge of the circle. The ship's wandering should be gradual / smooth and not erratic. 
* *Importance:* **5 / 10**
* *Status:* **Un-implemented**

### Follow
* *Description:* The ship will attempt to follow or approach an entity and match it's velocity
* *Expected Behaviours:* Given a static and dynamic target, the ship will attempt to follow, match the predicted heading and velocity. 
* *Importance:* **5 / 10**
* *Status:* **Un-implemented**

## Combat Ship Steering

### Attack
* *Description:* Ship will predict enemy movements and fire to intercept target. 
* *Expected Behaviours:* Ship will attempt to decipher enemy movements and fire on target.
* *Importance:* **5 / 10**
* *Status:* **Un-implemented**

## Politics
Console based simulation.
There are multiple factions in the game.
Each faction has the following:
* Resource Pool
* Military Strength Rating
* Stack of history events that influence future events. Relations are built out of this.
* Personality factors (Aggressiveness, Grudge holding)

Start with 3 factions and give them certain parameters.
Build decision trees that tell what action that empire will take next.

Example:
* Empire 1 has a military strength 200 higher than Empire 2 but is peaceful. 
* Empire 1 is normally peaceful but, iterating through the history stack, Empire 1sees that Empire 2 attacked them twice.
* Empire 1 attacks Empire 2.


### Template
> * *Description:* Short description here
> * *Expected Behaviours:* What behaviour should be exhibited
> * *Importance:* **[0 - 10] / 10**
> * *Status:* **Un-implemented** / **WIP** / **Partially Implemented** / **Fully Implemented**
