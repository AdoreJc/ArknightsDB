# Logger

**Namespace:** `UnityEngine`


## Fields

- `ILogHandler <logHandler>k__BackingField`

- `Boolean <logEnabled>k__BackingField`

- `LogType <filterLogType>k__BackingField`


## Properties

- `ILogHandler logHandler`

- `Boolean logEnabled`

- `LogType filterLogType`


## Methods

- `ILogHandler get_logHandler()`

- `Void set_logHandler(ILogHandler)`

- `Boolean get_logEnabled()`

- `Void set_logEnabled(Boolean)`

- `LogType get_filterLogType()`

- `Void set_filterLogType(LogType)`

- `Boolean IsLogTypeAllowed(LogType)`

- `Void Log(LogType, Object)`

- `Void Log(LogType, Object, Object)`

- `Void LogError(String, Object)`

- `Void LogException(Exception, Object)`

- `Void LogFormat(LogType, String, Object[])`

- `Void LogFormat(LogType, Object, String, Object[])`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Logger : ILogger, ILogHandler
{
	private ILogHandler <logHandler>k__BackingField; // 0x10
	private Boolean <logEnabled>k__BackingField; // 0x18
	private LogType <filterLogType>k__BackingField; // 0x1c

	public ILogHandler logHandler { get; set; }
	public Boolean logEnabled { get; set; }
	public LogType filterLogType { get; set; }

	// RVA: 0x687433c VA: 0x7598e8c33c
	public Void .ctor(ILogHandler logHandler) { }
	// RVA: 0x6874380 VA: 0x7598e8c380
	public ILogHandler get_logHandler() { }
	// RVA: 0x6874388 VA: 0x7598e8c388
	public Void set_logHandler(ILogHandler value) { }
	// RVA: 0x6874390 VA: 0x7598e8c390
	public Boolean get_logEnabled() { }
	// RVA: 0x6874398 VA: 0x7598e8c398
	public Void set_logEnabled(Boolean value) { }
	// RVA: 0x68743a4 VA: 0x7598e8c3a4
	public LogType get_filterLogType() { }
	// RVA: 0x68743ac VA: 0x7598e8c3ac
	public Void set_filterLogType(LogType value) { }
	// RVA: 0x68743b4 VA: 0x7598e8c3b4
	public Boolean IsLogTypeAllowed(LogType logType) { }
	// RVA: 0x68743f0 VA: 0x7598e8c3f0
	private static String GetString(Object message) { }
	// RVA: 0x6874510 VA: 0x7598e8c510
	public Void Log(LogType logType, Object message) { }
	// RVA: 0x6874690 VA: 0x7598e8c690
	public Void Log(LogType logType, Object message, Object context) { }
	// RVA: 0x6874814 VA: 0x7598e8c814
	public Void LogError(String tag, Object message) { }
	// RVA: 0x68749bc VA: 0x7598e8c9bc
	public Void LogException(Exception exception, Object context) { }
	// RVA: 0x6874a90 VA: 0x7598e8ca90
	public Void LogFormat(LogType logType, String format, Object[] args) { }
	// RVA: 0x6874b88 VA: 0x7598e8cb88
	public Void LogFormat(LogType logType, Object context, String format, Object[] args) { }
}
```