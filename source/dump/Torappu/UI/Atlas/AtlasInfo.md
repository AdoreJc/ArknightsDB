# AtlasInfo

**Namespace:** `Torappu.UI.Atlas`


## Fields

- `Int32 index`

- `Texture2D texture`

- `Texture2D alpha`

- `Int32 size`


## Methods

- `SpriteRenderData CreateRenderData(AtlasSprite)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Atlas
public class AtlasInfo : IHotfixable
{
	public Int32 index; // 0x10
	public Texture2D texture; // 0x18
	public Texture2D alpha; // 0x20
	public Int32 size; // 0x28
	private static DelegateBridge __Hotfix0_CreateRenderData; // 0x0
	private static DelegateBridge __Hotfix0_ConvertAtlasSize; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c5ff34 VA: 0x7595277f34
	public SpriteRenderData CreateRenderData(AtlasSprite sprite) { }
	// RVA: 0x2c60314 VA: 0x7595278314
	public static Int32 ConvertAtlasSize(AtlasSize size) { }
	// RVA: 0x2c601b0 VA: 0x75952781b0
	public Void .ctor() { }
}
```