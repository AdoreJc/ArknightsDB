# DIYRoomTemplate

**Namespace:** ` `


## Fields

- `String _id`

- `Int32 _width`

- `Int32 _height`

- `Int32 _depth`

- `GameObject _prefab`


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
public class DIYRoomTemplate : IDIYRoomTemplate
{
	private String _id; // 0x10
	private Int32 _width; // 0x18
	private Int32 _height; // 0x1c
	private Int32 _depth; // 0x20
	private GameObject _prefab; // 0x28
	private RectConfig[] _obtacles; // 0x30

	public String id { get; }
	public Int32 width { get; }
	public Int32 height { get; }
	public Int32 depth { get; }
	public GameObject prefab { get; }

	// RVA: 0x37f5f8c VA: 0x7595e0df8c
	public String get_id() { }
	// RVA: 0x37f5f94 VA: 0x7595e0df94
	public Int32 get_width() { }
	// RVA: 0x37f5f9c VA: 0x7595e0df9c
	public Int32 get_height() { }
	// RVA: 0x37f5fa4 VA: 0x7595e0dfa4
	public Int32 get_depth() { }
	// RVA: 0x37f5fac VA: 0x7595e0dfac
	public GameObject get_prefab() { }
	// RVA: 0x37f5fb4 VA: 0x7595e0dfb4
	public Void ForEachObstacle(Action`1 action) { }
	// RVA: 0x37f60f0 VA: 0x7595e0e0f0
	public Void .ctor() { }
}
```