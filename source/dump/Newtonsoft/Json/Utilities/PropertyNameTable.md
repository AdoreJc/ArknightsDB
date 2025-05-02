# PropertyNameTable

**Namespace:** `Newtonsoft.Json.Utilities`


## Fields

- `Int32 _count`

- `Int32 _mask`


## Methods

- `String Get(Char[], Int32, Int32)`

- `String Add(String)`

- `String AddEntry(String, Int32)`

- `Void Grow()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class PropertyNameTable
{
	private static readonly Int32 HashCodeRandomizer; // 0x0
	private Int32 _count; // 0x10
	private Entry[] _entries; // 0x18
	private Int32 _mask; // 0x20


	// RVA: 0x6153334 VA: 0x759876b334
	private static Void .cctor() { }
	// RVA: 0x6153384 VA: 0x759876b384
	public Void .ctor() { }
	// RVA: 0x61533f4 VA: 0x759876b3f4
	public String Get(Char[] key, Int32 start, Int32 length) { }
	// RVA: 0x615362c VA: 0x759876b62c
	public String Add(String key) { }
	// RVA: 0x61537e0 VA: 0x759876b7e0
	private String AddEntry(String str, Int32 hashCode) { }
	// RVA: 0x6153944 VA: 0x759876b944
	private Void Grow() { }
	// RVA: 0x615357c VA: 0x759876b57c
	private static Boolean TextEquals(String str1, Char[] str2, Int32 str2Start, Int32 str2Length) { }
}
```