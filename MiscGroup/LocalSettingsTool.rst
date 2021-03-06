.. |Icon_Misc_LocalSettings| image:: /images/Icon_Misc_LocalSettings.png
   :scale: 100 %

################################################
Local Settings Tool |Icon_Misc_LocalSettings|
################################################

Sets up local variables.

Properties
-------------
Backface
 backfaces on/off

Lightmap Static
 Changes the lighting way to lightmap. This variable is interlocked with ``Lightmap Static`` in ``Lighting`` window.

Invisible In PlayMode.
 If on, a mesh is invisible in Play Mode and it is displayed in transparent color in Editor mode. This will be very useful if you want to use UModeler mesh as a trigger or a collider.

.. _recalculate-tangents: 

Recalculate Tangents
 If this is on, tangent vectors will be calculated every time UModeler mesh changes. If the materials in UModeler have normal textures, this should be on.
 
Don't Save In Build
 If this is on, UModeler component isn't included in Build. If you want to edit a mesh using UModeler at runtime, it needs to be on when the project is built.
 Usually this property is on because most meshes are just for rendering at runtime.
 
Generate UV2 channel for Lightmap
 Generate UVs for lightmaps. From 2.6.9 UVs for lightmap aren't created automatically. If you want to generate lightmap UVs of all UModeler meshs in a scene, click on ``Tools > UModeler > Refresh All``. 

.. figure:: /images/LocalSettings.jpg
   :scale: 100 %