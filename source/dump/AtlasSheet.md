# AtlasSheet

**Namespace:** ` `


## Properties

- `Int32 maxFreeRectWidth`

- `Int32 maxFreeRectHeight`

- `Texture2D pageTexture`

- `AtlasMaxRect rectBinPack`


## Methods

- `Int32 get_maxFreeRectWidth()`

- `Int32 get_maxFreeRectHeight()`

- `Texture2D get_pageTexture()`

- `AtlasMaxRect get_rectBinPack()`

- `RectInt InsertRect(Int32, Int32)`

- `Void CopyIntoAtlas(CommandBuffer, Texture, in)`

- `Void InsertRects(List`1, List`1)`

- `Void FreeRect(in)`

- `Void FreeRects(in)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class AtlasSheet
{
	private readonly Texture2D <pageTexture>k__BackingField; // 0x10
	private readonly Dictionary`2 <textureRefDict>k__BackingField; // 0x18
	private readonly AtlasMaxRect <rectBinPack>k__BackingField; // 0x20

	public Int32 maxFreeRectWidth { get; }
	public Int32 maxFreeRectHeight { get; }
	public Texture2D pageTexture { get; }
	public Dictionary`2 textureRefDict { get; }
	public AtlasMaxRect rectBinPack { get; }

	// RVA: 0x678890c VA: 0x7598da090c
	public Int32 get_maxFreeRectWidth() { }
	// RVA: 0x6788928 VA: 0x7598da0928
	public Int32 get_maxFreeRectHeight() { }
	// RVA: 0x6788dec VA: 0x7598da0dec
	public Texture2D get_pageTexture() { }
	// RVA: 0x6788df4 VA: 0x7598da0df4
	public Dictionary`2 get_textureRefDict() { }
	// RVA: 0x6788dfc VA: 0x7598da0dfc
	public AtlasMaxRect get_rectBinPack() { }
	// RVA: 0x6788740 VA: 0x7598da0740
	public Void .ctor(Int32 panelDepth, Int32 index, GraphicsFormat atlasFormat) { }
	// RVA: 0x6788944 VA: 0x7598da0944
	public RectInt InsertRect(Int32 width, Int32 height) { }
	// RVA: 0x67889fc VA: 0x7598da09fc
	public Void CopyIntoAtlas(CommandBuffer cmd, Texture texture, in RectInt rect) { }
	// RVA: 0x6788e04 VA: 0x7598da0e04
	public Void InsertRects(List`1 rects, List`1 dst) { }
	// RVA: 0x6788bc4 VA: 0x7598da0bc4
	public Void FreeRect(in RectInt rect) { }
	// RVA: 0x6788e24 VA: 0x7598da0e24
	public Void FreeRects(in List`1 rects) { }
}
```