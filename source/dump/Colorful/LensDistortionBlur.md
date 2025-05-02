# LensDistortionBlur

**Namespace:** `Colorful`


## Fields

- `QualityPreset Quality`

- `Int32 Samples`

- `Single Distortion`

- `Single CubicDistortion`

- `Single Scale`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class LensDistortionBlur : BaseEffect
{
	public QualityPreset Quality; // 0x28
	public Int32 Samples; // 0x2c
	public Single Distortion; // 0x30
	public Single CubicDistortion; // 0x34
	public Single Scale; // 0x38


	// RVA: 0x34ec878 VA: 0x7595b04878
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ec95c VA: 0x7595b0495c
	protected override String GetShaderName() { }
	// RVA: 0x34ec99c VA: 0x7595b0499c
	public Void .ctor() { }
}
```