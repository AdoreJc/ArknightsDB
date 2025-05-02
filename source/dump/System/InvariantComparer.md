# InvariantComparer

**Namespace:** `System`


## Fields

- `CompareInfo m_compareInfo`


## Methods

- `Int32 Compare(Object, Object)`


## Dump
```C#
// Dll : System.dll
// Namespace : System
internal class InvariantComparer : IComparer
{
	private CompareInfo m_compareInfo; // 0x10
	internal static readonly InvariantComparer Default; // 0x0


	// RVA: 0x636f048 VA: 0x7598987048
	internal Void .ctor() { }
	// RVA: 0x636f0cc VA: 0x75989870cc
	public Int32 Compare(Object a, Object b) { }
	// RVA: 0x636f1b8 VA: 0x75989871b8
	private static Void .cctor() { }
}
```