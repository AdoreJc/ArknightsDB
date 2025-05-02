# CallContextSecurityData

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `IPrincipal _principal`


## Methods

- `Object Clone()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class CallContextSecurityData : ICloneable
{
	private IPrincipal _principal; // 0x10

	internal Boolean HasInfo { get; }

	// RVA: 0x5fa03b8 VA: 0x75985b83b8
	internal Boolean get_HasInfo() { }
	// RVA: 0x5fa0338 VA: 0x75985b8338
	public Object Clone() { }
	// RVA: 0x5fa0520 VA: 0x75985b8520
	public Void .ctor() { }
}
```