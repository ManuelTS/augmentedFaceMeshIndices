# Indicies Source
1.10.0 Sceneform's [canonical_face_mesh.fbx](https://github.com/google-ar/sceneform-android-sdk/blob/master/assets/canonical_face_mesh.fbx) mesh indicies visualized via:

```
blender/3D View/Edit Mode/View/Properties/Mesh Display/
```
and the addon [space_view3d_index_visualiser_bmesh.py](https://developer.blender.org/F11709) installed.

# Usage
In your code, you can use the methods of [AugmentedFace](https://developers.google.com/ar/reference/java/arcore/reference/com/google/ar/core/AugmentedFace) to access the face mesh's:

1. [Vertex (x,y,z) Coordinates](https://developers.google.com/ar/reference/java/arcore/reference/com/google/ar/core/AugmentedFace#getMeshVertices())
1. [Triangle Indices](https://developers.google.com/ar/reference/java/arcore/reference/com/google/ar/core/AugmentedFace#getMeshTriangleIndices())
1. [Texture (u,v) Coordinates](https://developers.google.com/ar/reference/java/arcore/reference/com/google/ar/core/AugmentedFace#getMeshTextureCoordinates())
1. [Normals](https://developers.google.com/ar/reference/java/arcore/reference/com/google/ar/core/AugmentedFace#getMeshNormals())
