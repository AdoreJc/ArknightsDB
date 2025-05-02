# RoguelikeTopicBattlePassState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBattlePassView _battlePassView`

- `RoguelikeTopicBPGreatRewardView _grandPrizeView`

- `Single _greatRewardSwitchDelay`

- `RoguelikeTopicBattlePassStateBean m_stateBean`

- `String m_topicId`

- `RoguelikeTopicBattlePassStyle m_topicStyle`

- `Boolean m_isInited`

- `Boolean m_switchAnimActive`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _FocusCurrentLv()`

- `IEnumerator _UpdateGreatRewardModelAfterDelay(Int32)`

- `Void _OnGreatRewardSwitch(Boolean)`

- `Void _OnResumeFromPurchaseConfirmState(IStateBean)`

- `Void _OnJumpToPurchaseState(IStateBean)`

- `Void _OnJumpToDetailState(IStateBean)`

- `Void _OnLeftArrowClick()`

- `Void _OnRightArrowClick()`

- `Void _OnGreatRewardDetailClick(RoguelikeTopicBPPrizeViewModel)`

- `Void _OnPurchaseGrandPrizeClick(RoguelikeTopicBPPrizeViewModel)`

- `Void _OnRewardClick(List`1)`

- `Void OnGuideBtnClick()`

- `Void OnBpPurchaseClick(RoguelikeTopicBPTopViewModel)`

- `Void <_OnGreatRewardSwitch>b__14_0()`

- `Void <_OnRewardClick>b__25_0(RoguelikeTopicBpGetRewardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassState : PopupFadeState
{
	private RoguelikeTopicBattlePassView _battlePassView; // 0x70
	private RoguelikeTopicBPGreatRewardView _grandPrizeView; // 0x78
	private Single _greatRewardSwitchDelay; // 0x80
	private RoguelikeTopicBattlePassStateBean m_stateBean; // 0x88
	private String m_topicId; // 0x90
	private RoguelikeTopicBattlePassStyle m_topicStyle; // 0x98
	private Boolean m_isInited; // 0xa0
	private Boolean m_switchAnimActive; // 0xa1
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__FocusCurrentLv; // 0x20
	private static DelegateBridge __Hotfix0__UpdateGreatRewardModelAfterDelay; // 0x28
	private static DelegateBridge __Hotfix0__OnGreatRewardSwitch; // 0x30
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x38
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x40
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x48
	private static DelegateBridge __Hotfix0__OnResumeFromPurchaseConfirmState; // 0x50
	private static DelegateBridge __Hotfix0__OnJumpToPurchaseState; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpToDetailState; // 0x60
	private static DelegateBridge __Hotfix0__OnLeftArrowClick; // 0x68
	private static DelegateBridge __Hotfix0__OnRightArrowClick; // 0x70
	private static DelegateBridge __Hotfix0__OnGreatRewardDetailClick; // 0x78
	private static DelegateBridge __Hotfix0__OnPurchaseGrandPrizeClick; // 0x80
	private static DelegateBridge __Hotfix0__OnRewardClick; // 0x88
	private static DelegateBridge __Hotfix0_OnGuideBtnClick; // 0x90
	private static DelegateBridge __Hotfix0_OnBpPurchaseClick; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x263f7f0 VA: 0x7594c577f0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x263f858 VA: 0x7594c57858
	protected override Void OnEnter() { }
	// RVA: 0x263fd70 VA: 0x7594c57d70
	protected override Void OnResume() { }
	// RVA: 0x263f934 VA: 0x7594c57934
	private Void _InitIfNot() { }
	// RVA: 0x263fcc4 VA: 0x7594c57cc4
	private IEnumerator _FocusCurrentLv() { }
	// RVA: 0x263ffb0 VA: 0x7594c57fb0
	private IEnumerator _UpdateGreatRewardModelAfterDelay(Int32 step) { }
	// RVA: 0x264009c VA: 0x7594c5809c
	private Void _OnGreatRewardSwitch(Boolean isReverse) { }
	// RVA: 0x2640334 VA: 0x7594c58334
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x26403ac VA: 0x7594c583ac
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2640524 VA: 0x7594c58524
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2640718 VA: 0x7594c58718
	private Void _OnResumeFromPurchaseConfirmState(IStateBean stateBean) { }
	// RVA: 0x26407d0 VA: 0x7594c587d0
	private Void _OnJumpToPurchaseState(IStateBean stateBean) { }
	// RVA: 0x2640898 VA: 0x7594c58898
	private Void _OnJumpToDetailState(IStateBean stateBean) { }
	// RVA: 0x2640a04 VA: 0x7594c58a04
	private Void _OnLeftArrowClick() { }
	// RVA: 0x2640a70 VA: 0x7594c58a70
	private Void _OnRightArrowClick() { }
	// RVA: 0x2640adc VA: 0x7594c58adc
	private Void _OnGreatRewardDetailClick(RoguelikeTopicBPPrizeViewModel prizeModel) { }
	// RVA: 0x2640d94 VA: 0x7594c58d94
	private Void _OnPurchaseGrandPrizeClick(RoguelikeTopicBPPrizeViewModel prizeModel) { }
	// RVA: 0x2640ff0 VA: 0x7594c58ff0
	private Void _OnRewardClick(List`1 idList) { }
	// RVA: 0x2641214 VA: 0x7594c59214
	public Void OnGuideBtnClick() { }
	// RVA: 0x264131c VA: 0x7594c5931c
	public Void OnBpPurchaseClick(RoguelikeTopicBPTopViewModel viewModel) { }
	// RVA: 0x264160c VA: 0x7594c5960c
	public Void .ctor() { }
	// RVA: 0x26416c4 VA: 0x7594c596c4
	private Void <_OnGreatRewardSwitch>b__14_0() { }
	// RVA: 0x26416cc VA: 0x7594c596cc
	private Void <_OnRewardClick>b__25_0(RoguelikeTopicBpGetRewardResponse response) { }
	// RVA: 0x26417bc VA: 0x7594c597bc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x26417c4 VA: 0x7594c597c4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x26417cc VA: 0x7594c597cc
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x26417d4 VA: 0x7594c597d4
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x26417dc VA: 0x7594c597dc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```