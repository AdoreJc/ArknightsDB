# CriFsLoader

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`

- `GCHandle dstGch`

- `GCHandle srcGch`


## Methods

- `Void Dispose(Boolean)`

- `Void Load(CriFsBinder, String, Int64, Int64, Byte[])`

- `Void LoadById(CriFsBinder, Int32, Int64, Int64, Byte[])`

- `Void LoadWithoutDecompression(CriFsBinder, String, Int64, Int64, Byte[])`

- `Void LoadWithoutDecompressionById(CriFsBinder, Int32, Int64, Int64, Byte[])`

- `Void DecompressData(Int64, Byte[], Int64, Byte[])`

- `Void Stop()`

- `Status GetStatus()`

- `Void SetReadUnitSize(Int32)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsLoader : CriDisposable
{
	private IntPtr handle; // 0x20
	private GCHandle dstGch; // 0x28
	private GCHandle srcGch; // 0x30


	// RVA: 0x413c0dc VA: 0x75967540dc
	public Void .ctor() { }
	// RVA: 0x413c2fc VA: 0x75967542fc
	public override Void Dispose() { }
	// RVA: 0x413c360 VA: 0x7596754360
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x413c4d8 VA: 0x75967544d8
	public Void Load(CriFsBinder binder, String path, Int64 fileOffset, Int64 loadSize, Byte[] buffer) { }
	// RVA: 0x413c67c VA: 0x759675467c
	public Void LoadById(CriFsBinder binder, Int32 id, Int64 fileOffset, Int64 loadSize, Byte[] buffer) { }
	// RVA: 0x413c804 VA: 0x7596754804
	public Void LoadWithoutDecompression(CriFsBinder binder, String path, Int64 fileOffset, Int64 loadSize, Byte[] buffer) { }
	// RVA: 0x413c9a8 VA: 0x75967549a8
	public Void LoadWithoutDecompressionById(CriFsBinder binder, Int32 id, Int64 fileOffset, Int64 loadSize, Byte[] buffer) { }
	// RVA: 0x413cb30 VA: 0x7596754b30
	public Void DecompressData(Int64 srcSize, Byte[] srcBuffer, Int64 dstSize, Byte[] dstBuffer) { }
	// RVA: 0x413cc68 VA: 0x7596754c68
	public Void Stop() { }
	// RVA: 0x413cd50 VA: 0x7596754d50
	public Status GetStatus() { }
	// RVA: 0x413ce98 VA: 0x7596754e98
	public Void SetReadUnitSize(Int32 unit_size) { }
	// RVA: 0x413cf9c VA: 0x7596754f9c
	protected override Void Finalize() { }
	// RVA: 0x413c280 VA: 0x7596754280
	private static extern Int32 criFsLoader_Create(out IntPtr loader) { }
	// RVA: 0x413c45c VA: 0x759675445c
	private static extern Int32 criFsLoader_Destroy(IntPtr loader) { }
	// RVA: 0x413c59c VA: 0x759675459c
	private static extern Int32 criFsLoader_Load(IntPtr loader, IntPtr binder, String path, Int64 offset, Int64 load_size, IntPtr buffer, Int64 buffer_size) { }
	// RVA: 0x413c740 VA: 0x7596754740
	private static extern Int32 criFsLoader_LoadById(IntPtr loader, IntPtr binder, Int32 id, Int64 offset, Int64 load_size, IntPtr buffer, Int64 buffer_size) { }
	// RVA: 0x413ccd4 VA: 0x7596754cd4
	private static extern Int32 criFsLoader_Stop(IntPtr loader) { }
	// RVA: 0x413ce14 VA: 0x7596754e14
	private static extern Int32 criFsLoader_GetStatus(IntPtr loader, out Status status) { }
	// RVA: 0x413cf18 VA: 0x7596754f18
	private static extern Int32 criFsLoader_SetReadUnitSize(IntPtr loader, Int64 unit_size) { }
	// RVA: 0x413c8c8 VA: 0x75967548c8
	private static extern Int32 criFsLoader_LoadWithoutDecompression(IntPtr loader, IntPtr binder, String path, Int64 offset, Int64 load_size, IntPtr buffer, Int64 buffer_size) { }
	// RVA: 0x413ca6c VA: 0x7596754a6c
	private static extern Int32 criFsLoader_LoadWithoutDecompressionById(IntPtr loader, IntPtr binder, Int32 id, Int64 offset, Int64 load_size, IntPtr buffer, Int64 buffer_size) { }
	// RVA: 0x413cbbc VA: 0x7596754bbc
	private static extern Int32 criFsLoader_DecompressData(IntPtr loader, IntPtr src, Int64 src_size, IntPtr dst, Int64 dst_size) { }
}
```