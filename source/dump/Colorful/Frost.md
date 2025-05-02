# Frost

**Namespace:** `Colorful`


## Fields

- `Single Scale`

- `Single Sharpness`

- `Single Darkness`

- `Boolean EnableVignette`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Frost : BaseEffect
{
	public Single Scale; // 0x28
	public Single Sharpness; // 0x2c
	public Single Darkness; // 0x30
	public Boolean EnableVignette; // 0x34


	// RVA: 0x34ea44c VA: 0x7595b0244c
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ea5c0 VA: 0x7595b025c0
	protected override String GetShaderName() { }
	// RVA: 0x34ea600 VA: 0x7595b02600
	public Void .ctor() { }
}
```