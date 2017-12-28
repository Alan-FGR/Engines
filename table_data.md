
FEATURE|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Scripting|1:C# / UnityScript|1:C# / C++ / GDScript|0.75:Lua / Angel / C++|0.75:Lua / C# (WIP) / C++|1:C# / C++|
Performance|★★★|★★|★★★★|★★★★★|★★★★★|This is an arbitrary but somewhat educated guess.
Source Access|0|1|1|1|1|
Editor|★★★★|★★★|★|★★|★★|
Permissive|0|1|1|1|1:pay what you want|
Platforms|1:Win / Mac / Lin / iOS / And / Web|1:Win / Mac / Lin / iOS / And|1:Win / Mac / Lin / iOS / And / Web / Rpi|0.8:Win|0.9:Win / Lin|Consoles Not included because of legal limitations for opensource projects.
Documentation|★★★★|★★★|★|★|★★★|This is an arbitrary but somewhat educated guess.
3rd Party Assets|★★★★★|★★★|★|★|★|SteamWorks
Production-ready|1|0.5:3.0 not quite|0.75:(experienced dev)|0.75:(experienced dev)|0:not yet|

General|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Terrain System|1|0 (WIP)|1|1|1|
LOD System|1|1 (terrible)|1|1|1|

Scripting|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Octree Queries|0||1|0|1|
Profiling|1|0|0|1|0|

3D Physics|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Engine|PhysX (very limited)|Own/Bullet|Bullet|PhysX / Bullet(WIP)|PhysX|PhysX is objectively the best physics engine to date both in sim quality and performance (check PEEL), but it's proprietary. Unity is very limited in the sense that you can't access most of the API and a ton of stuff is neglected for example articulations and origin shifting.
Speculative CD|1|0/0(WIP)|1|1|1|
Multi-threaded|0?|0|0|1|1|
Async Scene|0|0|0|0|0|

APIs|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Minimum GL|v2.0:1|v3.0:0.8|v2.1:1|v2.0:1|v4.4:0.5|
Minimum DX|v10/11:1|0|v9.0c:1|v9.0c:1|v11:0.9|
Vulkan Support|1|0|0|0:uses bgfx|1|
DX12 Support|1|0|0|1||
Shader Language|Cg / HLSL:1|GLSL subset:1|GLSL+HLSL:1|GLSL-based:1|HLSL-based:1|Banshee supports subroutines in either GLSL or HLSL

Rendering|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Texture Arrays|1 (0 pipeline)|0|1 (XML)|1 (0 pipeline)|0|
Runtime GI - Precomputed|1 (Enlighten(SH)/own)|1 - VXGI|0|0|0|
PBR|1|1|1|1|1|
IBL|1|1|1|1|1|
Dynamic Batching|1 (800 vert attrib)|0|0|0|0|This is somewhat important for mobile games
Auto Instancing|1|0|1|1|1|
Realtime Reflection Probes|1|1|1|0|1|
Soft Shadows|1|1|1|1|0 (WIP)|
Post Processing|1|1|1|1|1|Remove?
Realtime IBL Probes|0|0|0|0|0|
SS Reflection|0|0|0|0|1|Screen-Space
MSAA|1|0|1|0|1|
TXAA|0|0|0|0|0|
VR Support|1|0|0|0|0|
GPU Profiling|0|0|0|0|1|
Debugging|1 (incl. RenderDoc support)|0|0|1|1|
Debug Drawing|1|1|1|1|1|Remove this?
Occlusion Culling|1||1|1|0|
Particles|1|1|1|1|1|Remove this?
Skinned Decals|0|0|1|0|0|

2D|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
2D support|1|1|1|0|0 (Roadmap)|
Sprites|1|1|1|0|0|
Physics|1:Box2D|1:Own|1:Box2D|0|0|
Audio|1|1|1|0|1|
Particles|0|1|1|0|0|3D particles are usable for 2D in most cases

