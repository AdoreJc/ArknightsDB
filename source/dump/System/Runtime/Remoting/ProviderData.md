# ProviderData

**Namespace:** `System.Runtime.Remoting`


## Methods

- `Void CopyFrom(ProviderData)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class ProviderData
{
	internal String Ref; // 0x10
	internal String Type; // 0x18
	internal String Id; // 0x20
	internal Hashtable CustomProperties; // 0x28
	internal IList CustomData; // 0x30


	// RVA: 0x5f81438 VA: 0x7598599438
	public Void CopyFrom(ProviderData other) { }
	// RVA: 0x5f85b00 VA: 0x759859db00
	public Void .ctor() { }
}
```