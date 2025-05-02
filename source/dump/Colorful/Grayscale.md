# Grayscale

**Namespace:** `Colorful`


## Fields

- `Single RedLuminance`

- `Single GreenLuminance`

- `Single BlueLuminance`

- `Single Amount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Grayscale : BaseEffect
{
	public Single RedLuminance; // 0x28
	public Single GreenLuminance; // 0x2c
	public Single BlueLuminance; // 0x30
	public Single Amount; // 0x34


	// RVA: 0x34ebbc4 VA: 0x7595b03bc4
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ebcb4 VA: 0x7595b03cb4
	protected override String GetShaderName() { }
	// RVA: 0x34ebcf4 VA: 0x7595b03cf4
	public Void .ctor() { }
}
```