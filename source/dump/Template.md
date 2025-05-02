# Template

**Namespace:** ` `


## Fields

- `RoomSlotModel roomSlotModel`

- `CachedAssetLoader m_cachedAssetLoader`


## Properties

- `String id`

- `Int32 width`

- `Int32 height`

- `Int32 depth`

- `GameObject prefab`


## Methods

- `String get_id()`

- `Int32 get_width()`

- `Int32 get_height()`

- `Int32 get_depth()`

- `GameObject get_prefab()`

- `Void ForEachObstacle(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Template : IDIYRoomTemplate
{
	public RoomSlotModel roomSlotModel; // 0x10
	private CachedAssetLoader m_cachedAssetLoader; // 0x18

	public String id { get; }
	public Int32 width { get; }
	public Int32 height { get; }
	public Int32 depth { get; }
	public GameObject prefab { get; }

	// RVA: 0x37ca628 VA: 0x7595de2628
	public Void .ctor(CachedAssetLoader loader) { }
	// RVA: 0x37ca7e4 VA: 0x7595de27e4
	public String get_id() { }
	// RVA: 0x37ca800 VA: 0x7595de2800
	public Int32 get_width() { }
	// RVA: 0x37ca828 VA: 0x7595de2828
	public Int32 get_height() { }
	// RVA: 0x37ca850 VA: 0x7595de2850
	public Int32 get_depth() { }
	// RVA: 0x37ca878 VA: 0x7595de2878
	public GameObject get_prefab() { }
	// RVA: 0x37ca9a0 VA: 0x7595de29a0
	public Void ForEachObstacle(Action`1 action) { }
}
```