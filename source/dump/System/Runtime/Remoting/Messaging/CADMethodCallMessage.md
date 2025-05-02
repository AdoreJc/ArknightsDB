# CADMethodCallMessage

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `String _uri`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class CADMethodCallMessage : CADMessageBase
{
	private String _uri; // 0x38

	internal String Uri { get; }
	internal Int32 PropertiesCount { get; }

	// RVA: 0x5fa3310 VA: 0x75985bb310
	internal String get_Uri() { }
	// RVA: 0x5f9c484 VA: 0x75985b4484
	internal static CADMethodCallMessage Create(IMessage callMsg) { }
	// RVA: 0x5fa3318 VA: 0x75985bb318
	internal Void .ctor(IMethodCallMessage callMsg) { }
	// RVA: 0x5fa352c VA: 0x75985bb52c
	internal ArrayList GetArguments() { }
	// RVA: 0x5fa3678 VA: 0x75985bb678
	internal Object[] GetArgs(ArrayList args) { }
	// RVA: 0x5fa3688 VA: 0x75985bb688
	internal Int32 get_PropertiesCount() { }
}
```