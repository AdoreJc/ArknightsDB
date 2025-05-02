# CriFsWebInstaller

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Methods

- `Void Copy(String, String)`

- `Void Stop()`

- `StatusInfo GetStatusInfo()`

- `Boolean GetCRC32(out)`

- `Void Dispose(Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsWebInstaller : CriDisposable
{
	private static Boolean <isInitialized>k__BackingField; // 0x0
	private static Boolean <isCrcEnabled>k__BackingField; // 0x1
	public const Int32 InvalidHttpStatusCode; // 0x0
	public const Int64 InvalidContentsSize; // 0x0
	private IntPtr handle; // 0x20

	public static Boolean isInitialized { get; set; }
	public static Boolean isCrcEnabled { get; set; }
	public static ModuleConfig defaultModuleConfig { get; }

	// RVA: 0x4142fb0 VA: 0x759675afb0
	public static Boolean get_isInitialized() { }
	// RVA: 0x4142ff8 VA: 0x759675aff8
	private static Void set_isInitialized(Boolean value) { }
	// RVA: 0x4143044 VA: 0x759675b044
	public static Boolean get_isCrcEnabled() { }
	// RVA: 0x414308c VA: 0x759675b08c
	private static Void set_isCrcEnabled(Boolean value) { }
	// RVA: 0x41430d8 VA: 0x759675b0d8
	public static ModuleConfig get_defaultModuleConfig() { }
	// RVA: 0x41408ec VA: 0x75967588ec
	public Void .ctor() { }
	// RVA: 0x41431d8 VA: 0x759675b1d8
	protected override Void Finalize() { }
	// RVA: 0x414335c VA: 0x759675b35c
	public override Void Dispose() { }
	// RVA: 0x41409f4 VA: 0x75967589f4
	public Void Copy(String url, String dstPath) { }
	// RVA: 0x4140748 VA: 0x7596758748
	public Void Stop() { }
	// RVA: 0x4140b9c VA: 0x7596758b9c
	public StatusInfo GetStatusInfo() { }
	// RVA: 0x4140c4c VA: 0x7596758c4c
	public Boolean GetCRC32(out UInt32 ret_val) { }
	// RVA: 0x4143608 VA: 0x759675b608
	public static Void InitializeModule(ModuleConfig config) { }
	// RVA: 0x41438c4 VA: 0x759675b8c4
	private static Type GetCriFsWebInstallerCurlExpansionClass() { }
	// RVA: 0x4143a28 VA: 0x759675ba28
	public static Void FinalizeModule() { }
	// RVA: 0x4142eb0 VA: 0x759675aeb0
	public static Void ExecuteMain() { }
	// RVA: 0x4143c28 VA: 0x759675bc28
	public static Boolean SetRequestHeader(String field, String value) { }
	// RVA: 0x4143270 VA: 0x759675b270
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x4143958 VA: 0x759675b958
	private static extern Int32 criFsWebInstaller_Initialize(in ModuleConfig config) { }
	// RVA: 0x4143b58 VA: 0x759675bb58
	private static extern Int32 criFsWebInstaller_Finalize() { }
	// RVA: 0x4143bc0 VA: 0x759675bbc0
	private static extern Int32 criFsWebInstaller_ExecuteMain() { }
	// RVA: 0x414315c VA: 0x759675b15c
	private static extern Int32 criFsWebInstaller_Create(out IntPtr installer) { }
	// RVA: 0x4143cf4 VA: 0x759675bcf4
	private static extern Int32 criFsWebInstaller_Destroy(IntPtr installer) { }
	// RVA: 0x41433c0 VA: 0x759675b3c0
	private static extern Int32 criFsWebInstaller_Copy(IntPtr installer, String url, String dstPath) { }
	// RVA: 0x4143484 VA: 0x759675b484
	private static extern Int32 criFsWebInstaller_Stop(IntPtr installer) { }
	// RVA: 0x4143500 VA: 0x759675b500
	private static extern Int32 criFsWebInstaller_GetStatusInfo(IntPtr installer, out StatusInfo status) { }
	// RVA: 0x4143584 VA: 0x759675b584
	private static extern Int32 criFsWebInstaller_GetCRC32(IntPtr installer, out UInt32 crc32) { }
	// RVA: 0x4143c40 VA: 0x759675bc40
	private static extern Int32 criFsWebInstaller_SetRequestHeader(String field, String value) { }
}
```