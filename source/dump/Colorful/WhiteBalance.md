# WhiteBalance

**Namespace:** `Colorful`


## Fields

- `Color White`

- `BalanceMode Mode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class WhiteBalance : BaseEffect
{
	public Color White; // 0x28
	public BalanceMode Mode; // 0x38


	// RVA: 0x34f1b1c VA: 0x7595b09b1c
	protected virtual Void Reset() { }
	// RVA: 0x34f1b60 VA: 0x7595b09b60
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f1c28 VA: 0x7595b09c28
	protected override String GetShaderName() { }
	// RVA: 0x34f1c68 VA: 0x7595b09c68
	public Void .ctor() { }
}
```