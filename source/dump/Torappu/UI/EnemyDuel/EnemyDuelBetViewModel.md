# EnemyDuelBetViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `EnemyDuelModeType modeType`

- `Int32 currRoundNum`

- `Int32 boomFxRoundNum`

- `Boolean canSkip`

- `Int32 totalBetTime`

- `Int32 privateBetTime`

- `Int32 minWinStreakCount`

- `EnemyDuelTopBarViewModel topBarViewModel`

- `String selfPlayerId`

- `EnemyDuelOperationModeViewModel operationModeViewModel`

- `EnemyDuelStandModeViewModel standModeViewModel`

- `Int64 betEndTs`

- `Boolean isSurvive`

- `EnemyDuelBetSelectStatus selectStatus`

- `Boolean showEnemyDetailPanel`

- `Int32 totalPlayerCount`

- `Int32 survivePlayerCount`

- `Int32 loadSeqNum`

- `Int32 refreshPlayerListSeqNum`


## Methods

- `Void LoadData()`

- `Void UpdateData()`

- `EnemyDuelBetSelectStatus _GetSelectStatus(EnemyDuelChoiceSide, EnemyDuelChoiceType)`

- `EnemyDuelBetParams GenerateBetParams(EnemyDuelBetSelectStatus)`

- `Boolean CanSelect(EnemyDuelBetSelectStatus)`

- `Boolean SetEnemyDetailPanelShowStatus(Boolean)`

- `Void ToggleEnemyDetailPanelShowStatus()`

- `Void SetEmoticonDisabledStatus(Boolean)`

- `Void RefreshPlayerList()`

- `Void ClearPlayerList()`

- `Int32 _SortPlayerListByBetTs(EnemyDuelBetPlayerViewModel, EnemyDuelBetPlayerViewModel)`

- `Void _CalculatePlayerRank()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetViewModel : IHotfixable
{
	public String actId; // 0x10
	public EnemyDuelModeType modeType; // 0x18
	public Int32 currRoundNum; // 0x1c
	public Int32 boomFxRoundNum; // 0x20
	public Boolean canSkip; // 0x24
	public Int32 totalBetTime; // 0x28
	public Int32 privateBetTime; // 0x2c
	public Int32 minWinStreakCount; // 0x30
	public EnemyDuelTopBarViewModel topBarViewModel; // 0x38
	public String selfPlayerId; // 0x40
	public EnemyDuelOperationModeViewModel operationModeViewModel; // 0x48
	public EnemyDuelStandModeViewModel standModeViewModel; // 0x50
	public List`1 playerList; // 0x58
	public Dictionary`2 playerDict; // 0x60
	public List`1 playerListLeft; // 0x68
	public List`1 playerListRight; // 0x70
	public List`1 enemyListLeft; // 0x78
	public List`1 enemyListRight; // 0x80
	public Int64 betEndTs; // 0x88
	public Boolean isSurvive; // 0x90
	public EnemyDuelBetSelectStatus selectStatus; // 0x94
	public Boolean showEnemyDetailPanel; // 0x98
	public Int32 totalPlayerCount; // 0x9c
	public Int32 survivePlayerCount; // 0xa0
	public Int32 loadSeqNum; // 0xa4
	public Int32 refreshPlayerListSeqNum; // 0xa8
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0__GetSelectStatus; // 0x10
	private static DelegateBridge __Hotfix0_GenerateBetParams; // 0x18
	private static DelegateBridge __Hotfix0_CanSelect; // 0x20
	private static DelegateBridge __Hotfix0_SetEnemyDetailPanelShowStatus; // 0x28
	private static DelegateBridge __Hotfix0_ToggleEnemyDetailPanelShowStatus; // 0x30
	private static DelegateBridge __Hotfix0_SetEmoticonDisabledStatus; // 0x38
	private static DelegateBridge __Hotfix0_RefreshPlayerList; // 0x40
	private static DelegateBridge __Hotfix0_ClearPlayerList; // 0x48
	private static DelegateBridge __Hotfix0__SortPlayerListByBetTs; // 0x50
	private static DelegateBridge __Hotfix0__CalculatePlayerRank; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x297cf68 VA: 0x7594f94f68
	public Void LoadData() { }
	// RVA: 0x297de3c VA: 0x7594f95e3c
	public Void UpdateData() { }
	// RVA: 0x2982c2c VA: 0x7594f9ac2c
	private EnemyDuelBetSelectStatus _GetSelectStatus(EnemyDuelChoiceSide choiceSide, EnemyDuelChoiceType choiceType) { }
	// RVA: 0x297e548 VA: 0x7594f96548
	public EnemyDuelBetParams GenerateBetParams(EnemyDuelBetSelectStatus status) { }
	// RVA: 0x297e420 VA: 0x7594f96420
	public Boolean CanSelect(EnemyDuelBetSelectStatus status) { }
	// RVA: 0x297e7f8 VA: 0x7594f967f8
	public Boolean SetEnemyDetailPanelShowStatus(Boolean isShow) { }
	// RVA: 0x297e788 VA: 0x7594f96788
	public Void ToggleEnemyDetailPanelShowStatus() { }
	// RVA: 0x297d56c VA: 0x7594f9556c
	public Void SetEmoticonDisabledStatus(Boolean isEmoticonDisabled) { }
	// RVA: 0x2982cfc VA: 0x7594f9acfc
	public Void RefreshPlayerList() { }
	// RVA: 0x2983220 VA: 0x7594f9b220
	public Void ClearPlayerList() { }
	// RVA: 0x29832f8 VA: 0x7594f9b2f8
	private Int32 _SortPlayerListByBetTs(EnemyDuelBetPlayerViewModel lhs, EnemyDuelBetPlayerViewModel rhs) { }
	// RVA: 0x2982a68 VA: 0x7594f9aa68
	private Void _CalculatePlayerRank() { }
	// RVA: 0x2983418 VA: 0x7594f9b418
	public Void .ctor() { }
}
```