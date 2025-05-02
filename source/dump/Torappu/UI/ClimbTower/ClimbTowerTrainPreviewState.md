# ClimbTowerTrainPreviewState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `RectTransform _previewContainer`

- `ClimbTowerPanelPreviewLevel _prefabPreview`

- `RectTransform _backBtn`

- `ClimbTowerTrainPreviewStateBean m_stateBean`

- `ClimbTowerPanelPreviewLevel m_previewPanel`

- `Boolean m_hasInited`


## Methods

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void OnBackBtnClick()`

- `Void _InitIfNot()`

- `Void _OnJumpToEnemyHandbook(List`1, Int32)`

- `Void _OnJumpToRewardDetailView()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrainPreviewState : PopupFloatState, IHotfixable
{
	private RectTransform _previewContainer; // 0x70
	private ClimbTowerPanelPreviewLevel _prefabPreview; // 0x78
	private RectTransform _backBtn; // 0x80
	private ClimbTowerTrainPreviewStateBean m_stateBean; // 0x88
	private ClimbTowerPanelPreviewLevel m_previewPanel; // 0x90
	private Boolean m_hasInited; // 0x98
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0x20
	private static DelegateBridge __Hotfix0_OnBackBtnClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandbook; // 0x38
	private static DelegateBridge __Hotfix1__OnJumpToRewardDetailView; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2ca47e0 VA: 0x75952bc7e0
	protected override Void OnEnter() { }
	// RVA: 0x2ca4ac4 VA: 0x75952bcac4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ca4b2c VA: 0x75952bcb2c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ca4d20 VA: 0x75952bcd20
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x2ca4ec8 VA: 0x75952bcec8
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x2ca4fe0 VA: 0x75952bcfe0
	public Void OnBackBtnClick() { }
	// RVA: 0x2ca48a4 VA: 0x75952bc8a4
	private Void _InitIfNot() { }
	// RVA: 0x2ca50ec VA: 0x75952bd0ec
	private Void _OnJumpToEnemyHandbook(List`1 enemyList, Int32 enemyListIdx) { }
	// RVA: 0x2ca5340 VA: 0x75952bd340
	private Void _OnJumpToRewardDetailView() { }
	// RVA: 0x2ca5548 VA: 0x75952bd548
	public Void .ctor() { }
	// RVA: 0x2ca5664 VA: 0x75952bd664
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ca566c VA: 0x75952bd66c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```