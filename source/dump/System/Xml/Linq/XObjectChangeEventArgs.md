# XObjectChangeEventArgs

**Namespace:** `System.Xml.Linq`


## Fields

- `XObjectChange _objectChange`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XObjectChangeEventArgs : EventArgs
{
	private XObjectChange _objectChange; // 0x10
	public static readonly XObjectChangeEventArgs Add; // 0x0
	public static readonly XObjectChangeEventArgs Remove; // 0x8
	public static readonly XObjectChangeEventArgs Name; // 0x10
	public static readonly XObjectChangeEventArgs Value; // 0x18


	// RVA: 0x62855f8 VA: 0x759889d5f8
	public Void .ctor(XObjectChange objectChange) { }
	// RVA: 0x6285664 VA: 0x759889d664
	private static Void .cctor() { }
}
```