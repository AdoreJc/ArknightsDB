# ActMultiV3BattleFinishView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `UIFullScreenImage _blurBg`

- `ActMultiV3BattleFinishCompleteInfoView _completeInfoPrefab`

- `ActMultiV3BattleFinishPlayerDisplayView _playerDisplayPrefab`

- `ActMultiV3BattleFinishReportPanel _reportPanelPrefab`

- `RectTransform _completeInfoContainer`

- `RectTransform _playerDisplayContainer`

- `RectTransform _reportPanelContainer`

- `Single _autoNextInterval`

- `Boolean m_hasConfirm`

- `ActMultiV3BattleFinishViewModel m_viewModel`

- `ActMultiV3BattleFinishCompleteInfoView m_completeInfoView`

- `ActMultiV3BattleFinishPlayerDisplayView m_playerDisplayView`

- `ActMultiV3BattleFinishReportPanel m_reportPanel`


## Methods

- `ActMultiV3BattleFinishViewModel _CreateViewModel()`

- `MultiplayerInput _GetMultiplayerInput()`

- `Boolean _CheckIfTraining()`

- `BattleFinishRspData _GetBattleFinishRspData(Boolean)`

- `Void _EventOnReportShow()`

- `Void _EventOnReportHide()`

- `Void _EventOnReportConfirm()`

- `Void _EventOnReportItemClick(String)`

- `Void _SetReportPanelVisible(Boolean)`

- `Void _OnNextClick()`

- `Void _OnBackHomeClick()`

- `Void _OnBackRoomClick()`

- `Void _OnContinueCoop()`

- `Void _OnBackMatchClick()`

- `Void _EventOnBtnLikeClick()`

- `Void _RouteToAct(Boolean, Boolean)`

- `Void _HandleTeamChanged(Object)`

- `Void _HandleGotLike()`

- `Void _HandlePartnerContinue()`

- `Void _HandleSelfContinue()`

- `Boolean <ShowEnterEffectCoroutine>b__13_0()`

- `IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishView : DynBattleFinishView
{
	private UIFullScreenImage _blurBg; // 0x20
	private ActMultiV3BattleFinishCompleteInfoView _completeInfoPrefab; // 0x28
	private ActMultiV3BattleFinishPlayerDisplayView _playerDisplayPrefab; // 0x30
	private ActMultiV3BattleFinishReportPanel _reportPanelPrefab; // 0x38
	private RectTransform _completeInfoContainer; // 0x40
	private RectTransform _playerDisplayContainer; // 0x48
	private RectTransform _reportPanelContainer; // 0x50
	private Single _autoNextInterval; // 0x58
	private Boolean m_hasConfirm; // 0x5c
	private ActMultiV3BattleFinishViewModel m_viewModel; // 0x60
	private ActMultiV3BattleFinishCompleteInfoView m_completeInfoView; // 0x68
	private ActMultiV3BattleFinishPlayerDisplayView m_playerDisplayView; // 0x70
	private ActMultiV3BattleFinishReportPanel m_reportPanel; // 0x78
	private static DelegateBridge __Hotfix0_ShowEnterEffectCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0__CreateViewModel; // 0x10
	private static DelegateBridge __Hotfix0__GetMultiplayerInput; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfTraining; // 0x20
	private static DelegateBridge __Hotfix0__GetBattleFinishRspData; // 0x28
	private static DelegateBridge __Hotfix0__EventOnReportShow; // 0x30
	private static DelegateBridge __Hotfix0__EventOnReportHide; // 0x38
	private static DelegateBridge __Hotfix0__EventOnReportConfirm; // 0x40
	private static DelegateBridge __Hotfix0__EventOnReportItemClick; // 0x48
	private static DelegateBridge __Hotfix0__SetReportPanelVisible; // 0x50
	private static DelegateBridge __Hotfix0__OnNextClick; // 0x58
	private static DelegateBridge __Hotfix0__OnBackHomeClick; // 0x60
	private static DelegateBridge __Hotfix0__OnBackRoomClick; // 0x68
	private static DelegateBridge __Hotfix0__OnContinueCoop; // 0x70
	private static DelegateBridge __Hotfix0__OnBackMatchClick; // 0x78
	private static DelegateBridge __Hotfix0__EventOnBtnLikeClick; // 0x80
	private static DelegateBridge __Hotfix0__RouteToAct; // 0x88
	private static DelegateBridge __Hotfix0__HandleTeamChanged; // 0x90
	private static DelegateBridge __Hotfix0__HandleGotLike; // 0x98
	private static DelegateBridge __Hotfix0__HandlePartnerContinue; // 0xa0
	private static DelegateBridge __Hotfix0__HandleSelfContinue; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0


	// RVA: 0x31850c0 VA: 0x759579d0c0
	public override IEnumerator ShowEnterEffectCoroutine() { }
	// RVA: 0x3185194 VA: 0x759579d194
	protected override Void OnInit() { }
	// RVA: 0x318581c VA: 0x759579d81c
	private ActMultiV3BattleFinishViewModel _CreateViewModel() { }
	// RVA: 0x3185eac VA: 0x759579deac
	private MultiplayerInput _GetMultiplayerInput() { }
	// RVA: 0x3185af8 VA: 0x759579daf8
	private Boolean _CheckIfTraining() { }
	// RVA: 0x3185cd8 VA: 0x759579dcd8
	private BattleFinishRspData _GetBattleFinishRspData(Boolean isTraining) { }
	// RVA: 0x3186b10 VA: 0x759579eb10
	private Void _EventOnReportShow() { }
	// RVA: 0x3186c40 VA: 0x759579ec40
	private Void _EventOnReportHide() { }
	// RVA: 0x3186cac VA: 0x759579ecac
	private Void _EventOnReportConfirm() { }
	// RVA: 0x3186fc8 VA: 0x759579efc8
	private Void _EventOnReportItemClick(String reportId) { }
	// RVA: 0x3186b7c VA: 0x759579eb7c
	private Void _SetReportPanelVisible(Boolean isShow) { }
	// RVA: 0x318708c VA: 0x759579f08c
	private Void _OnNextClick() { }
	// RVA: 0x31872e0 VA: 0x759579f2e0
	private Void _OnBackHomeClick() { }
	// RVA: 0x3187350 VA: 0x759579f350
	private Void _OnBackRoomClick() { }
	// RVA: 0x3187408 VA: 0x759579f408
	private Void _OnContinueCoop() { }
	// RVA: 0x3187728 VA: 0x759579f728
	private Void _OnBackMatchClick() { }
	// RVA: 0x3187798 VA: 0x759579f798
	private Void _EventOnBtnLikeClick() { }
	// RVA: 0x3187124 VA: 0x759579f124
	private Void _RouteToAct(Boolean isBackToEntry, Boolean continueCoop) { }
	// RVA: 0x3187954 VA: 0x759579f954
	private Void _HandleTeamChanged(Object arg) { }
	// RVA: 0x31879f8 VA: 0x759579f9f8
	private Void _HandleGotLike() { }
	// RVA: 0x3187abc VA: 0x759579fabc
	private Void _HandlePartnerContinue() { }
	// RVA: 0x3187b80 VA: 0x759579fb80
	private Void _HandleSelfContinue() { }
	// RVA: 0x3187fdc VA: 0x759579ffdc
	public Void .ctor() { }
	// RVA: 0x3188054 VA: 0x75957a0054
	private Boolean <ShowEnterEffectCoroutine>b__13_0() { }
	// RVA: 0x3188064 VA: 0x75957a0064
	private IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine() { }
}
```