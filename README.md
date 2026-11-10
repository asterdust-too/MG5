# MG5
## Devlog
### Prompt Answers
1. It is more advantageous to script a character's movement when you have a lot of ground to cover and don't need anything to hit anything else. In other words, a game that needs pathfinding should use NavMesh. In a large open-world game that has enemies that rush toward you before attacking, or say, a superpower that repels everything, you can use a NavMesh to make all of these things happen. For physics, you can use it for things that need collision to function. A good example is the soccer game we coded, or something similar like Rocket League where you bounce a ball around. Any physics-based game is likely going to use physics for its movement rather than NavMesh because it can take advantage of all the jank that comes with physics.
2. The loop is counting all of the different birds in the scene, which after it is fixed, should encompass all of them. Vector3.Distance calculates the distance between the player and the birds, and keeps that difference as the player moves. As a result, the player pushes the birds away as the move forward until the bird runs out of space to move, in which case the player could reach it.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
