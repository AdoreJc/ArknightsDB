# Vibrance

**Namespace:** `Colorful`


## Fields

- `Single Amount`

- `Single RedChannel`

- `Single GreenChannel`

- `Single BlueChannel`

- `Boolean AdvancedMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Vibrance : BaseEffect
{
	public Single Amount; // 0x28
	public Single RedChannel; // 0x2c
	public Single GreenChannel; // 0x30
	public Single BlueChannel; // 0x34
	public Boolean AdvancedMode; // 0x38


	// RVA: 0x34f15b8 VA: 0x7595b095b8
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f174c VA: 0x7595b0974c
	protected override String GetShaderName() { }
	// RVA: 0x34f178c VA: 0x7595b0978c
	public Void .ctor() { }
}
```