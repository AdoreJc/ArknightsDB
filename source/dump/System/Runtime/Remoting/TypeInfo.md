# TypeInfo

**Namespace:** `System.Runtime.Remoting`


## Fields

- `String serverType`


## Properties

- `String TypeName`


## Methods

- `String get_TypeName()`

- `Boolean CanCastTo(Type, Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class TypeInfo : IRemotingTypeInfo
{
	private String serverType; // 0x10
	private String[] serverHierarchy; // 0x18
	private String[] interfacesImplemented; // 0x20

	public String TypeName { get; }

	// RVA: 0x5f7d9f8 VA: 0x75985959f8
	public Void .ctor(Type type) { }
	// RVA: 0x5f8c108 VA: 0x75985a4108
	public String get_TypeName() { }
	// RVA: 0x5f8c110 VA: 0x75985a4110
	public Boolean CanCastTo(Type fromType, Object o) { }
}
```