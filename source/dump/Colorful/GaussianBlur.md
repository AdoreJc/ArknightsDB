# GaussianBlur

**Namespace:** `Colorful`


## Fields

- `Int32 Passes`

- `Single Downscaling`

- `Single Amount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class GaussianBlur : BaseEffect
{
	public Int32 Passes; // 0x28
	public Single Downscaling; // 0x2c
	public Single Amount; // 0x30


	// RVA: 0x34ea624 VA: 0x7595b02624
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ea800 VA: 0x7595b02800
	protected virtual Void OnePassBlur(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34eaa3c VA: 0x7595b02a3c
	protected virtual Void MultiPassBlur(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34eadc8 VA: 0x7595b02dc8
	protected override String GetShaderName() { }
	// RVA: 0x34eae08 VA: 0x7595b02e08
	public Void .ctor() { }
}
```