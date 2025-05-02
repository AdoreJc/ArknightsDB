# CaseInsensitiveAscii

**Namespace:** `System.Net`


## Methods

- `Int32 GetHashCode(Object)`

- `Int32 Compare(Object, Object)`

- `Int32 FastGetHashCode(String)`

- `Boolean Equals(Object, Object)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class CaseInsensitiveAscii : IEqualityComparer, IComparer
{
	internal static readonly CaseInsensitiveAscii StaticInstance; // 0x0
	internal static readonly Byte[] AsciiToLower; // 0x8


	// RVA: 0x642e988 VA: 0x7598a46988
	public Int32 GetHashCode(Object myObject) { }
	// RVA: 0x642eaa0 VA: 0x7598a46aa0
	public Int32 Compare(Object firstObject, Object secondObject) { }
	// RVA: 0x642ec10 VA: 0x7598a46c10
	private Int32 FastGetHashCode(String myString) { }
	// RVA: 0x642ed00 VA: 0x7598a46d00
	public Boolean Equals(Object firstObject, Object secondObject) { }
	// RVA: 0x642ee78 VA: 0x7598a46e78
	public Void .ctor() { }
	// RVA: 0x642ee80 VA: 0x7598a46e80
	private static Void .cctor() { }
}
```