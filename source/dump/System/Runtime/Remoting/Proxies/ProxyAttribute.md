# ProxyAttribute

**Namespace:** `System.Runtime.Remoting.Proxies`


## Methods

- `Void GetPropertiesForNewContext(IConstructionCallMessage)`

- `Boolean IsContextOK(Context, IConstructionCallMessage)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Proxies
public class ProxyAttribute : Attribute, IContextAttribute
{


	// RVA: 0x5f8e228 VA: 0x75985a6228
	public virtual MarshalByRefObject CreateInstance(Type serverType) { }
	// RVA: 0x5f8e36c VA: 0x75985a636c
	public virtual RealProxy CreateProxy(ObjRef objRef, Type serverType, Object serverObject, Context serverContext) { }
	// RVA: 0x5f8e3dc VA: 0x75985a63dc
	public Void GetPropertiesForNewContext(IConstructionCallMessage msg) { }
	// RVA: 0x5f8e3e0 VA: 0x75985a63e0
	public Boolean IsContextOK(Context ctx, IConstructionCallMessage msg) { }
}
```