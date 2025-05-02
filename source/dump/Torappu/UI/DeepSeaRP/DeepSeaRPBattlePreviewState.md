# DeepSeaRPBattlePreviewState

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPBattleDetailView _battleDetailView`

- `DeepSeaRPBattleStoryView _battleStoryView`

- `DeepSeaRPBattlePreviewInfoBasicPanel _battleInfoPanel`

- `DeepSeaRPBattlePreviewInfoBasicPanel _battleInfoHardPanel`

- `CanvasGroup _apStatusCanvasGroup`

- `Boolean m_isInited`

- `DeepSeaRPBattlePreviewStateBean m_stateBean`

- `IStateCacheHandler m_runtimeHandler`

- `DeepSeaRolePlayPage m_page`


## Methods

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void OnBtnStartBattleClick()`

- `Void OnBtnStartPracticeClick()`

- `Void OnZoneMapEmptyAreaClicked()`

- `Void OnReplayStoryOpenClick()`

- `Void OnReplayStoryTrigClick(Int32)`

- `Void OnDetailBtnClicked()`

- `Void OnEnemyHandBookOpen()`

- `Void OnOpenRewardClick()`

- `Void ToggleAutoBattle()`

- `Void OnBeHard()`

- `Void OnBeNormal()`

- `Void OnLockedHardBattleClick()`

- `Void _InitIfNot()`

- `Boolean _CheckCostBeforeStartBattle()`

- `Boolean _CheckApBeforeStartBattle(StageViewModel)`

- `Void _GoToSquad(Boolean)`

- `Void _OnGoToSquad(String, String, Boolean, Boolean, Boolean)`

- `Void _OpenSquadPage(String, String, Boolean, Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattlePreviewState : PopupFadeState, IHotfixable
{
	private DeepSeaRPBattleDetailView _battleDetailView; // 0x70
	private DeepSeaRPBattleStoryView _battleStoryView; // 0x78
	private DeepSeaRPBattlePreviewInfoBasicPanel _battleInfoPanel; // 0x80
	private DeepSeaRPBattlePreviewInfoBasicPanel _battleInfoHardPanel; // 0x88
	private CanvasGroup _apStatusCanvasGroup; // 0x90
	private Boolean m_isInited; // 0x98
	private DeepSeaRPBattlePreviewStateBean m_stateBean; // 0xa0
	private IStateCacheHandler m_runtimeHandler; // 0xa8
	private DeepSeaRolePlayPage m_page; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0_OnPause; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnStartBattleClick; // 0x38
	private static DelegateBridge __Hotfix0_OnBtnStartPracticeClick; // 0x40
	private static DelegateBridge __Hotfix0_OnZoneMapEmptyAreaClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnReplayStoryOpenClick; // 0x50
	private static DelegateBridge __Hotfix0_OnReplayStoryTrigClick; // 0x58
	private static DelegateBridge __Hotfix0_OnDetailBtnClicked; // 0x60
	private static DelegateBridge __Hotfix0_OnEnemyHandBookOpen; // 0x68
	private static DelegateBridge __Hotfix0_OnOpenRewardClick; // 0x70
	private static DelegateBridge __Hotfix0_ToggleAutoBattle; // 0x78
	private static DelegateBridge __Hotfix0_OnBeHard; // 0x80
	private static DelegateBridge __Hotfix0_OnBeNormal; // 0x88
	private static DelegateBridge __Hotfix0_OnLockedHardBattleClick; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x98
	private static DelegateBridge __Hotfix0__CheckCostBeforeStartBattle; // 0xa0
	private static DelegateBridge __Hotfix0__CheckApBeforeStartBattle; // 0xa8
	private static DelegateBridge __Hotfix0__GoToSquad; // 0xb0
	private static DelegateBridge __Hotfix0__OnGoToSquad; // 0xb8
	private static DelegateBridge __Hotfix0__OpenSquadPage; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x29be35c VA: 0x7594fd635c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29be3c4 VA: 0x7594fd63c4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x29be5b8 VA: 0x7594fd65b8
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x29be764 VA: 0x7594fd6764
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x29be89c VA: 0x7594fd689c
	protected override Void OnEnter() { }
	// RVA: 0x29beebc VA: 0x7594fd6ebc
	protected override Void OnResume() { }
	// RVA: 0x29bef54 VA: 0x7594fd6f54
	protected override Void OnPause() { }
	// RVA: 0x29befd8 VA: 0x7594fd6fd8
	public Void OnBtnStartBattleClick() { }
	// RVA: 0x29bf248 VA: 0x7594fd7248
	public Void OnBtnStartPracticeClick() { }
	// RVA: 0x29bf420 VA: 0x7594fd7420
	public Void OnZoneMapEmptyAreaClicked() { }
	// RVA: 0x29bfa28 VA: 0x7594fd7a28
	public Void OnReplayStoryOpenClick() { }
	// RVA: 0x29bfb1c VA: 0x7594fd7b1c
	public Void OnReplayStoryTrigClick(Int32 index) { }
	// RVA: 0x29bfecc VA: 0x7594fd7ecc
	public Void OnDetailBtnClicked() { }
	// RVA: 0x29bff88 VA: 0x7594fd7f88
	public Void OnEnemyHandBookOpen() { }
	// RVA: 0x29c0090 VA: 0x7594fd8090
	public Void OnOpenRewardClick() { }
	// RVA: 0x29c0198 VA: 0x7594fd8198
	public Void ToggleAutoBattle() { }
	// RVA: 0x29c025c VA: 0x7594fd825c
	public Void OnBeHard() { }
	// RVA: 0x29c037c VA: 0x7594fd837c
	public Void OnBeNormal() { }
	// RVA: 0x29c048c VA: 0x7594fd848c
	public Void OnLockedHardBattleClick() { }
	// RVA: 0x29beaf0 VA: 0x7594fd6af0
	private Void _InitIfNot() { }
	// RVA: 0x29bf098 VA: 0x7594fd7098
	private Boolean _CheckCostBeforeStartBattle() { }
	// RVA: 0x29c056c VA: 0x7594fd856c
	private Boolean _CheckApBeforeStartBattle(StageViewModel model) { }
	// RVA: 0x29bf128 VA: 0x7594fd7128
	private Void _GoToSquad(Boolean isPractice) { }
	// RVA: 0x29c06f0 VA: 0x7594fd86f0
	private Void _OnGoToSquad(String stageId, String hardId, Boolean isHard, Boolean isPractice, Boolean isAuto) { }
	// RVA: 0x29c0b0c VA: 0x7594fd8b0c
	private Void _OpenSquadPage(String stageId, String hardId, Boolean isPractive, Boolean isAuto, Boolean isHard) { }
	// RVA: 0x29c1174 VA: 0x7594fd9174
	public Void .ctor() { }
	// RVA: 0x29c1224 VA: 0x7594fd9224
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x29c122c VA: 0x7594fd922c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x29c1234 VA: 0x7594fd9234
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x29c123c VA: 0x7594fd923c
	private Void <>xLuaBaseProxy_OnPause() { }
}
```