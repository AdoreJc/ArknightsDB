# Technicolor

**Namespace:** `Colorful`


## Fields

- `Single Exposure`

- `Vector3 Balance`

- `Single Amount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Technicolor : BaseEffect
{
	public Single Exposure; // 0x28
	public Vector3 Balance; // 0x2c
	public Single Amount; // 0x38


	// RVA: 0x34f1124 VA: 0x7595b09124
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f12a4 VA: 0x7595b092a4
	protected override String GetShaderName() { }
	// RVA: 0x34f12e4 VA: 0x7595b092e4
	public Void .ctor() { }
}
```