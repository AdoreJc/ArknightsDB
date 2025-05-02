# Posterize

**Namespace:** `Colorful`


## Fields

- `Int32 Levels`

- `Single Amount`

- `Boolean LuminosityOnly`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Posterize : BaseEffect
{
	public Int32 Levels; // 0x28
	public Single Amount; // 0x2c
	public Boolean LuminosityOnly; // 0x30


	// RVA: 0x34efeb0 VA: 0x7595b07eb0
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34eff80 VA: 0x7595b07f80
	protected override String GetShaderName() { }
	// RVA: 0x34effc0 VA: 0x7595b07fc0
	public Void .ctor() { }
}
```