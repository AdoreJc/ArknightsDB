# CriFsWebInstallRequest

**Namespace:** `CriWare`


## Fields

- `CriFsWebInstaller installer`

- `UInt32 crc32`

- `Boolean crc32_set`


## Methods

- `Boolean GetCRC32(out)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsWebInstallRequest : CriFsInstallRequest
{
	private CriFsWebInstaller installer; // 0x58
	private UInt32 crc32; // 0x60
	private Boolean crc32_set; // 0x64


	// RVA: 0x4140738 VA: 0x7596758738
	public override Void Stop() { }
	// RVA: 0x41407b4 VA: 0x75967587b4
	public Boolean GetCRC32(out UInt32 ret_val) { }
	// RVA: 0x41407c4 VA: 0x75967587c4
	public Void .ctor(String srcPath, String dstPath, DoneDelegate doneDelegate) { }
	// RVA: 0x41409fc VA: 0x75967589fc
	public override Void Update() { }
	// RVA: 0x4140c68 VA: 0x7596758c68
	protected override Void Dispose(Boolean disposing) { }
}
```