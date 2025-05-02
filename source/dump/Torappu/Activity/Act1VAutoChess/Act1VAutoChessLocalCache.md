# Act1VAutoChessLocalCache

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `String GetLastSelectModeId(String)`

- `Void SaveLastSelectModeId(String, String)`

- `Boolean GetBattleSpeedLevel(String)`

- `Void SaveBattleSpeedLevel(String, Boolean)`

- `Boolean GetGameGoldLeftIgnore(String, String)`

- `Void SaveGameGoldLeftIgnore(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_GetLastSelectModeId; // 0x28
	private static DelegateBridge __Hotfix0_SaveLastSelectModeId; // 0x30
	private static DelegateBridge __Hotfix0_GetBattleSpeedLevel; // 0x38
	private static DelegateBridge __Hotfix0_SaveBattleSpeedLevel; // 0x40
	private static DelegateBridge __Hotfix0_GetGameGoldLeftIgnore; // 0x48
	private static DelegateBridge __Hotfix0_SaveGameGoldLeftIgnore; // 0x50


	// RVA: 0x335fea8 VA: 0x7595977ea8
	private Void .ctor() { }
	// RVA: 0x335ff38 VA: 0x7595977f38
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x336009c VA: 0x759597809c
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x336027c VA: 0x759597827c
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x33603d4 VA: 0x75959783d4
	private Void _SaveData(ActData data) { }
	// RVA: 0x3360480 VA: 0x7595978480
	public String GetLastSelectModeId(String actId) { }
	// RVA: 0x3360540 VA: 0x7595978540
	public Void SaveLastSelectModeId(String actId, String lastSelectModeId) { }
	// RVA: 0x3360614 VA: 0x7595978614
	public Boolean GetBattleSpeedLevel(String actId) { }
	// RVA: 0x33606c0 VA: 0x75959786c0
	public Void SaveBattleSpeedLevel(String actId, Boolean enableBattleSpeedStandard) { }
	// RVA: 0x336078c VA: 0x759597878c
	public Boolean GetGameGoldLeftIgnore(String actId, String gameTs) { }
	// RVA: 0x336084c VA: 0x759597884c
	public Void SaveGameGoldLeftIgnore(String actId, String gameTs) { }
}
```