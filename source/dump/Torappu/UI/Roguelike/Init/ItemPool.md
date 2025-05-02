# ItemPool

**Namespace:** `Torappu.UI.Roguelike.Init`


## Properties

- `Int32 count`

- `T Item`


## Methods

- `Void Clear()`

- `T FetchItem()`

- `Int32 get_count()`

- `T get_Item(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class ItemPool`1
{
	private Func`1 m_creator; // 0x0
	private List`1 m_items; // 0x0
	private List`1 m_usingItems; // 0x0

	public Int32 count { get; }
	public T Item { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor(Func`1 creator) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public T FetchItem() { }
	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
}
```