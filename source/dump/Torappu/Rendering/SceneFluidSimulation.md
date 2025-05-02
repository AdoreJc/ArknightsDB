# SceneFluidSimulation

**Namespace:** `Torappu.Rendering`


## Fields

- `Shader simulation`

- `RenderTexture velocityRT`

- `RenderTexture colorRT`

- `RenderTexture velocityTempRT`

- `RenderTexture colorTempRT`

- `Material simulationMat`

- `Single fluidSpeed`

- `Single fluidVorticity`

- `Int32 rtSize`

- `Texture flowMap`

- `Single flowMapIntensity`

- `Boolean isUpdate`

- `Boolean pinpong`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateFluid()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class SceneFluidSimulation : MonoBehaviour
{
	public Shader simulation; // 0x18
	private RenderTexture velocityRT; // 0x20
	private RenderTexture colorRT; // 0x28
	private RenderTexture velocityTempRT; // 0x30
	private RenderTexture colorTempRT; // 0x38
	private Material simulationMat; // 0x40
	public Single fluidSpeed; // 0x48
	public Single fluidVorticity; // 0x4c
	public Int32 rtSize; // 0x50
	public Texture flowMap; // 0x58
	public Single flowMapIntensity; // 0x60
	public Boolean isUpdate; // 0x64
	private Boolean pinpong; // 0x65
	public List`1 emitterList; // 0x68
	private Vector4[] positionsArray; // 0x70
	private Single[] rangesArray; // 0x78
	private Single[] forceIntensityArray; // 0x80
	private Vector4[] forceDirectionArray; // 0x88
	private Vector4[] colorArray; // 0x90
	private static readonly Int32 fluidPosition; // 0x0
	private static readonly Int32 fluidRange; // 0x4
	private static readonly Int32 forceIntensity; // 0x8
	private static readonly Int32 forceDirection; // 0xc
	private static readonly Int32 fluidCol; // 0x10
	private static readonly Int32 emitterCount; // 0x14
	private static readonly Int32 _FluidSpeed; // 0x18
	private static readonly Int32 _FluidFlowMap; // 0x1c
	private static readonly Int32 _FluidFlowMapIntensity; // 0x20
	private static readonly Int32 _FluidVorticity; // 0x24


	// RVA: 0x3f054e4 VA: 0x759651d4e4
	private Void Start() { }
	// RVA: 0x3f05b2c VA: 0x759651db2c
	private Void OnDestroy() { }
	// RVA: 0x3f05794 VA: 0x759651d794
	private Void UpdateFluid() { }
	// RVA: 0x3f05cb0 VA: 0x759651dcb0
	private Void Update() { }
	// RVA: 0x3f05ebc VA: 0x759651debc
	public Void .ctor() { }
	// RVA: 0x3f05fc8 VA: 0x759651dfc8
	private static Void .cctor() { }
}
```