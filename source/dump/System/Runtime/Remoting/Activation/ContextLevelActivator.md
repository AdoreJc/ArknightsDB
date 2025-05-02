# ContextLevelActivator

**Namespace:** `System.Runtime.Remoting.Activation`


## Fields

- `IActivator m_NextActivator`


## Properties

- `IActivator NextActivator`


## Methods

- `IActivator get_NextActivator()`

- `IConstructionReturnMessage Activate(IConstructionCallMessage)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Activation
internal class ContextLevelActivator : IActivator
{
	private IActivator m_NextActivator; // 0x10

	public IActivator NextActivator { get; }

	// RVA: 0x5f9d190 VA: 0x75985b5190
	public Void .ctor(IActivator next) { }
	// RVA: 0x5f9dcec VA: 0x75985b5cec
	public IActivator get_NextActivator() { }
	// RVA: 0x5f9dcf4 VA: 0x75985b5cf4
	public IConstructionReturnMessage Activate(IConstructionCallMessage ctorCall) { }
}
```