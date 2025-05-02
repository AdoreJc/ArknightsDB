# SCurveContrast

**Namespace:** `Colorful`


## Fields

- `Single RedSteepness`

- `Single RedGamma`

- `Single GreenSteepness`

- `Single GreenGamma`

- `Single BlueSteepness`

- `Single BlueGamma`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class SCurveContrast : BaseEffect
{
	public Single RedSteepness; // 0x28
	public Single RedGamma; // 0x2c
	public Single GreenSteepness; // 0x30
	public Single GreenGamma; // 0x34
	public Single BlueSteepness; // 0x38
	public Single BlueGamma; // 0x3c


	// RVA: 0x34f0344 VA: 0x7595b08344
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f0480 VA: 0x7595b08480
	protected override String GetShaderName() { }
	// RVA: 0x34f04c0 VA: 0x7595b084c0
	public Void .ctor() { }
}
```