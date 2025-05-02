# SecureStringHasher

**Namespace:** `System.Xml`


## Fields

- `Int32 hashCodeRandomizer`


## Methods

- `Boolean Equals(String, String)`

- `Int32 GetHashCode(String)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class SecureStringHasher : IEqualityComparer`1
{
	private static HashCodeOfStringDelegate hashCodeDelegate; // 0x0
	private Int32 hashCodeRandomizer; // 0x10


	// RVA: 0x6278698 VA: 0x7598890698
	public Void .ctor() { }
	// RVA: 0x62786bc VA: 0x75988906bc
	public Boolean Equals(String x, String y) { }
	// RVA: 0x62786d4 VA: 0x75988906d4
	public Int32 GetHashCode(String key) { }
	// RVA: 0x62788d8 VA: 0x75988908d8
	private static Int32 GetHashCodeOfString(String key, Int32 sLen, Int64 additionalEntropy) { }
	// RVA: 0x6278780 VA: 0x7598890780
	private static HashCodeOfStringDelegate GetHashCodeDelegate() { }
}
```