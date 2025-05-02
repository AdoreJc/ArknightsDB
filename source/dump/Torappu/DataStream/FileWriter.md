# FileWriter

**Namespace:** `Torappu.DataStream`


## Methods

- `Void Dispose()`

- `Void WriteBool(Boolean)`

- `Void WriteSByte(SByte)`

- `Void WriteByte(Byte)`

- `Int32 WriteBytes(Byte[], Int32, Int32)`

- `Void WriteInt16(Int16)`

- `Void WriteInt32(Int32)`

- `Void WriteInt64(Int64)`

- `Void WriteString(String)`

- `Void WriteString2(String)`

- `Void WriteUint16(UInt16)`

- `Void WriteUint32(UInt32)`

- `Void WriteUint64(UInt64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataStream
public class FileWriter : IStreamWriter, IHotfixable, IDisposable
{
	private readonly BinaryWriter m_file; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge __Hotfix0_WriteBool; // 0x10
	private static DelegateBridge __Hotfix0_WriteSByte; // 0x18
	private static DelegateBridge __Hotfix0_WriteByte; // 0x20
	private static DelegateBridge __Hotfix0_WriteBytes; // 0x28
	private static DelegateBridge __Hotfix0_WriteInt16; // 0x30
	private static DelegateBridge __Hotfix0_WriteInt32; // 0x38
	private static DelegateBridge __Hotfix0_WriteInt64; // 0x40
	private static DelegateBridge __Hotfix0_WriteString; // 0x48
	private static DelegateBridge __Hotfix0_WriteString2; // 0x50
	private static DelegateBridge __Hotfix0_WriteUint16; // 0x58
	private static DelegateBridge __Hotfix0_WriteUint32; // 0x60
	private static DelegateBridge __Hotfix0_WriteUint64; // 0x68


	// RVA: 0x37249b8 VA: 0x7595d3c9b8
	public Void .ctor(FileStream file) { }
	// RVA: 0x3724a94 VA: 0x7595d3ca94
	public Void Dispose() { }
	// RVA: 0x3724b0c VA: 0x7595d3cb0c
	public Void WriteBool(Boolean v) { }
	// RVA: 0x3724b9c VA: 0x7595d3cb9c
	public Void WriteSByte(SByte v) { }
	// RVA: 0x3724c1c VA: 0x7595d3cc1c
	public Void WriteByte(Byte v) { }
	// RVA: 0x3724cac VA: 0x7595d3ccac
	public Int32 WriteBytes(Byte[] src, Int32 offset, Int32 len) { }
	// RVA: 0x3724d68 VA: 0x7595d3cd68
	public Void WriteInt16(Int16 v) { }
	// RVA: 0x3724dfc VA: 0x7595d3cdfc
	public Void WriteInt32(Int32 v) { }
	// RVA: 0x3724e90 VA: 0x7595d3ce90
	public Void WriteInt64(Int64 v) { }
	// RVA: 0x3724f24 VA: 0x7595d3cf24
	public Void WriteString(String v) { }
	// RVA: 0x3724fb8 VA: 0x7595d3cfb8
	public Void WriteString2(String v) { }
	// RVA: 0x372504c VA: 0x7595d3d04c
	public Void WriteUint16(UInt16 v) { }
	// RVA: 0x37250e0 VA: 0x7595d3d0e0
	public Void WriteUint32(UInt32 v) { }
	// RVA: 0x3725174 VA: 0x7595d3d174
	public Void WriteUint64(UInt64 v) { }
}
```