# CallContextRemotingData

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `String _logicalCallID`


## Methods

- `Object Clone()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class CallContextRemotingData : ICloneable
{
	private String _logicalCallID; // 0x10

	internal String LogicalCallID { get; set; }
	internal Boolean HasInfo { get; }

	// RVA: 0x5fa0528 VA: 0x75985b8528
	internal String get_LogicalCallID() { }
	// RVA: 0x5fa0530 VA: 0x75985b8530
	internal Void set_LogicalCallID(String value) { }
	// RVA: 0x5fa03a8 VA: 0x75985b83a8
	internal Boolean get_HasInfo() { }
	// RVA: 0x5fa02c8 VA: 0x75985b82c8
	public Object Clone() { }
	// RVA: 0x5fa0538 VA: 0x75985b8538
	public Void .ctor() { }
}
```