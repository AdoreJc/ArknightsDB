# DynamicHeightFogEffect

**Namespace:** `Torappu.Rendering`


## Fields

- `Transform WaterSurface`

- `Single extrude`

- `Single range`

- `Color fogColor`

- `Texture2D fogNoise`

- `Vector2 fogNoiseScale`

- `Single fogSpeed`

- `Vector4 m_heightFogParam`

- `Vector4 m_heightFogNoiseST`

- `Vector4 m_colorgradingParam`

- `Single tempHeight`


## Methods

- `Void Start()`

- `Void Update()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class DynamicHeightFogEffect : MonoBehaviour
{
	public Transform WaterSurface; // 0x18
	public Single extrude; // 0x20
	public Single range; // 0x24
	public Color fogColor; // 0x28
	public Texture2D fogNoise; // 0x38
	public Vector2 fogNoiseScale; // 0x40
	public Single fogSpeed; // 0x48
	private Vector4 m_heightFogParam; // 0x4c
	private Vector4 m_heightFogNoiseST; // 0x5c
	private Vector4 m_colorgradingParam; // 0x6c
	private Single tempHeight; // 0x7c


	// RVA: 0x3f09670 VA: 0x7596521670
	private Void Start() { }
	// RVA: 0x3f096d4 VA: 0x75965216d4
	private Void Update() { }
	// RVA: 0x3f09894 VA: 0x7596521894
	private Void OnDestroy() { }
	// RVA: 0x3f098d8 VA: 0x75965218d8
	public Void .ctor() { }
}
```