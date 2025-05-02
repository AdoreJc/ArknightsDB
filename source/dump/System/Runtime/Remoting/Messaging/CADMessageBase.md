# CADMessageBase

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `Int32 _propertyCount`

- `CADArgHolder _callContext`


## Methods

- `Object MarshalArgument(Object, ref)`

- `Object UnmarshalArgument(Object, ArrayList)`

- `Void SaveLogicalCallContext(IMethodMessage, ref)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class CADMessageBase
{
	protected Object[] _args; // 0x10
	protected Byte[] _serializedArgs; // 0x18
	protected Int32 _propertyCount; // 0x20
	protected CADArgHolder _callContext; // 0x28
	internal Byte[] serializedMethod; // 0x30


	// RVA: 0x5fa15d4 VA: 0x75985b95d4
	public Void .ctor(IMethodMessage msg) { }
	// RVA: 0x5fa1670 VA: 0x75985b9670
	internal MethodBase GetMethod() { }
	// RVA: 0x5fa16f0 VA: 0x75985b96f0
	protected static Type[] GetSignature(MethodBase methodBase, Boolean load) { }
	// RVA: 0x5fa18e0 VA: 0x75985b98e0
	internal static Int32 MarshalProperties(IDictionary dict, ref ArrayList args) { }
	// RVA: 0x5fa21e8 VA: 0x75985ba1e8
	internal static Void UnmarshalProperties(IDictionary dict, Int32 count, ArrayList args) { }
	// RVA: 0x5fa2324 VA: 0x75985ba324
	private static Boolean IsPossibleToIgnoreMarshal(Object obj) { }
	// RVA: 0x5fa24d4 VA: 0x75985ba4d4
	protected Object MarshalArgument(Object arg, ref ArrayList args) { }
	// RVA: 0x5fa26a8 VA: 0x75985ba6a8
	protected Object UnmarshalArgument(Object arg, ArrayList args) { }
	// RVA: 0x5fa2e10 VA: 0x75985bae10
	internal Object[] MarshalArguments(Object[] arguments, ref ArrayList args) { }
	// RVA: 0x5fa2f20 VA: 0x75985baf20
	internal Object[] UnmarshalArguments(Object[] arguments, ArrayList args) { }
	// RVA: 0x5fa3030 VA: 0x75985bb030
	protected Void SaveLogicalCallContext(IMethodMessage msg, ref ArrayList serializeList) { }
	// RVA: 0x5fa3288 VA: 0x75985bb288
	internal LogicalCallContext GetLogicalCallContext(ArrayList args) { }
}
```