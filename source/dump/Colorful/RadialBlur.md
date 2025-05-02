# RadialBlur

**Namespace:** `Colorful`


## Fields

- `Single Strength`

- `Int32 Samples`

- `Vector2 Center`

- `QualityPreset Quality`

- `Single Sharpness`

- `Single Darkness`

- `Boolean EnableVignette`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class RadialBlur : BaseEffect
{
	public Single Strength; // 0x28
	public Int32 Samples; // 0x2c
	public Vector2 Center; // 0x30
	public QualityPreset Quality; // 0x38
	public Single Sharpness; // 0x3c
	public Single Darkness; // 0x40
	public Boolean EnableVignette; // 0x44


	// RVA: 0x34effd4 VA: 0x7595b07fd4
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f0144 VA: 0x7595b08144
	protected override String GetShaderName() { }
	// RVA: 0x34f0184 VA: 0x7595b08184
	public Void .ctor() { }
}
```