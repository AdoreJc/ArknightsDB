# CADMethodRef

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `Boolean ctor`

- `String typeName`

- `String methodName`


## Methods

- `MethodBase Resolve()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class CADMethodRef
{
	private Boolean ctor; // 0x10
	private String typeName; // 0x18
	private String methodName; // 0x20
	private String[] param_names; // 0x28
	private String[] generic_arg_names; // 0x30


	// RVA: 0x5fa0c38 VA: 0x75985b8c38
	private Type[] GetTypes(String[] typeArray) { }
	// RVA: 0x5fa0da0 VA: 0x75985b8da0
	public MethodBase Resolve() { }
	// RVA: 0x5fa12c4 VA: 0x75985b92c4
	public Void .ctor(IMethodMessage msg) { }
}
```