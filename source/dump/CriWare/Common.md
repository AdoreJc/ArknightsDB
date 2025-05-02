# Common

**Namespace:** `CriWare`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class Common
{
	private const String scriptVersionString; // 0x0
	public const Boolean supportsCriFsInstaller; // 0x0
	public const Boolean supportsCriFsWebInstaller; // 0x0
	public const String pluginName; // 0x0
	public const CallingConvention pluginCallingConvention; // 0x0
	public const String engineName; // 0x0
	private static GameObject _managerObject; // 0x0

	public static String streamingAssetsPath { get; }
	public static String installTargetPath { get; }
	public static String installCachePath { get; }
	public static GameObject managerObject { get; }

	// RVA: 0x41472dc VA: 0x759675f2dc
	public static String get_streamingAssetsPath() { }
	// RVA: 0x414824c VA: 0x759676024c
	public static String get_installTargetPath() { }
	// RVA: 0x4148254 VA: 0x7596760254
	public static String get_installCachePath() { }
	// RVA: 0x4147258 VA: 0x759675f258
	public static Boolean IsStreamingAssetsPath(String path) { }
	// RVA: 0x41427f0 VA: 0x759675a7f0
	public static GameObject get_managerObject() { }
	// RVA: 0x4148278 VA: 0x7596760278
	public static String GetScriptVersionString() { }
	// RVA: 0x41482b8 VA: 0x75967602b8
	public static Int32 GetBinaryVersionNumber() { }
	// RVA: 0x4148324 VA: 0x7596760324
	public static Int32 GetRequiredBinaryVersionNumber() { }
	// RVA: 0x4148330 VA: 0x7596760330
	public static Boolean CheckBinaryVersionCompatibility() { }
	// RVA: 0x41483b4 VA: 0x75967603b4
	public static UInt32 GetFsMemoryUsage() { }
	// RVA: 0x4148400 VA: 0x7596760400
	public static UInt32 GetAtomMemoryUsage() { }
	// RVA: 0x4148450 VA: 0x7596760450
	public static UInt32 GetManaMemoryUsage() { }
	// RVA: 0x414849c VA: 0x759676049c
	public static CpuUsage GetAtomCpuUsage() { }
	// RVA: 0x41482bc VA: 0x75967602bc
	public static extern Int32 CRIWARE0124771C() { }
	// RVA: 0x41445b8 VA: 0x759675c5b8
	public static extern Void criWareUnity_SetRenderingEventOffsetForMana(Int32 offset) { }
	// RVA: 0x41484ec VA: 0x75967604ec
	public Void .ctor() { }
}
```