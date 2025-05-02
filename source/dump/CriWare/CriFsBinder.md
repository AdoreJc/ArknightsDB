# CriFsBinder

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Properties

- `IntPtr nativeHandle`


## Methods

- `Void Dispose(Boolean)`

- `UInt32 BindCpk(CriFsBinder, String)`

- `UInt32 BindDirectory(CriFsBinder, String)`

- `UInt32 BindFile(CriFsBinder, String)`

- `UInt32 BindFileSection(CriFsBinder, String, UInt64, Int32, String)`

- `Int64 GetFileSize(String)`

- `Int64 GetFileSize(Int32)`

- `Boolean GetContentsFileInfo(String, out)`

- `Boolean GetContentsFileInfo(Int32, out)`

- `IntPtr get_nativeHandle()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsBinder : CriDisposable
{
	private IntPtr handle; // 0x20

	public IntPtr nativeHandle { get; }

	// RVA: 0x413da60 VA: 0x7596755a60
	public Void .ctor() { }
	// RVA: 0x413dc34 VA: 0x7596755c34
	public override Void Dispose() { }
	// RVA: 0x413dc98 VA: 0x7596755c98
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x413ddb4 VA: 0x7596755db4
	public UInt32 BindCpk(CriFsBinder srcBinder, String path) { }
	// RVA: 0x413df44 VA: 0x7596755f44
	public UInt32 BindDirectory(CriFsBinder srcBinder, String path) { }
	// RVA: 0x413e0d4 VA: 0x75967560d4
	public UInt32 BindFile(CriFsBinder srcBinder, String path) { }
	// RVA: 0x413e238 VA: 0x7596756238
	public UInt32 BindFileSection(CriFsBinder srcBinder, String path, UInt64 offset, Int32 size, String sectionName) { }
	// RVA: 0x413e430 VA: 0x7596756430
	public static Void Unbind(UInt32 bindId) { }
	// RVA: 0x413e514 VA: 0x7596756514
	public static Status GetStatus(UInt32 bindId) { }
	// RVA: 0x413e618 VA: 0x7596756618
	public Int64 GetFileSize(String path) { }
	// RVA: 0x413e758 VA: 0x7596756758
	public Int64 GetFileSize(Int32 id) { }
	// RVA: 0x413e87c VA: 0x759675687c
	public Boolean GetContentsFileInfo(String path, out ContentsFileInfo info) { }
	// RVA: 0x413ed98 VA: 0x7596756d98
	public Boolean GetContentsFileInfo(Int32 id, out ContentsFileInfo info) { }
	// RVA: 0x413f068 VA: 0x7596757068
	public static Boolean GetContentsFileInfoByIndex(UInt32 bindId, Int32 index, Int32 numFiles, out ContentsFileInfo[] info) { }
	// RVA: 0x413f4c4 VA: 0x75967574c4
	public static Int32 GetNumContentsFiles(UInt32 bindId) { }
	// RVA: 0x413f544 VA: 0x7596757544
	public static Void SetPriority(UInt32 bindId, Int32 priority) { }
	// RVA: 0x413f644 VA: 0x7596757644
	public IntPtr get_nativeHandle() { }
	// RVA: 0x413f64c VA: 0x759675764c
	protected override Void Finalize() { }
	// RVA: 0x413dbb8 VA: 0x7596755bb8
	private static extern UInt32 criFsBinder_Create(out IntPtr binder) { }
	// RVA: 0x413dd38 VA: 0x7596755d38
	private static extern UInt32 criFsBinder_Destroy(IntPtr binder) { }
	// RVA: 0x413de74 VA: 0x7596755e74
	private static extern UInt32 criFsBinder_BindCpk(IntPtr binder, IntPtr srcBinder, String path, IntPtr work, Int32 worksize, out UInt32 bindId) { }
	// RVA: 0x413e004 VA: 0x7596756004
	private static extern UInt32 criFsBinder_BindDirectory(IntPtr binder, IntPtr srcBinder, String path, IntPtr work, Int32 worksize, out UInt32 bindId) { }
	// RVA: 0x413e168 VA: 0x7596756168
	private static extern UInt32 criFsBinder_BindFile(IntPtr binder, IntPtr srcBinder, String path, IntPtr work, Int32 worksize, out UInt32 bindId) { }
	// RVA: 0x413e324 VA: 0x7596756324
	private static extern UInt32 criFsBinder_BindFileSection(IntPtr binder, IntPtr srcBinder, String path, UInt64 offset, Int32 size, String sectionName, IntPtr work, Int32 worksize, out UInt32 bindId) { }
	// RVA: 0x413e498 VA: 0x7596756498
	private static extern Int32 criFsBinder_Unbind(UInt32 bindId) { }
	// RVA: 0x413e594 VA: 0x7596756594
	private static extern Int32 criFsBinder_GetStatus(UInt32 bindId, out Status status) { }
	// RVA: 0x413e6a8 VA: 0x75967566a8
	private static extern Int32 criFsBinder_GetFileSize(IntPtr binder, String path, out Int64 size) { }
	// RVA: 0x413e7e8 VA: 0x75967567e8
	private static extern Int32 criFsBinder_GetFileSizeById(IntPtr binder, Int32 id, out Int64 size) { }
	// RVA: 0x413f5c0 VA: 0x75967575c0
	private static extern Int32 criFsBinder_SetPriority(UInt32 bindId, Int32 priority) { }
	// RVA: 0x413eab8 VA: 0x7596756ab8
	private static extern Int32 criFsBinder_GetContentsFileInfo(IntPtr binder, String path, IntPtr info) { }
	// RVA: 0x413efd4 VA: 0x7596756fd4
	private static extern Int32 criFsBinder_GetContentsFileInfoById(IntPtr binder, Int32 id, IntPtr info) { }
	// RVA: 0x413f428 VA: 0x7596757428
	private static extern Int32 criFsBinder_GetContentsFileInfoByIndex(UInt32 id, Int32 index, IntPtr info, Int32 num) { }
	// RVA: 0x413f4c8 VA: 0x75967574c8
	private static extern Int32 CRIWARE2667177F(UInt32 id) { }
}
```