# HiddenStageDefaultState

**Namespace:** `Torappu.UI.HiddenStage`


## Fields

- `GameObject _mapTips`

- `Image _mapPreview`

- `Image _bgImg`

- `RectTransform m_viewContainer`

- `String m_cachedStageId`

- `HiddenStageDecodeProperty m_property`

- `Boolean m_isInited`

- `HiddenStageDecodeView m_view`


## Properties

- `Boolean isRetro`

- `String activityId`


## Methods

- `Boolean get_isRetro()`

- `String get_activityId()`

- `Void _InitIfNot()`

- `Void _InitDecodeView()`

- `Void SendUnlockHiddenStage(String, Action`1)`

- `Void _UnlockResp(HiddenStageUnlockResponse)`

- `Void _OnGoToSquad(Boolean)`

- `Void _EventOnAvgClick()`

- `Void _EventOnEnemyHandbookClick()`

- `Void _EventOnBattleStart()`

- `Void _OnOpenRewardClick()`

- `Void _EventOnJumpToStageDetail()`

- `Void _EventOnJumpToStage(String)`

- `Void _EventOnJumpToDecodePanel()`

- `Void _EventOnUnlockHiddenStage()`

- `Void _EventOnExit()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void _ClearBlurSprite()`

- `Void CloseTips()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HiddenStage
public class HiddenStageDefaultState : State
{
	private GameObject _mapTips; // 0x50
	private Image _mapPreview; // 0x58
	private Image _bgImg; // 0x60
	private RectTransform m_viewContainer; // 0x68
	private String m_cachedStageId; // 0x70
	private HiddenStageDecodeProperty m_property; // 0x78
	private Boolean m_isInited; // 0x80
	private HiddenStageDecodeView m_view; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_isRetro; // 0x8
	private static DelegateBridge __Hotfix0_get_activityId; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__InitDecodeView; // 0x20
	private static DelegateBridge __Hotfix0_SendUnlockHiddenStage; // 0x28
	private static DelegateBridge __Hotfix0__UnlockResp; // 0x30
	private static DelegateBridge __Hotfix0__OnGoToSquad; // 0x38
	private static DelegateBridge __Hotfix0__EventOnAvgClick; // 0x40
	private static DelegateBridge __Hotfix0__EventOnEnemyHandbookClick; // 0x48
	private static DelegateBridge __Hotfix0__EventOnBattleStart; // 0x50
	private static DelegateBridge __Hotfix0__OnOpenRewardClick; // 0x58
	private static DelegateBridge __Hotfix0__EventOnJumpToStageDetail; // 0x60
	private static DelegateBridge __Hotfix0__EventOnJumpToStage; // 0x68
	private static DelegateBridge __Hotfix0__EventOnJumpToDecodePanel; // 0x70
	private static DelegateBridge __Hotfix0__EventOnUnlockHiddenStage; // 0x78
	private static DelegateBridge __Hotfix0__EventOnExit; // 0x80
	private static DelegateBridge __Hotfix0_OnEnter; // 0x88
	private static DelegateBridge __Hotfix0_OnResume; // 0x90
	private static DelegateBridge __Hotfix0_OnPause; // 0x98
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0xa0
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0xa8
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0xb0
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0xb8
	private static DelegateBridge __Hotfix0_CloseTips; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Boolean isRetro { get; }
	public String activityId { get; }

	// RVA: 0x285c078 VA: 0x7594e74078
	public override IStateBean GetCacheBean() { }
	// RVA: 0x285c0dc VA: 0x7594e740dc
	public Boolean get_isRetro() { }
	// RVA: 0x285c170 VA: 0x7594e74170
	public String get_activityId() { }
	// RVA: 0x285c204 VA: 0x7594e74204
	private Void _InitIfNot() { }
	// RVA: 0x285c524 VA: 0x7594e74524
	private Void _InitDecodeView() { }
	// RVA: 0x285ca9c VA: 0x7594e74a9c
	private Void SendUnlockHiddenStage(String stageId, Action`1 handler) { }
	// RVA: 0x285ccd8 VA: 0x7594e74cd8
	private Void _UnlockResp(HiddenStageUnlockResponse resp) { }
	// RVA: 0x285cde0 VA: 0x7594e74de0
	private Void _OnGoToSquad(Boolean isPractice) { }
	// RVA: 0x285cfa4 VA: 0x7594e74fa4
	private Void _EventOnAvgClick() { }
	// RVA: 0x285d260 VA: 0x7594e75260
	private Void _EventOnEnemyHandbookClick() { }
	// RVA: 0x285d36c VA: 0x7594e7536c
	private Void _EventOnBattleStart() { }
	// RVA: 0x285d3d8 VA: 0x7594e753d8
	private Void _OnOpenRewardClick() { }
	// RVA: 0x285d4e4 VA: 0x7594e754e4
	private Void _EventOnJumpToStageDetail() { }
	// RVA: 0x285d598 VA: 0x7594e75598
	private Void _EventOnJumpToStage(String stageId) { }
	// RVA: 0x285d6d4 VA: 0x7594e756d4
	private Void _EventOnJumpToDecodePanel() { }
	// RVA: 0x285d78c VA: 0x7594e7578c
	private Void _EventOnUnlockHiddenStage() { }
	// RVA: 0x285d8c0 VA: 0x7594e758c0
	private Void _EventOnExit() { }
	// RVA: 0x285d93c VA: 0x7594e7593c
	protected override Void OnEnter() { }
	// RVA: 0x285da80 VA: 0x7594e75a80
	protected override Void OnResume() { }
	// RVA: 0x285daec VA: 0x7594e75aec
	protected override Void OnPause() { }
	// RVA: 0x285db58 VA: 0x7594e75b58
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x285dd4c VA: 0x7594e75d4c
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x285dec0 VA: 0x7594e75ec0
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x285e00c VA: 0x7594e7600c
	private Void _ClearBlurSprite() { }
	// RVA: 0x285e110 VA: 0x7594e76110
	public Void CloseTips() { }
	// RVA: 0x285e1a8 VA: 0x7594e761a8
	public Void .ctor() { }
	// RVA: 0x285e28c VA: 0x7594e7628c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x285e294 VA: 0x7594e76294
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x285e29c VA: 0x7594e7629c
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x285e2a4 VA: 0x7594e762a4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```