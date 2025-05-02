# ImageData

**Namespace:** ` `


## Fields

- `Vector2 pos`

- `Vector2 size`

- `String spritePath`

- `String matPath`

- `Type imgType`


## Methods

- `Void ParseFromJson(JObject)`

- `Void FillUIData(Image, AssetPathConvertor)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ImageData
{
	public Vector2 pos; // 0x10
	public Vector2 size; // 0x18
	public String spritePath; // 0x20
	public String matPath; // 0x28
	public Type imgType; // 0x30


	// RVA: 0x284a4a8 VA: 0x7594e624a8
	public Void ParseFromJson(JObject jdata) { }
	// RVA: 0x284a694 VA: 0x7594e62694
	public Void FillUIData(Image image, AssetPathConvertor pathConvertor) { }
	// RVA: 0x284a4a0 VA: 0x7594e624a0
	public Void .ctor() { }
}
```