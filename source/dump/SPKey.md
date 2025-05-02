# SPKey

**Namespace:** ` `


## Fields

- `Uri uri`

- `Uri proxy`

- `Boolean use_connect`


## Properties

- `Boolean UsesProxy`


## Methods

- `Boolean get_UsesProxy()`


## Dump
```C#
// Dll : System.dll
// Namespace : 
internal class SPKey
{
	private Uri uri; // 0x10
	private Uri proxy; // 0x18
	private Boolean use_connect; // 0x20

	public Boolean UsesProxy { get; }

	// RVA: 0x6331b48 VA: 0x7598949b48
	public Void .ctor(Uri uri, Uri proxy, Boolean use_connect) { }
	// RVA: 0x6331c38 VA: 0x7598949c38
	public Boolean get_UsesProxy() { }
	// RVA: 0x6331c98 VA: 0x7598949c98
	public override Int32 GetHashCode() { }
	// RVA: 0x6331d68 VA: 0x7598949d68
	public override Boolean Equals(Object obj) { }
}
```