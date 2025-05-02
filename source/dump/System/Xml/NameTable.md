# NameTable

**Namespace:** `System.Xml`


## Fields

- `Int32 count`

- `Int32 mask`

- `Int32 hashCodeRandomizer`


## Methods

- `String AddEntry(String, Int32)`

- `Void Grow()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class NameTable : XmlNameTable
{
	private Entry[] entries; // 0x10
	private Int32 count; // 0x18
	private Int32 mask; // 0x1c
	private Int32 hashCodeRandomizer; // 0x20


	// RVA: 0x62afbb0 VA: 0x75988c7bb0
	public Void .ctor() { }
	// RVA: 0x62b8020 VA: 0x75988d0020
	public override String Add(String key) { }
	// RVA: 0x62b82a8 VA: 0x75988d02a8
	public override String Add(Char[] key, Int32 start, Int32 len) { }
	// RVA: 0x62b84d0 VA: 0x75988d04d0
	public override String Get(String value) { }
	// RVA: 0x62b819c VA: 0x75988d019c
	private String AddEntry(String str, Int32 hashCode) { }
	// RVA: 0x62b868c VA: 0x75988d068c
	private Void Grow() { }
	// RVA: 0x62b8420 VA: 0x75988d0420
	private static Boolean TextEquals(String str1, Char[] str2, Int32 str2Start, Int32 str2Length) { }
}
```