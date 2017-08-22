# RoboRoach

Roach-Wiring.svg should provide a slightly clearer diagram about wiring Robo Roach up.

## How Robo Roach's Circuit Works

It might be difficult to understand how Robo Roach's circuit is allowing the robot to avoid obstacles. Essentially each of the two motors is being supplied current by one of the AA Batteries, the battery that is in use by a given motor depends on the position of the toggle switches.

This should mean when one of the Roach's 'antenna' encounters an obstacle, the robot will reverse the direction of the motor+wheel that's associated with that antenna.

## More Technical information
This person:

[Jerome Demers](http://www.instructables.com/id/How-to-Build-a-Robot---The-BeetleBot/#step16)

Provides a really nice page describing in detail the same kind of circuit that runs in RoboRoach and provides some nice diagrams of the current flow in the circuit. Check it out!

## Possible problems:

If you find that the motor stops, when it encounters an obstacle (rather than reversing) it would suggest that you've wired up the robot slightly wrong (the NO terminal has now become redundant in this situation!) Technically the robot can still avoid some obstacles, as this happened to me once during testing, but it's not operating quite right!
