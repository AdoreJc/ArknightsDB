# CADSerializer

**Namespace:** `System.Runtime.Remoting.Channels`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Channels
internal class CADSerializer
{


	// RVA: 0x5f9c514 VA: 0x75985b4514
	internal static IMessage DeserializeMessage(MemoryStream mem, IMethodCallMessage msg) { }
	// RVA: 0x5f9bf38 VA: 0x75985b3f38
	internal static MemoryStream SerializeMessage(IMessage msg) { }
	// RVA: 0x5f9cbc4 VA: 0x75985b4bc4
	internal static Object DeserializeObjectSafe(Byte[] mem) { }
	// RVA: 0x5f9ccf8 VA: 0x75985b4cf8
	internal static MemoryStream SerializeObject(Object obj) { }
	// RVA: 0x5f9cc64 VA: 0x75985b4c64
	internal static Object DeserializeObject(MemoryStream mem) { }
}
```