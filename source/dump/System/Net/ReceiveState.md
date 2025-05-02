# ReceiveState

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class ReceiveState
{
	internal ResponseDescription Resp; // 0x10
	internal Int32 ValidThrough; // 0x18
	internal Byte[] Buffer; // 0x20
	internal CommandStream Connection; // 0x28


	// RVA: 0x641b064 VA: 0x7598a33064
	internal Void .ctor(CommandStream connection) { }
}
```