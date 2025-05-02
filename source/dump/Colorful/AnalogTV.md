# AnalogTV

**Namespace:** `Colorful`


## Fields

- `Boolean AutomaticPhase`

- `Single Phase`

- `Boolean ConvertToGrayscale`

- `Single NoiseIntensity`

- `Single ScanlinesIntensity`

- `Int32 ScanlinesCount`

- `Single ScanlinesOffset`

- `Boolean VerticalScanlines`

- `Single Distortion`

- `Single CubicDistortion`

- `Single Scale`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class AnalogTV : BaseEffect
{
	public Boolean AutomaticPhase; // 0x28
	public Single Phase; // 0x2c
	public Boolean ConvertToGrayscale; // 0x30
	public Single NoiseIntensity; // 0x34
	public Single ScanlinesIntensity; // 0x38
	public Int32 ScanlinesCount; // 0x3c
	public Single ScanlinesOffset; // 0x40
	public Boolean VerticalScanlines; // 0x44
	public Single Distortion; // 0x48
	public Single CubicDistortion; // 0x4c
	public Single Scale; // 0x50


	// RVA: 0x34e7848 VA: 0x7595aff848
	protected virtual Void Update() { }
	// RVA: 0x34e78a0 VA: 0x7595aff8a0
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e79a4 VA: 0x7595aff9a4
	protected override String GetShaderName() { }
	// RVA: 0x34e79e4 VA: 0x7595aff9e4
	public Void .ctor() { }
}
```