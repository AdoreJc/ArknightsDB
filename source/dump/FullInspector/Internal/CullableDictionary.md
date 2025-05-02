# CullableDictionary

**Namespace:** `FullInspector.Internal`


## Fields

- `TDictionary _primary`

- `TDictionary _culled`

- `Boolean _isCulling`


## Properties

- `TValue Item`

- `Boolean IsEmpty`


## Methods

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Void Add(TKey, TValue)`

- `Boolean TryGetValue(TKey, out)`

- `Void BeginCullZone()`

- `Void EndCullZone()`

- `Boolean get_IsEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class CullableDictionary`3 : ICullableDictionary`2
{
	private TDictionary _primary; // 0x0
	private TDictionary _culled; // 0x0
	private Boolean _isCulling; // 0x0

	public TValue Item { get; set; }
	public IEnumerable`1 Items { get; }
	public Boolean IsEmpty { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public IEnumerable`1 get_Items() { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Void BeginCullZone() { }
	// RVA: 0x VA: 0x0
	public Void EndCullZone() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsEmpty() { }
}
```