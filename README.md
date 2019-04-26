# Surface Snapping Bug

Here is short video https://youtu.be/yLXJuaw0pkk

1. Place BP Actor (NewBlueprint) from content folder on the scene.
2. Switch Surface Snapping on.
3. Select Arrow component inside BP (I think it may be any component).
4. Try to move Arrow by dragging any 1 axis - you chance Arrow location.
5. Try to move Arrow bu dragging square between axis, or root of all 3 axis (free move) you end up changing location of DefaultSceneRoot component, not Arrow.
6. All moving works as expected if Surface Snapping is off.
