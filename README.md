# mapbox_3dtiles_samples

## Demo's  MapBox GL JS v3

In MapBox GL JS v3 beta functionality 3D model support is added to the standard library.

Some demo's with it:

1] Load glTF model

https://bertt.github.io/mapbox_3dtiles_samples/samples/standard/3dmodel/

![image](https://github.com/bertt/mapbox_3dtiles_samples/assets/538812/a391877c-a805-485c-af86-cb9db168c17a)


2] 170K trees

https://bertt.github.io/mapbox_3dtiles_samples/samples/standard/trees/

![image](https://github.com/bertt/mapbox_3dtiles_samples/assets/538812/04ebd034-cfa3-4f3f-9049-f51b909c4694)

3] Batched models

https://bertt.github.io/mapbox_3dtiles_samples/samples/standard/b3dm_working/

![image](https://github.com/bertt/mapbox_3dtiles_samples/assets/538812/5a4d2ca9-a879-4c02-b2ea-7d004520daf6)

4] Custom GLB at Dam square

https://bertt.github.io/mapbox_3dtiles_samples/samples/standard/dam_square/

![Screenshot 2024-02-27 103820](https://github.com/bertt/mapbox_3dtiles_samples/assets/538812/2cdfbcf3-b963-4b22-be6d-42147870b81f)

5] Delaware buildings

https://bertt.github.io/mapbox_3dtiles_samples/samples/standard/delaware/

![image](https://github.com/bertt/mapbox_3dtiles_samples/assets/538812/ac464c87-36d8-4220-a483-ca26e0d50df6)

6] Tienhoven Dutch 3D bag

https://bertt.github.io/mapbox_3dtiles_samples/samples/standard/tienhoven/

![image](https://github.com/bertt/mapbox_3dtiles_samples/assets/538812/7440b27a-c00f-4ff4-9879-e2844b6aca9c)

7] Tiles on multiple levels 15,16,17

https://bertt.github.io/mapbox_3dtiles_samples/samples/standard/multiple_levels

![Screenshot 2024-03-11 144053](https://github.com/bertt/mapbox_3dtiles_samples/assets/538812/c67fd415-d83b-4d2d-b668-58f57bc89dec)


## Classic Demo's using Mapbox3DTiles.js

Repository with some samples of 3D Tiles in a MapBox viewer.

In these demo https://github.com/Geodan/mapbox-3dtiles is used for handling the 3D tiles.

1] LOD's demo

Demo MapBox GL JS + 3D Tiles Level of detail. Different glTF models are visualized for far/nearby.

https://bertt.github.io/mapbox_3dtiles_samples/samples/lods

<img src = "lods.gif">

2] Demo MapBox GL JS + referencing external tilesets 

https://bertt.github.io/mapbox_3dtiles_samples/samples/external

Two tilesets are displayed in 1 layer using 'external tileset' technique.

<img src = "external_tilesets.png">

3] Demo MapBox GL JS + 3D tiles with glTF SpecularGlossiness shader

https://bertt.github.io/mapbox_3dtiles_samples/samples/shaders

<img src = "specular_glossiness.png">

4] Demo MapBox GL JS + client side lighting examples (ambient, hemisphere, directional)

https://bertt.github.io/mapbox_3dtiles_samples/samples/lighting

<img src = "lighting.png">

5] Demo MapBox GL JS + placement b3dm's (house models converted from IFC)

https://bertt.github.io/mapbox_3dtiles_samples/samples/b3dm

<img src = "b3dm.png">

6] Demo MapBox GL JS + composite tiles (cmpt)

https://bertt.github.io/mapbox_3dtiles_samples/samples/composite

<img src = "composite.png">

Composite tiles contains two instanced models.

7] Demo MapBox GL JS + instanced 3D Tiles (i3dm)

https://bertt.github.io/mapbox_3dtiles_samples/samples/instanced

<img src = "instanced.png">

Instanced models with random scale/rotation and batch info

------------------------------------------------------------------------

Not working demo's:

- Demo MapBox GL JS + 3D tiles with glTF animations

Note: Visualizing glTF animations is not working yet :-(

https://bertt.github.io/mapbox_3dtiles_samples/samples/animations

- Demo MapBox GL JS + Draco compressed 3D Tiles 

Note: Visualizing 3D Tiles with Draco compression is not working yet :-(

https://bertt.github.io/mapbox_3dtiles_samples/samples/draco.html

