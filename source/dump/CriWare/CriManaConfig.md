# CriManaConfig

**Namespace:** `CriWare`


## Fields

- `Int32 numberOfDecoders`

- `Int32 numberOfMaxEntries`

- `Boolean useStreamerManager`

- `PCH264PlaybackConfig pcH264PlaybackConfig`

- `VitaH264PlaybackConfig vitaH264PlaybackConfig`

- `WebGLConfig webglConfig`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriManaConfig
{
	public Int32 numberOfDecoders; // 0x10
	public Int32 numberOfMaxEntries; // 0x14
	public readonly Boolean graphicsMultiThreaded; // 0x18
	public Boolean useStreamerManager; // 0x19
	public PCH264PlaybackConfig pcH264PlaybackConfig; // 0x20
	public VitaH264PlaybackConfig vitaH264PlaybackConfig; // 0x28
	public WebGLConfig webglConfig; // 0x30


	// RVA: 0x414ad6c VA: 0x7596762d6c
	public Void .ctor() { }
}
```