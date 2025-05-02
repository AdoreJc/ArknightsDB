# DynamicPropertyCollection

**Namespace:** `System.Runtime.Remoting.Contexts`


## Fields

- `ArrayList _properties`


## Properties

- `Boolean HasProperties`


## Methods

- `Boolean get_HasProperties()`

- `Boolean RegisterDynamicProperty(IDynamicProperty)`

- `Boolean UnregisterDynamicProperty(String)`

- `Void NotifyMessage(Boolean, IMessage, Boolean, Boolean)`

- `Int32 FindProperty(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Contexts
internal class DynamicPropertyCollection
{
	private ArrayList _properties; // 0x10

	public Boolean HasProperties { get; }

	// RVA: 0x5f94b8c VA: 0x75985acb8c
	public Boolean get_HasProperties() { }
	// RVA: 0x5f94e30 VA: 0x75985ace30
	public Boolean RegisterDynamicProperty(IDynamicProperty prop) { }
	// RVA: 0x5f951c4 VA: 0x75985ad1c4
	public Boolean UnregisterDynamicProperty(String name) { }
	// RVA: 0x5f954b0 VA: 0x75985ad4b0
	public Void NotifyMessage(Boolean start, IMessage msg, Boolean client_site, Boolean async) { }
	// RVA: 0x5f976f0 VA: 0x75985af6f0
	private Int32 FindProperty(String name) { }
	// RVA: 0x5f9533c VA: 0x75985ad33c
	public Void .ctor() { }
}
```