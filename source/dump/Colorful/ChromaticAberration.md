# ChromaticAberration

**Namespace:** `Colorful`


## Fields

- `Single RedRefraction`

- `Single GreenRefraction`

- `Single BlueRefraction`

- `Boolean PreserveAlpha`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class ChromaticAberration : BaseEffect
{
	public Single RedRefraction; // 0x28
	public Single GreenRefraction; // 0x2c
	public Single BlueRefraction; // 0x30
	public Boolean PreserveAlpha; // 0x34


	// RVA: 0x34e8d14 VA: 0x7595b00d14
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e8dd8 VA: 0x7595b00dd8
	protected override String GetShaderName() { }
	// RVA: 0x34e8e18 VA: 0x7595b00e18
	public Void .ctor() { }
}
```