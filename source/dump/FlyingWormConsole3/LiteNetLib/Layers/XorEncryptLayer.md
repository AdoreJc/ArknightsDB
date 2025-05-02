# XorEncryptLayer

**Namespace:** `FlyingWormConsole3.LiteNetLib.Layers`


## Methods

- `Void SetKey(String)`

- `Void SetKey(Byte[])`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib.Layers
public class XorEncryptLayer : PacketLayerBase
{
	private Byte[] _byteKey; // 0x18


	// RVA: 0x410bf08 VA: 0x7596723f08
	public Void .ctor() { }
	// RVA: 0x410bf24 VA: 0x7596723f24
	public Void .ctor(Byte[] key) { }
	// RVA: 0x410bff4 VA: 0x7596723ff4
	public Void .ctor(String key) { }
	// RVA: 0x410c024 VA: 0x7596724024
	public Void SetKey(String key) { }
	// RVA: 0x410bf54 VA: 0x7596723f54
	public Void SetKey(Byte[] key) { }
	// RVA: 0x410c070 VA: 0x7596724070
	public override Void ProcessInboundPacket(IPEndPoint endPoint, ref Byte[] data, ref Int32 offset, ref Int32 length) { }
	// RVA: 0x410c0fc VA: 0x75967240fc
	public override Void ProcessOutBoundPacket(IPEndPoint endPoint, ref Byte[] data, ref Int32 offset, ref Int32 length) { }
}
```