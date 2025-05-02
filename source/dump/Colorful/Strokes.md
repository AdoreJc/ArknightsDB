# Strokes

**Namespace:** `Colorful`


## Fields

- `ColorMode Mode`

- `Single Amplitude`

- `Single Frequency`

- `Single Scaling`

- `Single MaxThickness`

- `Single Threshold`

- `Single Harshness`

- `Single RedLuminance`

- `Single GreenLuminance`

- `Single BlueLuminance`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Strokes : BaseEffect
{
	public ColorMode Mode; // 0x28
	public Single Amplitude; // 0x2c
	public Single Frequency; // 0x30
	public Single Scaling; // 0x34
	public Single MaxThickness; // 0x38
	public Single Threshold; // 0x3c
	public Single Harshness; // 0x40
	public Single RedLuminance; // 0x44
	public Single GreenLuminance; // 0x48
	public Single BlueLuminance; // 0x4c


	// RVA: 0x34f0f3c VA: 0x7595b08f3c
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f10ac VA: 0x7595b090ac
	protected override String GetShaderName() { }
	// RVA: 0x34f10ec VA: 0x7595b090ec
	public Void .ctor() { }
}
```