# RemoteActivator

**Namespace:** `System.Runtime.Remoting.Activation`


## Properties

- `IActivator NextActivator`


## Methods

- `IConstructionReturnMessage Activate(IConstructionCallMessage)`

- `IActivator get_NextActivator()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Activation
internal class RemoteActivator : MarshalByRefObject, IActivator
{

	public IActivator NextActivator { get; }

	// RVA: 0x5f9e458 VA: 0x75985b6458
	public IConstructionReturnMessage Activate(IConstructionCallMessage msg) { }
	// RVA: 0x5f9e8ec VA: 0x75985b68ec
	public IActivator get_NextActivator() { }
}
```