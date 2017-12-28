General Info                    |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Scripting                       |1:C# / UnityScript              |1:C# / C++ / GDScript           |0.75:Lua / Angel / C++          |0.75:Lua / C# (WIP) / C++       |1:C# / C++                      |Check UrhoSharp and Atomic for extra Urho bindings.
Platforms                       |1:Win/Mac/Lin/iOS/And/Web       |1:Win/Mac/Lin/iOS/And           |1:Win/Mac/Lin/iOS/And/Web/Rpi   |0.8:Win                         |0.9:Win/Lin                     |Consoles Not included because of legal limitations for opensource projects.
Performance                     |Good:0.6                        |Fair:0.4                        |Very Good:0.8                   |Superb:1                        |Superb:1                        |This is an arbitrary but somewhat educated guess.
Source Access                   |0                               |1                               |1                               |1                               |1                               |
Permissive                      |0                               |1                               |1                               |1                               |1:pay what you want             |
3rd Party Assets                |★★★★★                       |★★★                          |★                               |★                              |★                              |Game Services, Social Media, Billing Services, etc.
Production-ready                |1                               |0.75:3.0 not quite              |0.75:for experienced devs       |0.75:for experienced devs       |0.25:not yet                    |

Documentation                   |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-                           |-|-|-|-
API Docs                        |1                               |1                               |1                               |0                               |1                               |Official
API Snippets                    |1                               |0                               |0                               |0                               |0                               |Official
Manuals                         |1                               |0                               |0.4:Old wiki, forums            |0                               |0                               |Official
Tutorials                       |1                               |0                               |0                               |0                               |0                               |Official
Video Tutorials                 |1                               |0                               |0                               |0.4:A few                       |0                               |Official
Community Docs/Tuts             |1                               |0.4:A few                       |0                               |0                               |0                               |
Commercial Material             |1                               |0                               |0                               |0                               |0                               |Books. paid courses, etc

Terrain                         |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Terrain System                  |1                               |0:WIP                           |1                               |1                               |1                               |
Geomipmapping                   |1                               |                                |1                               |1                               |1                               |
Foliage system                  |1                               |0                               |0                               |1                               |0                               |
Max terrain resolution          |                                |                                |                                |Unlimited                       |                                |(single)
Tileable Terrains               |1                               |                                |0                               |0                               |0                               |(adjacent awareness)
Terrain splines                 |0                               |0                               |0                               |0                               |0                               |roads/rivers/etc
Voxel-based (/alternatively)    |0                               |0                               |0                               |0                               |0                               |

Scripting                       |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Octree Queries                  |0                               |                                |1                               |0                               |1                               |
Profiling                       |1                               |0                               |0                               |1                               |0                               |

3D Physics                      |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Engine                          |0.8:PhysX (very limited)        |0.8:Own/Bullet                  |0.8:Bullet                      |1:PhysX / Bullet(WIP)           |1:PhysX                         |PhysX is objectively the best physics engine to date both in sim quality and performance (check PEEL), but it's proprietary. Unity is very limited in the sense that you can't access most of the API and a ton of stuff is neglected for example articulations and origin shifting.
Speculative CD                  |1                               |0/0(WIP)                        |1                               |1                               |1                               |
Multi-threaded                  |0?                              |0                               |0                               |1                               |1                               |
Async Scene                     |0                               |0                               |0                               |0                               |0                               |
Cloth                           |1                               |                                |                                |                                |                                |
Particle collision              |1                               |                                |                                |                                |                                |

APIs                            |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Minimum GL                      |v2.0:1                          |v3.0:0.8                        |v2.1:1                          |v2.0:1                          |v4.4:0.5                        |
Minimum DX                      |v10/11:1                        |0                               |v9.0c:1                         |v9.0c:1                         |v11:0.9                         |
Vulkan Support                  |1                               |0                               |0                               |0:uses bgfx                     |1                               |
DX12 Support                    |1                               |0                               |0                               |1                               |                                |
Shader Language                 |Cg / HLSL:1                     |GLSL subset:1                   |GLSL+HLSL:1                     |GLSL-based:1                    |HLSL-based:1                    |Banshee supports subroutines in either GLSL or HLSL

