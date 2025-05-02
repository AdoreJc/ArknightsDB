# CriAtomExAcbLoader

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Methods

- `Status GetStatus()`

- `CriAtomExAcb MoveAcb()`

- `Void Dispose(Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExAcbLoader : CriDisposable
{
	private IntPtr handle; // 0x20
	private Nullable`1 gch; // 0x28


	// RVA: 0x4110644 VA: 0x7596728644
	public static CriAtomExAcbLoader LoadAcbFileAsync(CriFsBinder binder, String acbPath, String awbPath, Boolean loadAwbOnMemory) { }
	// RVA: 0x4110c14 VA: 0x7596728c14
	public static CriAtomExAcbLoader LoadAcbDataAsync(Byte[] acbData, CriFsBinder awbBinder, String awbPath, Boolean loadAwbOnMemory) { }
	// RVA: 0x4125f0c VA: 0x759673df0c
	public static CriAtomExAcbLoader LoadAcbDataAsync(IntPtr acbData, Int32 dataSize, CriFsBinder awbBinder, String awbPath, Boolean loadAwbOnMemory) { }
	// RVA: 0x4110774 VA: 0x7596728774
	public Status GetStatus() { }
	// RVA: 0x411077c VA: 0x759672877c
	public CriAtomExAcb MoveAcb() { }
	// RVA: 0x4126138 VA: 0x759673e138
	public override Void Dispose() { }
	// RVA: 0x412619c VA: 0x759673e19c
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x4125d2c VA: 0x759673dd2c
	private Void .ctor(IntPtr handle, Nullable`1 dataHandle) { }
	// RVA: 0x41262b8 VA: 0x759673e2b8
	protected override Void Finalize() { }
	// RVA: 0x4125b4c VA: 0x759673db4c
	private static extern IntPtr criAtomExAcbLoader_Create(in LoaderConfig config) { }
	// RVA: 0x4125cb0 VA: 0x759673dcb0
	private static extern Void criAtomExAcbLoader_Destroy(IntPtr acb_loader) { }
	// RVA: 0x4125bd0 VA: 0x759673dbd0
	private static extern Boolean criAtomExAcbLoader_LoadAcbFileAsync(IntPtr acb_loader, IntPtr acb_binder, String acb_path, IntPtr awb_binder, String awb_path) { }
	// RVA: 0x4125e40 VA: 0x759673de40
	private static extern Boolean criAtomExAcbLoader_LoadAcbDataAsync(IntPtr acb_loader, IntPtr acb_data, Int32 acb_size, IntPtr awb_binder, String awb_path) { }
	// RVA: 0x4126040 VA: 0x759673e040
	private static extern Status criAtomExAcbLoader_GetStatus(IntPtr acb_loader) { }
	// RVA: 0x4126350 VA: 0x759673e350
	private static extern Boolean criAtomExAcbLoader_WaitForCompletion(IntPtr acb_loader) { }
	// RVA: 0x41260bc VA: 0x759673e0bc
	private static extern IntPtr criAtomExAcbLoader_MoveAcbHandle(IntPtr acb_loader) { }
}
```