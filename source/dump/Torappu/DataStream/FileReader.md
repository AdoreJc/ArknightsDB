# FileReader

**Namespace:** `Torappu.DataStream`


## Methods

- `Void Dispose()`

- `Boolean ReadBool()`

- `SByte ReadSByte()`

- `Byte ReadByte()`

- `Int32 ReadBytes(Byte[], Int32, Int32)`

- `Int16 ReadInt16()`

- `Int32 ReadInt32()`

- `Int64 ReadInt64()`

- `String ReadString()`

- `String ReadString2()`

- `UInt16 ReadUint16()`

- `UInt32 ReadUint32()`

- `UInt64 ReadUint64()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataStream
public class FileReader : IStreamReader, IHotfixable, IDisposable
{
	private readonly BinaryReader m_reader; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge __Hotfix0_ReadBool; // 0x10
	private static DelegateBridge __Hotfix0_ReadSByte; // 0x18
	private static DelegateBridge __Hotfix0_ReadByte; // 0x20
	private static DelegateBridge __Hotfix0_ReadBytes; // 0x28
	private static DelegateBridge __Hotfix0_ReadInt16; // 0x30
	private static DelegateBridge __Hotfix0_ReadInt32; // 0x38
	private static DelegateBridge __Hotfix0_ReadInt64; // 0x40
	private static DelegateBridge __Hotfix0_ReadString; // 0x48
	private static DelegateBridge __Hotfix0_ReadString2; // 0x50
	private static DelegateBridge __Hotfix0_ReadUint16; // 0x58
	private static DelegateBridge __Hotfix0_ReadUint32; // 0x60
	private static DelegateBridge __Hotfix0_ReadUint64; // 0x68


	// RVA: 0x3724288 VA: 0x7595d3c288
	public Void .ctor(FileStream file) { }
	// RVA: 0x3724350 VA: 0x7595d3c350
	public Void Dispose() { }
	// RVA: 0x37243c8 VA: 0x7595d3c3c8
	public Boolean ReadBool() { }
	// RVA: 0x3724440 VA: 0x7595d3c440
	public SByte ReadSByte() { }
	// RVA: 0x37244a8 VA: 0x7595d3c4a8
	public Byte ReadByte() { }
	// RVA: 0x3724520 VA: 0x7595d3c520
	public Int32 ReadBytes(Byte[] dest, Int32 offset, Int32 len) { }
	// RVA: 0x37245d8 VA: 0x7595d3c5d8
	public Int16 ReadInt16() { }
	// RVA: 0x3724654 VA: 0x7595d3c654
	public Int32 ReadInt32() { }
	// RVA: 0x37246d0 VA: 0x7595d3c6d0
	public Int64 ReadInt64() { }
	// RVA: 0x372474c VA: 0x7595d3c74c
	public String ReadString() { }
	// RVA: 0x37247c8 VA: 0x7595d3c7c8
	public String ReadString2() { }
	// RVA: 0x3724844 VA: 0x7595d3c844
	public UInt16 ReadUint16() { }
	// RVA: 0x37248c0 VA: 0x7595d3c8c0
	public UInt32 ReadUint32() { }
	// RVA: 0x372493c VA: 0x7595d3c93c
	public UInt64 ReadUint64() { }
}
```