Animation|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
GPU Skinning|1||1|1||
IK|0 - only huma0id|0|1|1|1|
Huma0id-aware|1|0|0|0|0|
State machines|1|1|0|1|0|
Linear Blend|1|1|1|1|1|
Radial Blend|1|0|0|0|0|AKA Freeform
Blend Shapes|1|1|1|0|1|
Skeletal|1|1|1|1|1|
Generic Tweening|0|0|1 (Animation Property)|0|1|
Anim Events|1|1|1|1|1|
Anim Curves|1|0|0|0|0|
Root Bone Movement|1|0|0|1|1|

Input|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
GamePad|1|1|1|1|1|
HL Abstraction|1 (terrible)|0|0|0|1|

3D Audio|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Streaming|1|0|0|0|1|
Effects||||||

Network|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Scene Replication|1|1|1|0|0|
RPC||||||
HTTP requests|||1|||irrelevant?

AI|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Pathfinding|1:Recast/Detour|1:Own|1:Recast/Detour|1:Recast/Detour|0|
Runtime Graph Generation|1 (WIP)|0|1|1|N/A|
State Machine|0|0|0|0|0|
Crowd Simulation||0|1|||

Asset Pipeline|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
FBX|1:AD SDK|0.5:Bad support|0.5:Bad support|0.9:OpenFBX|1:AD SDK|
GLTF||||||
PSD||||||
Images||||||
Fonts||||||
Meshes||||||

UI|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
In-Game Restrained|1|1|1|1 (Turbobadger)|1|
In-Game Immediate|1|0|0|1 (Dear Imgui)|0|


|Unityᶠʳᵉᵉ|Godot|Urho|Lumix|Banshee|NOTES
-|-|-|-|-|-|-
Visual Shader Editor|0|1|0|0|0|
Pixel Perfect Rendering|0|0|0|0|0|
Pixel Units|0|1|0|0|0|
2D Skeletal Anim|1|1|0|0|0|
Animation Editor|1|1|0|0|0|
Blend Trees|1|1|0|1|0|
||||||
||||1||
HDR|1|1|1|1|1|
Geomipmapping|1||1|1|1|
Max terrain resolution (single)||||Unlimited||
Tileable Terrains (adjacent awareness)|1||0|0|0|
Async Loading|1|0|0 (background loading?)||1|Prefabs/Assets - add one for scenes?
||||||
skybox|1|1|1|1|1|
height-based fog|1|||1|1|
fur|0|0|0|1|0|
atmospheric scattering|1|0|0|1|0|
billboards|1|1|1|1|0|
mesh decals|0|0|1|0|0|
deferred decals|0 (WIP?)|1|1|1|0|
impostors|0|0|0|0|0|
cascaded shadows|1|1|1|1|1|
||||||
||||||
postfx||||||
dof|1|1|0|1||
tonemapping|1|1|0|1|1|
bloom|1|1|0|1||
godrays|||0|1||
ssao|1|1||1|1|
fxaa|1|1||1|1|
||||||
audiofx||||||
echo|||0|1|1|
doppler|||0||1|
reverb|1||||1|
space-aware reverb|||0||0|
static lightmaps|1|1|0|1|0|
tessellation|1|0||1||
line/trail renderer|1|0|0|1|0|split line and trail? trail is just a line+some scripting
voxel terrains|0|0|0|0|0|
voice over network|0|0|0|0|0|
cloth|1|||||
particle collision|1|||||
terrain splines|0|0|0|0|0|roads/rivers/etc
spotlight texture/cookie||||||add 0te for ies support
point light texture||||||
3d text - texture quads||||||
3d text - sdf||||||
texture packing||||||
texture atlasing||||||
static batching||||||
remote profiling (incl mobile)||||||
usable as lib|0|0|1|0|0|
visual scripting?|0|0 (WIP)|0|0|0|
visual ui editor|1|1|0|0|0|
foliage system|1|0|0|1|0|

