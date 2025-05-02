# AppDomainLevelActivator

**Namespace:** `System.Runtime.Remoting.Activation`


## Fields

- `String _activationUrl`

- `IActivator _next`


## Properties

- `IActivator NextActivator`


## Methods

- `IActivator get_NextActivator()`

- `IConstructionReturnMessage Activate(IConstructionCallMessage)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Activation
internal class AppDomainLevelActivator : IActivator
{
	private String _activationUrl; // 0x10
	private IActivator _next; // 0x18

	public IActivator NextActivator { get; }

	// RVA: 0x5f9d14c VA: 0x75985b514c
	public Void .ctor(String activationUrl, IActivator next) { }
	// RVA: 0x5f9d70c VA: 0x75985b570c
	public IActivator get_NextActivator() { }
	// RVA: 0x5f9d714 VA: 0x75985b5714
	public IConstructionReturnMessage Activate(IConstructionCallMessage ctorCall) { }
}
```