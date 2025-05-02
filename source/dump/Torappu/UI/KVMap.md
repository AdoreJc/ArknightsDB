# KVMap

**Namespace:** `Torappu.UI`


## Methods

- `Boolean ContainsKey(String)`

- `Boolean TryGetValue(String, out)`

- `Void SetValue(String, String)`

- `Void _Init()`

- `IEnumerator GetEnumerator()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class KVMap : ScriptableObject, IEnumerable
{
	private List`1 _keys; // 0x18
	private List`1 _values; // 0x20
	private Dictionary`2 _map; // 0x28


	// RVA: 0x21860cc VA: 0x759479e0cc
	public Boolean ContainsKey(String key) { }
	// RVA: 0x2186370 VA: 0x759479e370
	public Boolean TryGetValue(String key, out String value) { }
	// RVA: 0x21863e0 VA: 0x759479e3e0
	public Void SetValue(String key, String value) { }
	// RVA: 0x218612c VA: 0x759479e12c
	private Void _Init() { }
	// RVA: 0x2186534 VA: 0x759479e534
	public IEnumerator GetEnumerator() { }
	// RVA: 0x21865c8 VA: 0x759479e5c8
	public Void .ctor() { }
}
```