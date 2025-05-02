# FogCamera

**Namespace:** `Torappu.Rendering`


## Fields

- `FogProfile _fogProfile`

- `HighlightTileProfile _tileProfile`

- `Camera m_camera`

- `RenderTexture m_renderTexture`

- `MaterialPropertyBlock m_materialPropertyBlock`


## Properties

- `FogProfile fogProfile`


## Methods

- `FogProfile get_fogProfile()`

- `Void Awake()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class FogCamera : MonoBehaviour
{
	private MeshRenderer[] _fogRenderers; // 0x18
	private FogProfile _fogProfile; // 0x20
	private HighlightTileProfile _tileProfile; // 0x28
	private Camera m_camera; // 0x30
	private RenderTexture m_renderTexture; // 0x38
	private MaterialPropertyBlock m_materialPropertyBlock; // 0x40
	private const String RT_NAME_FOG; // 0x0
	private const String SHADER_RT; // 0x0

	public FogProfile fogProfile { get; }

	// RVA: 0x3f06214 VA: 0x759651e214
	public FogProfile get_fogProfile() { }
	// RVA: 0x3f0621c VA: 0x759651e21c
	private Void Awake() { }
	// RVA: 0x3f06458 VA: 0x759651e458
	private Void OnDestroy() { }
	// RVA: 0x3f064d8 VA: 0x759651e4d8
	public Void .ctor() { }
}
```