Rendering                       |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Texture Arrays                  |1:No pipeline                   |0                               |1:XML                           |1:No pipeline                   |0                               |
Runtime GI - Precomputed        |1 (Enlighten(SH)/own)           |1 - VXGI                        |0                               |0                               |0                               |
PBR                             |1                               |1                               |1                               |1                               |1                               |
IBL                             |1                               |1                               |1                               |1                               |1                               |
Dynamic Batching                |1 (800 vert attrib)             |0                               |0                               |0                               |0                               |This is somewhat important for mobile games
Auto Instancing                 |1                               |0                               |1                               |1                               |1                               |
Realtime Reflection Probes      |1                               |1                               |1                               |0                               |1                               |
Soft Shadows                    |1                               |1                               |1                               |1                               |0 (WIP)                         |
LOD System                      |1                               |0.25:terrible                   |1                               |1                               |1                               |
Post Processing                 |1                               |1                               |1                               |1                               |1                               |Remove?
Realtime IBL Probes             |0                               |0                               |0                               |0                               |0                               |
SS Reflection                   |0                               |0                               |0                               |0                               |1                               |Screen-Space
MSAA                            |1                               |0                               |1                               |0                               |1                               |
TXAA                            |0                               |0                               |0                               |0                               |0                               |
VR Support                      |1                               |0                               |0                               |0                               |0                               |
GPU Profiling                   |0                               |0                               |0                               |0                               |1                               |
Frame Debugging                 |1                               |0                               |0                               |0                               |0                               |
Debug Drawing                   |1                               |1                               |1                               |1                               |1                               |Remove this?
Occlusion Culling               |1                               |                                |1                               |1                               |0                               |
Particles                       |1                               |1                               |1                               |1                               |1                               |Remove this?
Billboards                      |1                               |1                               |1                               |1                               |0                               |
Impostors                       |0                               |0                               |0                               |0                               |0                               |
Deferred decals                 |0 (WIP?)                        |1                               |1                               |1                               |0                               |
Mesh decals                     |0                               |0                               |1                               |0                               |0                               |
Skinned Decals                  |0                               |0                               |1                               |0                               |0                               |
Atmospheric scattering          |1                               |0                               |0                               |1                               |0                               |
Height-based fog                |1                               |                                |                                |1                               |1                               |
Skybox                          |1                               |1                               |1                               |1                               |1                               |
Fur                             |0                               |0                               |0                               |1                               |0                               |
Cascaded shadows                |1                               |1                               |1                               |1                               |1                               |
HDR                             |1                               |1                               |1                               |1                               |1                               |
Tessellation                    |1                               |0                               |                                |1                               |                                |
Static lightmaps                |1                               |1                               |0                               |1                               |0                               |
Line/trail renderer             |1                               |0                               |0                               |1                               |0                               |split line and trail? trail is just a line+some scripting
Spotlight texture/cookie        |                                |                                |                                |                                |                                |add note for ies support
Point light texture             |                                |                                |                                |                                |                                |
3D space text                   |                                |                                |                                |                                |                                |
SDF Text Rendering              |1:TextMeshPro                   |                                |1                               |                                |                                |
Static batching                 |1                               |                                |                                |                                |                                |

Rendering - Post processing     |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Depth of Field                  |1                               |1                               |0                               |1                               |                                |
Tonemapping                     |1                               |1                               |0                               |1                               |1                               |
Bloom                           |1                               |1                               |0                               |1                               |                                |
Godrays                         |                                |                                |0                               |1                               |                                |
SSAO                            |1                               |1                               |                                |1                               |1                               |
FXAA                            |1                               |1                               |                                |1                               |1                               |

2D                              |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
2D support                      |1                               |1                               |1                               |0                               |0:Roadmap                       |
Sprites                         |1                               |1                               |1                               |0                               |0                               |
Sprite packing                  |1                               |                                |                                |                                |                                |
Physics                         |1:Box2D                         |1:Own                           |1:Box2D                         |0                               |0                               |
Audio                           |1                               |1                               |1                               |0                               |1                               |
Particles                       |0                               |1                               |1                               |0                               |0                               |3D particles are usable for 2D in most cases
Pixel Perfect Rendering         |0                               |0                               |0                               |0                               |0                               |
Pixel Units                     |0                               |1                               |0                               |0                               |0                               |
2D Skeletal Anim                |1                               |1                               |0                               |0                               |0                               |

