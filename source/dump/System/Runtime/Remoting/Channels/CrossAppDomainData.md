# CrossAppDomainData

**Namespace:** `System.Runtime.Remoting.Channels`


## Fields

- `Object _ContextID`

- `Int32 _DomainID`

- `String _processGuid`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Channels
internal class CrossAppDomainData
{
	private Object _ContextID; // 0x10
	private Int32 _DomainID; // 0x18
	private String _processGuid; // 0x20

	internal Int32 DomainID { get; }
	internal String ProcessID { get; }

	// RVA: 0x5f9b5e8 VA: 0x75985b35e8
	internal Void .ctor(Int32 domainId) { }
	// RVA: 0x5f9b6ac VA: 0x75985b36ac
	internal Int32 get_DomainID() { }
	// RVA: 0x5f9b6b4 VA: 0x75985b36b4
	internal String get_ProcessID() { }
}
```