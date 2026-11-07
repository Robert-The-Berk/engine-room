# Engine Room

You are the chief engineer of a starship. Keep the reactor's power flowing to Shields, Weapons, Life support, Engines and Repair until the jump drive is ready.

Open `index.html` in a browser to play. No build step.

- Walk between consoles (WASD/arrows or click) and set each system's power (Q/E, R to match the load).
- Too much power for a few seconds trips that system's breaker; reset it at the breaker panel.
- Too little power damages the ship.
- Eject spent fuel rods and coolant, drop them in the disposal chute, and load fresh ones from the racks.
- Alerts start as unknown contacts on long-range sensors, then get identified with a countdown, so there is time to plan.
- Each shift has a shape: a calm first minute, routine alerts, a hush before an enemy fleet attacks in three waves (spotted long before it arrives), a breather, then the jump drive spool, when the engines need extra power and the drive only charges as fast as they get it.
- Alerts can damage a shield emitter, the turret or a thruster (only 65% of that system's power gets through). The part comes down the cargo lift. Carry it to the repair bay, which takes a fixed 12 MW of reactor output while it works, then send it back up the lift.

## Sound
Everything is synthesized with Web Audio. Ambient sound follows the ship: the reactor hum tracks load, vents follow life support, a buzz warns of a breaker about to trip, welding crackles in the repair bay, and the jump drive spools up over the last 45 seconds. Sonar pings mark unknown contacts, and a klaxon sounds when the hull is below 40%.

## Screen
Split screen: the engine room in a 3/4 view on the left, and an external camera of the ship on the right. The ship view shows what your power choices do: shield bubble strength, turret fire, engine flame, cabin lights, hull scorch marks, repair drones, and the threats from each bridge alert (fighters, asteroids, torpedoes, solar flares, boarding drones, gravity wells, hull breaches).
