# DirectionalBlur

**Namespace:** `Colorful`


## Fields

- `QualityPreset Quality`

- `Int32 Samples`

- `Single Strength`

- `Single Angle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class DirectionalBlur : BaseEffect
{
	public QualityPreset Quality; // 0x28
	public Int32 Samples; // 0x2c
	public Single Strength; // 0x30
	public Single Angle; // 0x34


	// RVA: 0x34e99d8 VA: 0x7595b019d8
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e9b0c VA: 0x7595b01b0c
	protected override String GetShaderName() { }
	// RVA: 0x34e9b4c VA: 0x7595b01b4c
	public Void .ctor() { }
}
```