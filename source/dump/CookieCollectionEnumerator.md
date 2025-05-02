# CookieCollectionEnumerator

**Namespace:** ` `


## Fields

- `CookieCollection m_cookies`

- `Int32 m_count`

- `Int32 m_index`

- `Int32 m_version`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class CookieCollectionEnumerator : IEnumerator
{
	private CookieCollection m_cookies; // 0x10
	private Int32 m_count; // 0x18
	private Int32 m_index; // 0x1c
	private Int32 m_version; // 0x20

	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x643a1e8 VA: 0x7598a521e8
	internal Void .ctor(CookieCollection cookies) { }
	// RVA: 0x643a250 VA: 0x7598a52250
	private Object System.Collections.IEnumerator.get_Current() { }
	// RVA: 0x643a2fc VA: 0x7598a522fc
	private Boolean System.Collections.IEnumerator.MoveNext() { }
	// RVA: 0x643a3a0 VA: 0x7598a523a0
	private Void System.Collections.IEnumerator.Reset() { }
}
```