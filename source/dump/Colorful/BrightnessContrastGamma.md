# BrightnessContrastGamma

**Namespace:** `Colorful`


## Fields

- `Single Brightness`

- `Single Contrast`

- `Vector3 ContrastCoeff`

- `Single Gamma`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class BrightnessContrastGamma : BaseEffect
{
	public Single Brightness; // 0x28
	public Single Contrast; // 0x2c
	public Vector3 ContrastCoeff; // 0x30
	public Single Gamma; // 0x3c


	// RVA: 0x34e84e4 VA: 0x7595b004e4
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e865c VA: 0x7595b0065c
	protected override String GetShaderName() { }
	// RVA: 0x34e869c VA: 0x7595b0069c
	public Void .ctor() { }
}
```