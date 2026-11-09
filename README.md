# MG5
## Devlog
1. I think it definitely makes more sense to use a NavMesh when making movement for NPCs or in the case of this minigame click movement whereas something more movement intensive like a 3D platformer or multiplayer game would benefit from physics based movement. I think a good example of NavMesh would be something like League of Legends where complex movement isn't as important as traversing the map and fighting the simple enemy AI in the jungle. Deadlock, on the other hand, is a game where the movement and verticality are front and center with features like wall jumping and dashing that NavMesh could struggle to keep up with.
2. The call to Vector3.Distance is being used to measure the distance between the bird and the player which is then checked against the interact distance to determine if the bird runs away or not. Since I have (int i = 0; i < 4; i++) in my header and I have four birds in my array, all birds will run from the player.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