Animation                       |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
GPU Skinning                    |1                               |                                |1                               |1                               |                                |
IK                              |0:only humanoid                 |0                               |1                               |1                               |1                               |
Huma0id-aware                   |1                               |0                               |0                               |0                               |0                               |
State machines                  |1                               |1                               |0                               |1                               |0                               |
Linear Blend                    |1                               |1                               |1                               |1                               |1                               |
Radial Blend                    |1                               |0                               |0                               |0                               |0                               |AKA Freeform
Blend Shapes                    |1                               |1                               |1                               |0                               |1                               |
Skeletal                        |1                               |1                               |1                               |1                               |1                               |
Generic Tweening                |0                               |0                               |1:Animation Properties          |0                               |1                               |
Anim Events                     |1                               |1                               |1                               |1                               |1                               |
Anim Curves                     |1                               |0                               |0                               |0                               |0                               |
Root Bone Movement              |1                               |0                               |0                               |1                               |1                               |
Blend Trees                     |1                               |1                               |0                               |1                               |0                               |

Input                           |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
GamePad                         |1                               |1                               |1                               |1                               |1                               |
HL Abstraction                  |1 (terrible)                    |0                               |0                               |0                               |1                               |

Audio                           |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Streaming                       |1                               |0                               |0                               |0                               |1                               |
Effects                         |                                |                                |                                |                                |                                |

Audio - Effects                 |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Echo                            |                                |                                |0                               |1                               |1                               |
Doppler                         |                                |                                |0                               |                                |1                               |
Reverb                          |1                               |                                |                                |                                |1                               |
Space-aware reverb              |                                |                                |0                               |                                |0                               |

Network                         |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Scene Replication               |1                               |1                               |1                               |0                               |0                               |
RPC                             |                                |                                |                                |                                |                                |
HTTP requests                   |                                |                                |1                               |                                |                                |irrelevant?
Voice over network              |0                               |0                               |0                               |0                               |0                               |

AI                              |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Pathfinding                     |1:Recast/Detour                 |1:Own                           |1:Recast/Detour                 |1:Recast/Detour                 |0                               |
Runtime Graph Generation        |1 (WIP)                         |0                               |1                               |1                               |N/A                             |
State Machine                   |0                               |0                               |0                               |0                               |0                               |
Crowd Simulation                |                                |0                               |1                               |                                |                                |

Asset Pipeline                  |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
FBX                             |1:AD SDK                        |0.5:Bad support                 |0.5:Bad support                 |0.9:OpenFBX                     |1:AD SDK                        |
GLTF                            |                                |                                |                                |                                |                                |
PSD                             |                                |                                |                                |                                |                                |
Images                          |                                |                                |                                |                                |                                |
Fonts                           |                                |                                |                                |                                |                                |
Meshes                          |                                |                                |                                |                                |                                |

UI                              |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
In-Game Restrained              |1                               |1                               |1                               |1 (Turbobadger)                 |1                               |
In-Game Immediate               |1                               |0                               |0                               |1 (Dear Imgui)                  |0                               |

Editor                          |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Drag and Drop Prefabs           |                                |                                |                                |                                |                                |
Nested Prefabs                  |                                |                                |                                |                                |                                |
Customizable Prefab Previews    |0                               |0                               |0                               |1                               |0                               |
Animation Curves Editor         |1                               |1                               |0                               |0                               |0                               |
Animation State Machines Ed.    |1                               |1                               |0                               |1                               |0                               |
Auto Inspector Variable         |1                               |                                |0                               |1                               |1                               |Variables from scripts exposed in the inspector with minimal or no extra code
Snapping                        |1:Grid/Origin->Surf/Vertex      |0.8:1:Grid/Origin->Surf         |0.8:Grid/Origin->Surf           |1:Grid/Origin->Surf/Vertex      |0.8:Grid/Origin->Surf           |
Visual Shader Editor            |0                               |1                               |0                               |0                               |0                               |
Visual Scripting                |0                               |0:WIP                           |0                               |0                               |0                               |
Visual UI editor                |1                               |1                               |0                               |0                               |0                               |
IDE integration                 |                                |                                |                                |                                |                                |

Others                          |Unityᶠʳᵉᵉ                       |Godot                           |Urho                            |Lumix                           |Banshee                         |NOTES
-|-|-|-|-|-|-
Async Loading                   |1                               |0                               |0 (background loading?)         |                                |1                               |Prefabs/Assets - add one for scenes?
Remote profiling                |                                |                                |                                |                                |                                |
Usable as lib                   |0                               |0                               |1                               |0                               |0                               |