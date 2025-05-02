# ShadowCamera

**Namespace:** `Torappu.Rendering`


## Fields

- `HGShadowProfile _shadowProfile`

- `Boolean _isUpdating`

- `Camera _shadowCamera`

- `RenderTexture _renderTarget`

- `Matrix4x4 posToUV`


## Properties

- `Boolean ProfileLegal`


## Methods

- `Boolean get_ProfileLegal()`

- `Void Awake()`

- `Void Update()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class ShadowCamera : MonoBehaviour
{
	public HGShadowProfile _shadowProfile; // 0x18
	private Boolean _isUpdating; // 0x20
	private Camera _shadowCamera; // 0x28
	private RenderTexture _renderTarget; // 0x30
	private Matrix4x4 posToUV; // 0x38
	private const String RT_NAME_SHADOW; // 0x0

	private Boolean ProfileLegal { get; }

	// RVA: 0x3f08760 VA: 0x7596520760
	private Boolean get_ProfileLegal() { }
	// RVA: 0x3f08864 VA: 0x7596520864
	private Void Awake() { }
	// RVA: 0x3f08da8 VA: 0x7596520da8
	public Void Update() { }
	// RVA: 0x3f08f68 VA: 0x7596520f68
	private Void OnDestroy() { }
	// RVA: 0x3f090bc VA: 0x75965210bc
	public Void .ctor() { }
}
```