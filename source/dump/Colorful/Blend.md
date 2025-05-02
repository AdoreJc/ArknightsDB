# Blend

**Namespace:** `Colorful`


## Fields

- `Texture Texture`

- `Single Amount`

- `BlendingMode Mode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Blend : BaseEffect
{
	public Texture Texture; // 0x28
	public Single Amount; // 0x30
	public BlendingMode Mode; // 0x34


	// RVA: 0x34e8334 VA: 0x7595b00334
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e8494 VA: 0x7595b00494
	protected override String GetShaderName() { }
	// RVA: 0x34e84d4 VA: 0x7595b004d4
	public Void .ctor() { }
}
```