
FEATURE|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Scripting|C# / UnityScript|C# / C++ / GDScript|Lua / Angel / C++|Lua / C# / C++|C# / C++|
Performance|0.6:★★★|0.2:★★|0.8:★★★★|1:★★★★★|1:★★★★★|This is an arbitrary but somewhat educated guess.
Source Access|0|1|1|1|1|
Editor|0.8:★★★★|0.6:★★★|0.2:★|0.4:★★|0.4:★★|
Permissive|0|1|1|1|1:pay what you want|
Platforms|Win / Mac / Lin / iOS / And / Web|Win / Mac / Lin / iOS / And|Win / Mac / Lin / iOS / And / Web / Rpi|Win|Win / Lin|Consoles Not included because of legal limitations for opensource projects.
Documentation|★★★★|★★★|★|★|★★★|This is an arbitrary but somewhat educated guess.
3rd Party Assets|★★★★★|★★★|★|★|★|SteamWorks
Production-ready|1|3.0 0t quite|1 (experienced dev)|1 (experienced dev)|0t yet|

General|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Terrain System|1|0 (WIP)|1|1|1|
LOD System|1|1 (terrible)|1|1|1|

Scripting|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Octree Queries|0||1|0|1|
Profiling|1|0|0|1|0|

3D Physics|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Engine|PhysX (very limited)|Own/Bullet|Bullet|PhysX / Bullet(WIP)|PhysX|PhysX is objectively the best physics engine to date both in sim quality and performance (check PEEL), but it's proprietary. Unity is very limited in the sense that you can't access most of the API and a ton of stuff is neglected for example articulations and origin shifting.
Speculative CD|1|0/0(WIP)|1|1|1|
Multi-threaded|0?|0|0|1|1|
Async Scene|0|0|0|0|0|

APIs|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Minimum GL|2.0|3.0|2.1|2.0|4.4|
Minimum DX|10/11|N/A|9.0c|9.0c|11|
Vulkan Support|1|0|0|0 (bgfx)|1|
DX12 Support|1|0|0|1||
Shader Language|Cg / HLSL|GLSL subset|GLSL+HLSL|GLSL-based|HLSL-based|Banshee supports subroutines in either GLSL or HLSL

Rendering|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
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

2D|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
2D support|1|1|1|0|0 (Roadmap)|
Sprites|1|1|1|N/A|N/A|
Physics|Box2D|Own|Box2D|N/A|N/A|
Audio|1|1|1|0|1|
Particles|0|1|1|0|0|3D particles are usable for 2D in most cases

Animation|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
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

Input|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
GamePad|1|1|1|1|1|
HL Abstraction|1 (terrible)|0|0|0|1|

3D Audio|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Streaming|1|0|0|0|1|
Effects||||||

Network|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Scene Replication|1|1|1|0|0|
RPC||||||
HTTP requests|||1|||irrelevant?

AI|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Pathfinding|Recast/Detour|Own|Recast/Detour|Recast/Detour|0|
Runtime Graph Generation|1 (WIP)|0|1|1|N/A|
State Machine|0|0|0|0|0|
Crowd Simulation||0|1|||
Asset Pipeline|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
FBX|1 (AD SDK)|Bad|Bad|1 (OpenFBX)|1 (AD SDK)|
GLTF|todo|todo|todo|todo|todo|
PSD||||||
Images||||||
Fonts||||||
Meshes||||||

UI|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
In-Game Restrained|1|1|1|1 (Turbobadger)|1|
In-Game Immediate|1|0|0|1 (Dear Imgui)|0|


|Unity (Free)|Godot|Urho|Lumix|Banshee|0TES
||||||
Universal Features:||||||
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

