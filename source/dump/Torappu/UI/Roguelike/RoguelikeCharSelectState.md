# RoguelikeCharSelectState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeCharSelectStateBean _stateBean`

- `RectTransform _panelTopMenu`

- `GameObject _guideBtn`

- `GameObject _btnAssistGo`

- `UIGuidebookTrigger _guideBookTrigger`

- `RoguelikeCharSelectView _view`

- `RoguelikeMenuButtonPlugin _charRecruitBtnPlguin`

- `RoguelikeMenuButtonPlugin _charSelectBtnPlguin`

- `MenuAdapter m_menuAdapter`

- `RoguelikeMenuButtonPlugin m_menuPlugin`

- `Input m_menuPluginInput`

- `Boolean m_hideCharMenuObject`

- `RoguelikeCommonTopMenu m_topMenu`

- `Boolean m_inited`

- `String m_topicId`

- `Recruit m_recruitData`


## Methods

- `Void _InitIfNot()`

- `Void _DealWithInput()`

- `Void _UpdateRecruitData()`

- `Void DealWithCharClick(Int32)`

- `Void _DealWithSingleSelect(RoguelikeSelectCharViewModel, Int32)`

- `Void _DealWithMultiSelect(RoguelikeSelectCharViewModel, Int32)`

- `Void _TryInsertSelectInst(RoguelikeSelectCharViewModel, RoguelikeCharCardViewModel)`

- `Void DealWithSkillClick(String)`

- `Void DeadWithBranchClick(String)`

- `Void DealWithSkillClickWithCharId(Int32, String)`

- `Void EventOnAttrTabClick(CharAttrTabType)`

- `Void WrapperDismiss()`

- `Void WrapperShowInfo()`

- `Void CleanAllSelect()`

- `Void _CancelPage()`

- `Void _CheckPage()`

- `Boolean _StateClosing()`

- `Boolean _CheckPendingRecruitAndDo()`

- `Void OnCancelSelect()`

- `Void OnFinishSelect()`

- `Void _JumpToFriendAssistState()`

- `Void _SendGetAssistListRequest(String, ProfessionCategory, Action)`

