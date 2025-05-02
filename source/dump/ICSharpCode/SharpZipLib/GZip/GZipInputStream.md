# GZipInputStream

**Namespace:** `ICSharpCode.SharpZipLib.GZip`


## Fields

- `Crc32 crc`

- `Boolean readGZIPHeader`


## Methods

- `Boolean ReadHeader()`

- `Void ReadFooter()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.GZip
public class GZipInputStream : InflaterInputStream
{
	protected Crc32 crc; // 0x50
	private Boolean readGZIPHeader; // 0x58


	// RVA: 0x5ec4db4 VA: 0x75984dcdb4
	public Void .ctor(Stream baseInputStream) { }
	// RVA: 0x5ec4dbc VA: 0x75984dcdbc
	public Void .ctor(Stream baseInputStream, Int32 size) { }
	// RVA: 0x5ec4f50 VA: 0x75984dcf50
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ec500c VA: 0x75984dd00c
	private Boolean ReadHeader() { }
	// RVA: 0x5ec5408 VA: 0x75984dd408
	private Void ReadFooter() { }
}
```