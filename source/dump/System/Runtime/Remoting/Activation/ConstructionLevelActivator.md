# ConstructionLevelActivator

**Namespace:** `System.Runtime.Remoting.Activation`


## Properties

- `IActivator NextActivator`


## Methods

- `IActivator get_NextActivator()`

- `IConstructionReturnMessage Activate(IConstructionCallMessage)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Activation
internal class ConstructionLevelActivator : IActivator
{

	public IActivator NextActivator { get; }

	// RVA: 0x5f9dbf4 VA: 0x75985b5bf4
	public IActivator get_NextActivator() { }
	// RVA: 0x5f9dbfc VA: 0x75985b5bfc
	public IConstructionReturnMessage Activate(IConstructionCallMessage msg) { }
	// RVA: 0x5f9cf74 VA: 0x75985b4f74
	public Void .ctor() { }
}
```