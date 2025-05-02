# BossRushStageDetailState

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `RectTransform _topContainer`

- `BossRushStageDetailButtonGroupView _buttonGroupView`

- `BossRushStageDetailMapPreviewView _mapPreviewView`

- `BossRushStageDetailInfoView _infoView`

- `BossRushStageDetailTeamGroupView _teamGroupView`

- `BossRushStageDetailMapPreviewPanel _previewPanel`

- `BossRushStageDetailDropPanel _dropPanel`

- `BossRushStageDetailStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnHideMapClick()`

- `Void _OnMapPreviewItemClick(Int32)`

- `Void _OnModeButtonClick(BossRushStageType)`

- `Void _OnModeSwitchClick()`

- `Void _OnEnemyDetailClick()`

- `Void _OnTeamClick(String)`

- `Void _OnStartBattleClick()`

- `Void _OnMapPreviewClick(Boolean)`

- `Void _OnRewardClick()`

- `Void _InitIfNot()`

- `Void _RefreshView()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailState : PopupFadeState
{
	private RectTransform _topContainer; // 0x70
	private BossRushStageDetailButtonGroupView _buttonGroupView; // 0x78
	private BossRushStageDetailMapPreviewView _mapPreviewView; // 0x80
	private BossRushStageDetailInfoView _infoView; // 0x88
	private BossRushStageDetailTeamGroupView _teamGroupView; // 0x90
	private BossRushStageDetailMapPreviewPanel _previewPanel; // 0x98
	private BossRushStageDetailDropPanel _dropPanel; // 0xa0
	private BossRushStageDetailStateBean m_stateBean; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x20
	private static DelegateBridge __Hotfix0__OnHideMapClick; // 0x28
	private static DelegateBridge __Hotfix0__OnMapPreviewItemClick; // 0x30
	private static DelegateBridge __Hotfix0__OnModeButtonClick; // 0x38
	private static DelegateBridge __Hotfix0__OnModeSwitchClick; // 0x40
	private static DelegateBridge __Hotfix0__OnEnemyDetailClick; // 0x48
	private static DelegateBridge __Hotfix0__OnTeamClick; // 0x50
	private static DelegateBridge __Hotfix0__OnStartBattleClick; // 0x58
	private static DelegateBridge __Hotfix0__OnMapPreviewClick; // 0x60
	private static DelegateBridge __Hotfix0__OnRewardClick; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x70
	private static DelegateBridge __Hotfix0__RefreshView; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x2e763c4 VA: 0x759548e3c4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e7642c VA: 0x759548e42c
	protected override Void OnEnter() { }
	// RVA: 0x2e76b94 VA: 0x759548eb94
	protected override Void OnResume() { }
	// RVA: 0x2e76c24 VA: 0x759548ec24
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2e76d9c VA: 0x759548ed9c
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x2e77020 VA: 0x759548f020
	private Void _OnHideMapClick() { }
	// RVA: 0x2e770f4 VA: 0x759548f0f4
	private Void _OnMapPreviewItemClick(Int32 position) { }
	// RVA: 0x2e771cc VA: 0x759548f1cc
	private Void _OnModeButtonClick(BossRushStageType stageType) { }
	// RVA: 0x2e775b4 VA: 0x759548f5b4
	private Void _OnModeSwitchClick() { }
	// RVA: 0x2e77760 VA: 0x759548f760
	private Void _OnEnemyDetailClick() { }
	// RVA: 0x2e77868 VA: 0x759548f868
	private Void _OnTeamClick(String teamId) { }
	// RVA: 0x2e779c8 VA: 0x759548f9c8
	private Void _OnStartBattleClick() { }
	// RVA: 0x2e77c84 VA: 0x759548fc84
	private Void _OnMapPreviewClick(Boolean isShown) { }
	// RVA: 0x2e77d64 VA: 0x759548fd64
	private Void _OnRewardClick() { }
	// RVA: 0x2e764a8 VA: 0x759548e4a8
	private Void _InitIfNot() { }
	// RVA: 0x2e769a4 VA: 0x759548e9a4
	private Void _RefreshView() { }
	// RVA: 0x2e78180 VA: 0x7595490180
	public Void .ctor() { }
	// RVA: 0x2e782d8 VA: 0x75954902d8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e782e0 VA: 0x75954902e0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2e782e8 VA: 0x75954902e8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```