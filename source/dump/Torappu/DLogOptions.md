# DLogOptions

**Namespace:** `Torappu`


## Fields

- `Boolean _logInfo`

- `Boolean _logWarning`

- `Boolean _logError`

- `Boolean _enableAllForEditorMode`

- `Boolean _enableAllForDevelopmentBuild`


## Properties

- `Boolean LogInfo`

- `Boolean LogWarnning`

- `Boolean LogError`

- `Boolean EnableAllForDevelopmentBuild`


## Methods

- `Boolean get_LogInfo()`

- `Void set_LogInfo(Boolean)`

- `Boolean get_LogWarnning()`

- `Void set_LogWarnning(Boolean)`

- `Boolean get_LogError()`

- `Void set_LogError(Boolean)`

- `Boolean get_EnableAllForDevelopmentBuild()`

- `Void set_EnableAllForDevelopmentBuild(Boolean)`

- `Void DoApply()`

- `Void RefreshSetting()`

- `Void EnableLogsWithOptions()`

- `Void EnableAllLogs()`

- `LogLevel GetLogLevelFromOptions()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DLogOptions : SingletonScriptableObject`1
{
	private Boolean _logInfo; // 0x18
	private Boolean _logWarning; // 0x19
	private Boolean _logError; // 0x1a
	private Boolean _enableAllForEditorMode; // 0x1b
	private Boolean _enableAllForDevelopmentBuild; // 0x1c

	public Boolean LogInfo { get; set; }
	public Boolean LogWarnning { get; set; }
	public Boolean LogError { get; set; }
	public Boolean EnableAllForDevelopmentBuild { get; set; }

	// RVA: 0x34ff5e4 VA: 0x7595b175e4
	public Boolean get_LogInfo() { }
	// RVA: 0x34ff5ec VA: 0x7595b175ec
	public Void set_LogInfo(Boolean value) { }
	// RVA: 0x34ff5f8 VA: 0x7595b175f8
	public Boolean get_LogWarnning() { }
	// RVA: 0x34ff600 VA: 0x7595b17600
	public Void set_LogWarnning(Boolean value) { }
	// RVA: 0x34ff60c VA: 0x7595b1760c
	public Boolean get_LogError() { }
	// RVA: 0x34ff614 VA: 0x7595b17614
	public Void set_LogError(Boolean value) { }
	// RVA: 0x34ff620 VA: 0x7595b17620
	public Boolean get_EnableAllForDevelopmentBuild() { }
	// RVA: 0x34ff628 VA: 0x7595b17628
	public Void set_EnableAllForDevelopmentBuild(Boolean value) { }
	// RVA: 0x34ff634 VA: 0x7595b17634
	protected override Void OnEnable() { }
	// RVA: 0x34ff6f0 VA: 0x7595b176f0
	protected override Void OnDisable() { }
	// RVA: 0x34ff6c4 VA: 0x7595b176c4
	private Void DoApply() { }
	// RVA: 0x34ff8d8 VA: 0x7595b178d8
	public Void RefreshSetting() { }
	// RVA: 0x34ff814 VA: 0x7595b17814
	private Void EnableLogsWithOptions() { }
	// RVA: 0x34ff738 VA: 0x7595b17738
	private Void EnableAllLogs() { }
	// RVA: 0x34ff8dc VA: 0x7595b178dc
	private LogLevel GetLogLevelFromOptions() { }
	// RVA: 0x34ff7c4 VA: 0x7595b177c4
	private static Boolean IsDevelopmentBuild() { }
	// RVA: 0x34ff6bc VA: 0x7595b176bc
	private static Boolean IsEditorMode() { }
	// RVA: 0x34ff918 VA: 0x7595b17918
	public Void .ctor() { }
}
```