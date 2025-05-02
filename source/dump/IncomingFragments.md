# IncomingFragments

**Namespace:** ` `


## Fields

- `Int32 ReceivedCount`

- `Int32 TotalSize`

- `Byte ChannelId`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : 
private class IncomingFragments
{
	public NetPacket[] Fragments; // 0x10
	public Int32 ReceivedCount; // 0x18
	public Int32 TotalSize; // 0x1c
	public Byte ChannelId; // 0x20


	// RVA: 0x4102f28 VA: 0x759671af28
	public Void .ctor() { }
}
```