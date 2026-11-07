# Engine Room

You are the chief engineer of a starship. Keep the reactor's power flowing to Shields, Weapons, Life support, Engines and Repair until the jump drive is ready.

Open `index.html` in a browser to play. No build step.

- Set each system's power from the power panel, wherever you are on the ship (1–5 picks a system, Q/E adjusts it, R matches the load).
- Walk the deck (WASD/arrows, click, or click a room on the deck map): Engineering opens onto a corridor leading to Storage, the Med bay, the Bridge and Weapons. The Bridge and Med bay run automatically for now; their manual stations are the next updates.
- Take the guns in the Weapons room: the external camera becomes your sight (aim with the mouse or WASD, click or Space to fire). Weapons power sets how fast the turret recharges. Each fighter or drone destroyed lowers that alert's power demand and clearing them ends it early; torpedoes hit the hull unless shot down; from the fleet's second wave the cruiser can be destroyed to end the battle. Unmanned, the turret fires on its own, slowly and with poor aim.
- Too much power for a few seconds trips that system's breaker; reset it at the breaker panel in Engineering.
- Too little power damages the ship.
- Fresh fuel rods and coolant are in Storage. Swap them at the reactor (it re-primes for a few seconds), then take the spent one from the port tray to the disposal chute.
- Alerts start as unknown contacts on long-range sensors, then get identified with a countdown, so there is time to plan.
- Each shift has a shape: a calm first minute, routine alerts, a hush before an enemy fleet attacks in three waves (spotted long before it arrives), a breather, then the jump drive spool, when the engines need extra power and the drive only charges as fast as they get it.
- Alerts can damage a shield emitter, the turret or a thruster (only 65% of that system's power gets through). The part comes down the cargo lift. Carry it to the repair bay, which takes a fixed 12 MW of reactor output while it works, then send it back up the lift.

## Sound
Everything is synthesized with Web Audio. Ambient sound follows the ship: the reactor hum tracks load, vents follow life support, a buzz warns of a breaker about to trip, welding crackles in the repair bay, and the jump drive spools up over the last 45 seconds. Sonar pings mark unknown contacts, and a klaxon sounds when the hull is below 40%.

## Screen
Split screen: the room you are in, in a 3/4 view, on the left, and an external camera of the ship on the right. The ship view shows what your power choices do: shield bubble strength, turret fire, engine flame, cabin lights, hull scorch marks, repair drones, and the threats from each bridge alert (fighters, asteroids, torpedoes, solar flares, boarding drones, gravity wells, hull breaches).
