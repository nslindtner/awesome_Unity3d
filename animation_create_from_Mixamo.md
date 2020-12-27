#In Maximo
- Find character in maximo
- Find animation
- Download fbx for unity with skin

#In Unity (asset folder)
- Drag fbx file to Unity
- Use inspector on asset (imported file). NOT ON SCENE (if you have dragged it into the scene)
- Rig: Select humanoid
- Extract: Texture
- Extract: Materials
- Find animation and rename it (probally named mixamo.com now) - (note: if you exported it for unity, the file should contain animation name after @).
- Apply

#IN Unity (scene)
- Drag asset into scene
- Select char (nested under object).
- Find material (under skinned meshed renderer) - (probally Materials - element 0)
- Draw extracted diffuse -> albeite on materials
- Draw extracted normals -> normals map on material

- Add Animator to main character object
- create animator controller (script)
- Attach script to added animator script
- Draw animation into






# NOTE: If you want to get animation from fbx file. Simply make the import apply - then get to the animation (within the exported) and click CTRD-D. This will copy the animation into a .anim file. Containing the animation.
