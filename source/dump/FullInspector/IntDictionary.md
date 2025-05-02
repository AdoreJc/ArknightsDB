# IntDictionary

**Namespace:** `FullInspector`


## Properties

- `TValue Item`

- `Int32 Count`

- `Boolean IsReadOnly`


## Methods

- `Void Add(Int32, TValue)`

- `Boolean ContainsKey(Int32)`

- `Boolean Remove(Int32)`

- `Boolean TryGetValue(Int32, out)`

- `TValue get_Item(Int32)`

- `Void set_Item(Int32, TValue)`

- `Void Add(KeyValuePair`2)`

- `Void Clear()`

- `Boolean Contains(KeyValuePair`2)`

- `Void CopyTo(KeyValuePair`2[], Int32)`

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `Boolean Remove(KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
internal class IntDictionary`1 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable
{
	private List`1 _positives; // 0x0
	private Dictionary`2 _negatives; // 0x0

	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }
	public TValue Item { get; set; }
	public Int32 Count { get; }
	public Boolean IsReadOnly { get; }

	// RVA: 0x VA: 0x0
	public Void Add(Int32 key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(Int32 key) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(Int32 key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(Int32 key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(Int32 key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Add(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(KeyValuePair`2[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```