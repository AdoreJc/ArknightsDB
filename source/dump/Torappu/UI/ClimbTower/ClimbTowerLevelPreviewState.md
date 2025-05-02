# ClimbTowerLevelPreviewState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerLevelPreviewView _levelPreviewView`

- `RectTransform _backBtn`

- `ClimbTowerLevelPreviewStateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void OnBtnUpClicked()`

- `Void OnBtnDownClicked()`

- `Void OnBossInfoClicked()`

- `Void OnJumpToEnemyHandbook(List`1, Int32)`

- `Void OnJumpToRewardDetailView()`

- `Void <_InitIfNot>b__5_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLevelPreviewState : PopupFloatState
{
	private ClimbTowerLevelPreviewView _levelPreviewView; // 0x70
	private RectTransform _backBtn; // 0x78
	private ClimbTowerLevelPreviewStateBean m_stateBean; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnUpClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnDownClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnBossInfoClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnJumpToEnemyHandbook; // 0x48
	private static DelegateBridge __Hotfix0_OnJumpToRewardDetailView; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2c99220 VA: 0x75952b1220
	private Void _InitIfNot() { }
	// RVA: 0x2c99328 VA: 0x75952b1328
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c99390 VA: 0x75952b1390
	protected override Void OnEnter() { }
	// RVA: 0x2c996a4 VA: 0x75952b16a4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2c99898 VA: 0x75952b1898
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x2c999ec VA: 0x75952b19ec
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x2c99b4c VA: 0x75952b1b4c
	public Void OnBtnUpClicked() { }
	// RVA: 0x2c99d4c VA: 0x75952b1d4c
	public Void OnBtnDownClicked() { }
	// RVA: 0x2c99f4c VA: 0x75952b1f4c
	public Void OnBossInfoClicked() { }
	// RVA: 0x2c9a148 VA: 0x75952b2148
	public Void OnJumpToEnemyHandbook(List`1 enemyList, Int32 enemyListIdx) { }
	// RVA: 0x2c9a39c VA: 0x75952b239c
	public Void OnJumpToRewardDetailView() { }
	// RVA: 0x2c9a5a4 VA: 0x75952b25a4
	public Void .ctor() { }
	// RVA: 0x2c9a654 VA: 0x75952b2654
	private Void <_InitIfNot>b__5_0() { }
	// RVA: 0x2c9a664 VA: 0x75952b2664
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c9a66c VA: 0x75952b266c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```