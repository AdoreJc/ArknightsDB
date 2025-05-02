# Noise

**Namespace:** `Colorful`


## Fields

- `ColorMode Mode`

- `Boolean Animate`

- `Single Seed`

- `Single Strength`

- `Single LumContribution`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Noise : BaseEffect
{
	public ColorMode Mode; // 0x28
	public Boolean Animate; // 0x2c
	public Single Seed; // 0x30
	public Single Strength; // 0x34
	public Single LumContribution; // 0x38


	// RVA: 0x34ef89c VA: 0x7595b0789c
	protected virtual Void Update() { }
	// RVA: 0x34ef8f4 VA: 0x7595b078f4
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ef9d8 VA: 0x7595b079d8
	protected override String GetShaderName() { }
	// RVA: 0x34efa18 VA: 0x7595b07a18
	public Void .ctor() { }
}
```