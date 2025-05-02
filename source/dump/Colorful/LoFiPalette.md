# LoFiPalette

**Namespace:** `Colorful`


## Fields

- `Preset Palette`

- `Boolean Pixelize`

- `Single PixelSize`

- `Preset m_CurrentPreset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class LoFiPalette : LookupFilter3D
{
	public Preset Palette; // 0x60
	public Boolean Pixelize; // 0x64
	public Single PixelSize; // 0x68
	protected Preset m_CurrentPreset; // 0x6c


	// RVA: 0x34ecf54 VA: 0x7595b04f54
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ed100 VA: 0x7595b05100
	protected override Void RenderLut2D(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ed3f4 VA: 0x7595b053f4
	protected override Void RenderLut3D(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34eda98 VA: 0x7595b05a98
	public Void .ctor() { }
}
```