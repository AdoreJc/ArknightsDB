# CriFsConfig

**Namespace:** `CriWare`


## Fields

- `Int32 numberOfLoaders`

- `Int32 numberOfBinders`

- `Int32 numberOfInstallers`

- `Int32 installBufferSize`

- `Int32 maxPath`

- `String userAgentString`

- `Boolean minimizeFileDescriptorUsage`

- `Boolean enableCrcCheck`

- `Int32 androidDeviceReadBitrate`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsConfig
{
	public const Int32 defaultAndroidDeviceReadBitrate; // 0x0
	public Int32 numberOfLoaders; // 0x10
	public Int32 numberOfBinders; // 0x14
	public Int32 numberOfInstallers; // 0x18
	public Int32 installBufferSize; // 0x1c
	public Int32 maxPath; // 0x20
	public String userAgentString; // 0x28
	public Boolean minimizeFileDescriptorUsage; // 0x30
	public Boolean enableCrcCheck; // 0x31
	public Int32 androidDeviceReadBitrate; // 0x34


	// RVA: 0x414a770 VA: 0x7596762770
	public Void .ctor() { }
}
```