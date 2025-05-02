# RequestCachePolicy

**Namespace:** `System.Net.Cache`


## Fields

- `RequestCacheLevel m_Level`


## Properties

- `RequestCacheLevel Level`


## Methods

- `RequestCacheLevel get_Level()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Cache
public class RequestCachePolicy
{
	private RequestCacheLevel m_Level; // 0x10

	public RequestCacheLevel Level { get; }

	// RVA: 0x634c7a0 VA: 0x75989647a0
	public Void .ctor(RequestCacheLevel level) { }
	// RVA: 0x634c81c VA: 0x759896481c
	public RequestCacheLevel get_Level() { }
	// RVA: 0x634c824 VA: 0x7598964824
	public override String ToString() { }
}
```