- `Void OnBtnFriendAssist()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectState : PopupFadeState
{
	private RoguelikeCharSelectStateBean _stateBean; // 0x70
	private RectTransform _panelTopMenu; // 0x78
	private GameObject _guideBtn; // 0x80
	private GameObject _btnAssistGo; // 0x88
	private UIGuidebookTrigger _guideBookTrigger; // 0x90
	private RoguelikeCharSelectView _view; // 0x98
	private RoguelikeMenuButtonPlugin _charRecruitBtnPlguin; // 0xa0
	private RoguelikeMenuButtonPlugin _charSelectBtnPlguin; // 0xa8
	private MenuAdapter m_menuAdapter; // 0xb0
	private RoguelikeMenuButtonPlugin m_menuPlugin; // 0xb8
	private Input m_menuPluginInput; // 0xc0
	private Boolean m_hideCharMenuObject; // 0xc8
	private RoguelikeCommonTopMenu m_topMenu; // 0xd0
	private List`1 m_pluginContexts; // 0xd8
	private Boolean m_inited; // 0xe0
	private String m_topicId; // 0xe8
	private Recruit m_recruitData; // 0xf0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__DealWithInput; // 0x20
	private static DelegateBridge __Hotfix0__UpdateRecruitData; // 0x28
	private static DelegateBridge __Hotfix0_DealWithCharClick; // 0x30
	private static DelegateBridge __Hotfix0__DealWithSingleSelect; // 0x38
	private static DelegateBridge __Hotfix0__DealWithMultiSelect; // 0x40
	private static DelegateBridge __Hotfix0__TryInsertSelectInst; // 0x48
	private static DelegateBridge __Hotfix0_DealWithSkillClick; // 0x50
	private static DelegateBridge __Hotfix0_DeadWithBranchClick; // 0x58
	private static DelegateBridge __Hotfix0_DealWithSkillClickWithCharId; // 0x60
	private static DelegateBridge __Hotfix0_EventOnAttrTabClick; // 0x68
	private static DelegateBridge __Hotfix0_WrapperDismiss; // 0x70
	private static DelegateBridge __Hotfix0_WrapperShowInfo; // 0x78
	private static DelegateBridge __Hotfix0_CleanAllSelect; // 0x80
	private static DelegateBridge __Hotfix0__CancelPage; // 0x88
	private static DelegateBridge __Hotfix0__CheckPage; // 0x90
	private static DelegateBridge __Hotfix0__StateClosing; // 0x98
	private static DelegateBridge __Hotfix0__CheckPendingRecruitAndDo; // 0xa0
	private static DelegateBridge __Hotfix0_OnCancelSelect; // 0xa8
	private static DelegateBridge __Hotfix0_OnFinishSelect; // 0xb0
	private static DelegateBridge __Hotfix0__JumpToFriendAssistState; // 0xb8
	private static DelegateBridge __Hotfix0__SendGetAssistListRequest; // 0xc0
	private static DelegateBridge __Hotfix0_OnExit; // 0xc8
	private static DelegateBridge __Hotfix0_OnBtnFriendAssist; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8


	// RVA: 0x2ac6144 VA: 0x75950de144
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ac61ac VA: 0x75950de1ac
	private Void _InitIfNot() { }
	// RVA: 0x2ac645c VA: 0x75950de45c
	protected override Void OnEnter() { }
	// RVA: 0x2ac6ba8 VA: 0x75950deba8
	protected override Void OnResume() { }
	// RVA: 0x2ac6600 VA: 0x75950de600
	private Void _DealWithInput() { }
	// RVA: 0x2ac6ddc VA: 0x75950deddc
	private Void _UpdateRecruitData() { }
	// RVA: 0x2ac6ea4 VA: 0x75950deea4
	public Void DealWithCharClick(Int32 instId) { }
	// RVA: 0x2ac7048 VA: 0x75950df048
	private Void _DealWithSingleSelect(RoguelikeSelectCharViewModel value, Int32 instId) { }
	// RVA: 0x2ac7250 VA: 0x75950df250
	private Void _DealWithMultiSelect(RoguelikeSelectCharViewModel value, Int32 instId) { }
	// RVA: 0x2ac74a4 VA: 0x75950df4a4
	private Void _TryInsertSelectInst(RoguelikeSelectCharViewModel value, RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2ac7698 VA: 0x75950df698
	public Void DealWithSkillClick(String skillId) { }
	// RVA: 0x2ac7800 VA: 0x75950df800
	public Void DeadWithBranchClick(String equipId) { }
	// RVA: 0x2ac790c VA: 0x75950df90c
	public Void DealWithSkillClickWithCharId(Int32 instId, String skillId) { }
	// RVA: 0x2ac798c VA: 0x75950df98c
	public Void EventOnAttrTabClick(CharAttrTabType tabType) { }
	// RVA: 0x2ac7a70 VA: 0x75950dfa70
	public Void WrapperDismiss() { }
	// RVA: 0x2ac7b08 VA: 0x75950dfb08
	public Void WrapperShowInfo() { }
	// RVA: 0x2ac7b7c VA: 0x75950dfb7c
	public Void CleanAllSelect() { }
	// RVA: 0x2ac7d44 VA: 0x75950dfd44
	private Void _CancelPage() { }
	// RVA: 0x2ac813c VA: 0x75950e013c
	private Void _CheckPage() { }
	// RVA: 0x2ac7e34 VA: 0x75950dfe34
	private Boolean _StateClosing() { }
	// RVA: 0x2ac7eb0 VA: 0x75950dfeb0
	private Boolean _CheckPendingRecruitAndDo() { }
	// RVA: 0x2ac82e4 VA: 0x75950e02e4
	public Void OnCancelSelect() { }
	// RVA: 0x2ac84cc VA: 0x75950e04cc
	public Void OnFinishSelect() { }
	// RVA: 0x2ac87d0 VA: 0x75950e07d0
	private Void _JumpToFriendAssistState() { }
	// RVA: 0x2ac88d8 VA: 0x75950e08d8
	private Void _SendGetAssistListRequest(String index, ProfessionCategory profession, Action onComplete) { }
	// RVA: 0x2ac8ba4 VA: 0x75950e0ba4
	protected override Void OnExit() { }
	// RVA: 0x2ac8c28 VA: 0x75950e0c28
	public Void OnBtnFriendAssist() { }
	// RVA: 0x2ac8db4 VA: 0x75950e0db4
	public Void .ctor() { }
	// RVA: 0x2ac8e5c VA: 0x75950e0e5c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ac8e64 VA: 0x75950e0e64
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2ac8e6c VA: 0x75950e0e6c
	private Void <>xLuaBaseProxy_OnExit() { }
}
```