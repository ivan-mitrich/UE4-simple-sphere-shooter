# UE4-simple-sphere-shooter
This is a test project with no explicit win condition.

## Gameplay
Player shoots the spheres randomly spawned in certain volume. 

## Default game rules:
- Spheres are spawned in waves.
- Initial spawned volume radius is 2000. 
- Initial spawned spheres amount is 15.
- When player shot 10 spheres located at the distance 1500 from spawn point, new sphere wave is spawned and the rest of the old spheres are destroyed.
- This new wave has new volume radius = old volume radius * 1.05, and new spawned spheres amount = old spheres amount * 1.1.
- After creation all new spheres gradually change their size from big to small with certain step.


