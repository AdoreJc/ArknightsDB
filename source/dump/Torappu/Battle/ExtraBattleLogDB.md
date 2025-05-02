# ExtraBattleLogDB

**Namespace:** `Torappu.Battle`


## Methods

- `Int32 GetTypeTaskCount(Int32)`

- `String GetTaskLogStr(ExtraLogType, Int32)`

- `Void FetchLoggerIds(List`1, ExtraLogType, String)`

- `Void FetchLoggerIds(List`1, ExtraLogType, String, String, String)`

- `Void FetchLoggerIds(List`1, ExtraLogType, String, String, String, String)`

- `Void FetchLoggerIds(List`1, ExtraLogType, String, String, String, List`1, String, String, String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ExtraBattleLogDB : SimpleKVTable`2
{
	private List`1 m_allTaskLoggers; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetTypeTaskCount; // 0x8
	private static DelegateBridge __Hotfix0_GetTaskLogStr; // 0x10
	private static DelegateBridge __Hotfix0_FetchLoggerIds; // 0x18
	private static DelegateBridge __Hotfix1_FetchLoggerIds; // 0x20
	private static DelegateBridge __Hotfix2_FetchLoggerIds; // 0x28
	private static DelegateBridge __Hotfix3_FetchLoggerIds; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1c5614c VA: 0x759426e14c
	protected override Void OnInit() { }
	// RVA: 0x1c565c4 VA: 0x759426e5c4
	public Int32 GetTypeTaskCount(Int32 type) { }
	// RVA: 0x1c566b4 VA: 0x759426e6b4
	public String GetTaskLogStr(ExtraLogType logType, Int32 index) { }
	// RVA: 0x1c56a70 VA: 0x759426ea70
	public Void FetchLoggerIds(List`1 ids, ExtraLogType logType, String sourceId) { }
	// RVA: 0x1c56c64 VA: 0x759426ec64
	public Void FetchLoggerIds(List`1 ids, ExtraLogType logType, String sourceId, String sourceMode, String abilityName) { }
	// RVA: 0x1c56ec0 VA: 0x759426eec0
	public Void FetchLoggerIds(List`1 ids, ExtraLogType logType, String sourceId, String sourceMode, String projectileName, String abilityName) { }
	// RVA: 0x1c57148 VA: 0x759426f148
	public Void FetchLoggerIds(List`1 ids, ExtraLogType logType, String sourceId, String sourceMode, String enemyId, List`1 enemyTag, String enemyApplyWay, String projectileName, String abilityName, String enemyLevelType) { }
	// RVA: 0x1c57600 VA: 0x759426f600
	public Void .ctor() { }
}
```