# Levels

**Namespace:** `Colorful`


## Fields

- `ColorMode Mode`

- `Vector3 InputL`

- `Vector3 InputR`

- `Vector3 InputG`

- `Vector3 InputB`

- `Vector2 OutputL`

- `Vector2 OutputR`

- `Vector2 OutputG`

- `Vector2 OutputB`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Levels : BaseEffect
{
	public ColorMode Mode; // 0x28
	public Vector3 InputL; // 0x2c
	public Vector3 InputR; // 0x38
	public Vector3 InputG; // 0x44
	public Vector3 InputB; // 0x50
	public Vector2 OutputL; // 0x5c
	public Vector2 OutputR; // 0x64
	public Vector2 OutputG; // 0x6c
	public Vector2 OutputB; // 0x74


	// RVA: 0x34ecbdc VA: 0x7595b04bdc
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34eced8 VA: 0x7595b04ed8
	protected override String GetShaderName() { }
	// RVA: 0x34ecf18 VA: 0x7595b04f18
	public Void .ctor() { }
}
```