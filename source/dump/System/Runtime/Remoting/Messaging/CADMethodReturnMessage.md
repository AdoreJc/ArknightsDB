# CADMethodReturnMessage

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `Object _returnValue`

- `CADArgHolder _exception`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class CADMethodReturnMessage : CADMessageBase
{
	private Object _returnValue; // 0x38
	private CADArgHolder _exception; // 0x40
	private Type[] _sig; // 0x48

	internal Int32 PropertiesCount { get; }

	// RVA: 0x5fa3690 VA: 0x75985bb690
	internal static CADMethodReturnMessage Create(IMessage callMsg) { }
	// RVA: 0x5fa3720 VA: 0x75985bb720
	internal Void .ctor(IMethodReturnMessage retMsg) { }
	// RVA: 0x5fa3ae0 VA: 0x75985bbae0
	internal ArrayList GetArguments() { }
	// RVA: 0x5fa3c2c VA: 0x75985bbc2c
	internal Object[] GetArgs(ArrayList args) { }
	// RVA: 0x5fa3c3c VA: 0x75985bbc3c
	internal Object GetReturnValue(ArrayList args) { }
	// RVA: 0x5fa3c4c VA: 0x75985bbc4c
	internal Exception GetException(ArrayList args) { }
	// RVA: 0x5fa3cf0 VA: 0x75985bbcf0
	internal Int32 get_PropertiesCount() { }
}
```