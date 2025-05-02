# ThreadSafeStore

**Namespace:** `Newtonsoft.Json.Utilities`


## Methods

- `TValue Get(TKey)`

- `TValue AddValue(TKey)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class ThreadSafeStore`2
{
	private readonly Object _lock; // 0x0
	private Dictionary`2 _store; // 0x0
	private readonly Func`2 _creator; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(Func`2 creator) { }
	// RVA: 0x VA: 0x0
	public TValue Get(TKey key) { }
	// RVA: 0x VA: 0x0
	private TValue AddValue(TKey key) { }
}
```