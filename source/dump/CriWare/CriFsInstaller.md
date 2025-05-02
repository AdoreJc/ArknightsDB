# CriFsInstaller

**Namespace:** `CriWare`


## Fields

- `GCHandle installBufferGch`

- `IntPtr handle`


## Methods

- `Void Dispose(Boolean)`

- `Void Copy(CriFsBinder, String, String, Int32)`

- `Void Stop()`

- `Status GetStatus()`

- `Single GetProgress()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsInstaller : CriDisposable
{
	private Byte[] installBuffer; // 0x20
	private GCHandle installBufferGch; // 0x28
	private IntPtr handle; // 0x30


	// RVA: 0x413d034 VA: 0x7596755034
	public Void .ctor() { }
	// RVA: 0x413d214 VA: 0x7596755214
	public override Void Dispose() { }
	// RVA: 0x413d278 VA: 0x7596755278
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x413d3d8 VA: 0x75967553d8
	public Void Copy(CriFsBinder binder, String srcPath, String dstPath, Int32 installBufferSize) { }
	// RVA: 0x413d670 VA: 0x7596755670
	public Void Stop() { }
	// RVA: 0x413d758 VA: 0x7596755758
	public Status GetStatus() { }
	// RVA: 0x413d85c VA: 0x759675585c
	public Single GetProgress() { }
	// RVA: 0x413d95c VA: 0x759675595c
	public static Void ExecuteMain() { }
	// RVA: 0x413d9c8 VA: 0x75967559c8
	protected override Void Finalize() { }
	// RVA: 0x413d960 VA: 0x7596755960
	private static extern Int32 criFsInstaller_ExecuteMain() { }
	// RVA: 0x413d190 VA: 0x7596755190
	private static extern Int32 criFsInstaller_Create(out IntPtr installer, CopyPolicy option) { }
	// RVA: 0x413d35c VA: 0x759675535c
	private static extern Int32 criFsInstaller_Destroy(IntPtr installer) { }
	// RVA: 0x413d58c VA: 0x759675558c
	private static extern Int32 criFsInstaller_Copy(IntPtr installer, IntPtr binder, String src_path, String dst_path, IntPtr buffer, Int64 buffer_size) { }
	// RVA: 0x413d6dc VA: 0x75967556dc
	private static extern Int32 criFsInstaller_Stop(IntPtr installer) { }
	// RVA: 0x413d7d8 VA: 0x75967557d8
	private static extern Int32 criFsInstaller_GetStatus(IntPtr installer, out Status status) { }
	// RVA: 0x413d8d8 VA: 0x75967558d8
	private static extern Int32 criFsInstaller_GetProgress(IntPtr installer, out Single progress) { }
}
```