# Dithering

**Namespace:** `Colorful`


## Fields

- `Boolean ShowOriginal`

- `Boolean ConvertToGrayscale`

- `Single RedLuminance`

- `Single GreenLuminance`

- `Single BlueLuminance`

- `Single Amount`

- `Texture2D m_DitherPattern`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Dithering : BaseEffect
{
	public Boolean ShowOriginal; // 0x28
	public Boolean ConvertToGrayscale; // 0x29
	public Single RedLuminance; // 0x2c
	public Single GreenLuminance; // 0x30
	public Single BlueLuminance; // 0x34
	public Single Amount; // 0x38
	protected Texture2D m_DitherPattern; // 0x40


	// RVA: 0x34e9b68 VA: 0x7595b01b68
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e9d40 VA: 0x7595b01d40
	protected override String GetShaderName() { }
	// RVA: 0x34e9d80 VA: 0x7595b01d80
	public Void .ctor() { }
}
```