# FastVignette

**Namespace:** `Colorful`


## Fields

- `ColorMode Mode`

- `Color Color`

- `Vector2 Center`

- `Single Sharpness`

- `Single Darkness`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class FastVignette : BaseEffect
{
	public ColorMode Mode; // 0x28
	public Color Color; // 0x2c
	public Vector2 Center; // 0x3c
	public Single Sharpness; // 0x44
	public Single Darkness; // 0x48


	// RVA: 0x34ea2d8 VA: 0x7595b022d8
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ea3e4 VA: 0x7595b023e4
	protected override String GetShaderName() { }
	// RVA: 0x34ea424 VA: 0x7595b02424
	public Void .ctor() { }
}
```