# RequestCacheBinding

**Namespace:** `System.Net.Cache`


## Fields

- `RequestCache m_RequestCache`

- `RequestCacheValidator m_CacheValidator`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Cache
internal class RequestCacheBinding
{
	private RequestCache m_RequestCache; // 0x10
	private RequestCacheValidator m_CacheValidator; // 0x18

	internal RequestCache Cache { get; }
	internal RequestCacheValidator Validator { get; }

	// RVA: 0x634c790 VA: 0x7598964790
	internal RequestCache get_Cache() { }
	// RVA: 0x634c798 VA: 0x7598964798
	internal RequestCacheValidator get_Validator() { }
}
```