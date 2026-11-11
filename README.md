# MG5
## Devlog
1. A NavMesh system works best for automating movement on terrain that isn’t completely flat. You could also guide a character’s movement towards an object or destination using SetDestination(). In Deadlock a soul urn moves between lanes on a multiplane map. This is the ideal scenario for a NavMesh due to the variables in position and the complexity of the movement. In Super Mario Bros. a Goomba travels in straight lines along a 2d plane. Scripting is better suited to this scenario due to the simplicity of the movement.

2. The call to Vector3.Distance is being used to determine if the distance between the bird and the player is less than or equal to the _interactDistance variable for each bird in the bird array. If this statement is true the birds in the _birds array that are too close to the player will run away from the player's position. 


## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
