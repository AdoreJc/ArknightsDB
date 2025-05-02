# RemoteActivationAttribute

**Namespace:** `System.Runtime.Remoting.Activation`


## Fields

- `IList _contextProperties`


## Methods

- `Boolean IsContextOK(Context, IConstructionCallMessage)`

- `Void GetPropertiesForNewContext(IConstructionCallMessage)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Activation
internal class RemoteActivationAttribute : Attribute, IContextAttribute
{
	private IList _contextProperties; // 0x10


	// RVA: 0x5f9e038 VA: 0x75985b6038
	public Void .ctor(IList contextProperties) { }
	// RVA: 0x5f9e068 VA: 0x75985b6068
	public Boolean IsContextOK(Context ctx, IConstructionCallMessage ctor) { }
	// RVA: 0x5f9e070 VA: 0x75985b6070
	public Void GetPropertiesForNewContext(IConstructionCallMessage ctor) { }
}
```