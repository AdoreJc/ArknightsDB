# AutoCampConfigModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String stageId`

- `Status status`

- `AutoBattleOnly autoBattleOnly`

- `EnableFastBattle enableFastBattle`

- `Int32 fastTktCount`


## Methods

- `Void ReloadData(String)`

- `Void _ReloadAutoBattleOnlyModel(Boolean, FastBattleLockAlert, Boolean, LocalCache, Boolean)`

- `Void _ReloadEnableFastBattleModel(LocalCache, Boolean)`

- `Boolean CheckIfAutoBattle()`

- `Boolean CheckIfFastBattle()`

- `Void ToggleAutoBattle()`

- `Void ToggleFastBattle()`

- `Boolean CheckIfAutoBattleUnlocked(out)`

- `Boolean CheckIfFastBattleUnlocked(out)`

- `Boolean CheckIfFastBattleSysOpen()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class AutoCampConfigModel : IHotfixable
{
	public String stageId; // 0x10
	public Status status; // 0x18
	public AutoBattleOnly autoBattleOnly; // 0x1c
	public EnableFastBattle enableFastBattle; // 0x24
	public Int32 fastTktCount; // 0x28
	public List`1 fastTktInfo; // 0x30
	private static DelegateBridge __Hotfix0_ReloadData; // 0x0
	private static DelegateBridge __Hotfix0__ReloadAutoBattleOnlyModel; // 0x8
	private static DelegateBridge __Hotfix0__ReloadEnableFastBattleModel; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfAutoBattle; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfFastBattle; // 0x20
	private static DelegateBridge __Hotfix0_ToggleAutoBattle; // 0x28
	private static DelegateBridge __Hotfix0_ToggleFastBattle; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfAutoBattleUnlocked; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfFastBattleUnlocked; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfFastBattleSysOpen; // 0x48
	private static DelegateBridge __Hotfix0__GetLockToastByFastCampLockType; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2dddbf0 VA: 0x75953f5bf0
	public Void ReloadData(String targetStageId) { }
	// RVA: 0x2dde038 VA: 0x75953f6038
	private Void _ReloadAutoBattleOnlyModel(Boolean isFastSysOpen, FastBattleLockAlert fastLockType, Boolean hasBattleLog, LocalCache stageCache, Boolean isStageChanged) { }
	// RVA: 0x2dde118 VA: 0x75953f6118
	private Void _ReloadEnableFastBattleModel(LocalCache stageCache, Boolean isStageChanged) { }
	// RVA: 0x2dde1b8 VA: 0x75953f61b8
	public Boolean CheckIfAutoBattle() { }
	// RVA: 0x2dde2c4 VA: 0x75953f62c4
	public Boolean CheckIfFastBattle() { }
	// RVA: 0x2dde348 VA: 0x75953f6348
	public Void ToggleAutoBattle() { }
	// RVA: 0x2dde404 VA: 0x75953f6404
	public Void ToggleFastBattle() { }
	// RVA: 0x2dde488 VA: 0x75953f6488
	public Boolean CheckIfAutoBattleUnlocked(out String lockAlert) { }
	// RVA: 0x2dde594 VA: 0x75953f6594
	public Boolean CheckIfFastBattleUnlocked(out String lockAlert) { }
	// RVA: 0x2dde7c4 VA: 0x75953f67c4
	public Boolean CheckIfFastBattleSysOpen() { }
	// RVA: 0x2dde66c VA: 0x75953f666c
	private static String _GetLockToastByFastCampLockType(FastBattleLockAlert type) { }
	// RVA: 0x2dddf74 VA: 0x75953f5f74
	public Void .ctor() { }
}
```