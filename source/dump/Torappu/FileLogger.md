# FileLogger

**Namespace:** `Torappu`


## Fields

- `String <path>k__BackingField`


## Properties

- `String path`


## Methods

- `Void Dispose()`

- `Void Log(LogLevel, String)`

- `Boolean CheckLogLevel(LogLevel)`

- `String get_path()`

- `Void set_path(String)`

- `Void _OnCatchLog(String, String, LogType)`

- `String _GenFilePath(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FileLogger : IDisposable, IHotfixable
{
	private readonly Options m_options; // 0x10
	private readonly StreamWriter m_streamWriter; // 0x18
	private String <path>k__BackingField; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge __Hotfix0_Log; // 0x10
	private static DelegateBridge __Hotfix0_CheckLogLevel; // 0x18
	private static DelegateBridge __Hotfix0_get_path; // 0x20
	private static DelegateBridge __Hotfix0_set_path; // 0x28
	private static DelegateBridge __Hotfix0__OnCatchLog; // 0x30
	private static DelegateBridge __Hotfix0__GenFilePath; // 0x38
	private static DelegateBridge __Hotfix0_GetLogDirPath; // 0x40

	public String path { get; set; }

	// RVA: 0x2f44434 VA: 0x759555c434
	public Void .ctor(Options options, String nameFormat) { }
	// RVA: 0x2f4478c VA: 0x759555c78c
	public Void Dispose() { }
	// RVA: 0x2f448d0 VA: 0x759555c8d0
	public Void Log(LogLevel level, String message) { }
	// RVA: 0x2f442f8 VA: 0x759555c2f8
	public Boolean CheckLogLevel(LogLevel level) { }
	// RVA: 0x2f44230 VA: 0x759555c230
	public String get_path() { }
	// RVA: 0x2f468d4 VA: 0x759555e8d4
	private Void set_path(String value) { }
	// RVA: 0x2f46958 VA: 0x759555e958
	private Void _OnCatchLog(String logString, String stackTrace, LogType type) { }
	// RVA: 0x2f467b4 VA: 0x759555e7b4
	private String _GenFilePath(String format) { }
	// RVA: 0x2f46a10 VA: 0x759555ea10
	public static String GetLogDirPath(String dir) { }
}
```