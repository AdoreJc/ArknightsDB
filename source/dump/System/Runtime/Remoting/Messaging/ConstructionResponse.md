# ConstructionResponse

**Namespace:** `System.Runtime.Remoting.Messaging`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
public class ConstructionResponse : MethodResponse, IConstructionReturnMessage, IMethodReturnMessage, IMethodMessage, IMessage
{

	public override IDictionary Properties { get; }

	// RVA: 0x5f922bc VA: 0x75985aa2bc
	internal Void .ctor(Object resultObject, LogicalCallContext callCtx, IMethodCallMessage msg) { }
	// RVA: 0x5f9dbf0 VA: 0x75985b5bf0
	internal Void .ctor(Exception e, IMethodCallMessage msg) { }
	// RVA: 0x5fa668c VA: 0x75985be68c
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fa671c VA: 0x75985be71c
	public override IDictionary get_Properties() { }
}
```