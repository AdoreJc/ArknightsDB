# AtlasSprite

**Namespace:** ` `


## Fields

- `Texture2D mainTex`

- `Texture2D alphaTex`

- `AtlasCoord rect`

- `Int32 atlasSize`

- `Boolean rotate`


## Methods

- `Boolean IsEmpty()`

- `Void Set(SpriteRenderData)`

- `SpriteRenderData Get()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AtlasSprite
{
	public Texture2D mainTex; // 0x10
	public Texture2D alphaTex; // 0x18
	public AtlasCoord rect; // 0x20
	public Int32 atlasSize; // 0x30
	public Boolean rotate; // 0x34


	// RVA: 0x210a13c VA: 0x759472213c
	public Boolean IsEmpty() { }
	// RVA: 0x2109f4c VA: 0x7594721f4c
	public Void Set(SpriteRenderData data) { }
	// RVA: 0x210a300 VA: 0x7594722300
	public SpriteRenderData Get() { }
	// RVA: 0x2109f44 VA: 0x7594721f44
	public Void .ctor() { }
}
```