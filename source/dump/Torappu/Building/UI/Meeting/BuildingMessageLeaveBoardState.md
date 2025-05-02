# BuildingMessageLeaveBoardState

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `UIAnimationLocation _animEntry`

- `Image _blurBackground`

- `BuildingTwoContentNotify _socialRewardNotify`

- `BuildingMessageLeaveBoardTopView _topView`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BuildingMessageLeaveBoardVisitorView _visitorsView`

- `BuildingMessageLeaveBoardRewardItemView _rewardItemView`

- `BuildingMessageLeaveBoardBottomInfoView _bottomInfoView`

- `BuildingMessageLeaveBoardStateBean m_stateBean`

- `Boolean m_isInited`

- `Tween m_entryTween`

- `Int32 m_visitorInfoDlgInstId`

- `Int32 m_lastWeekRewardDlgInstId`


## Methods

- `Void _InitIfNot()`

- `Boolean _TryOpenLastWeekRewardView(BuildingMessageLeaveBoardModel)`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void _InitViews(BuildingMessageLeaveBoardProperty)`

- `IEnumerator _PlayEntryAnim()`

- `Void _InitTopMenu()`

- `Void _OnClickClose()`

- `Void _OnGetSocialPointProceed(BuildingPayloadConfirmMessageBoardRewardResponse)`

- `Void _ShowSocialPointRewardToast(Int32)`

- `Void _EventOnClickVisitorAvatar(IMessageBoardVisitorData)`

- `Void EventOnClickGetSocialPointReward()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Boolean <_PlayEntryAnim>b__20_0()`

- `Void <_InitTopMenu>b__21_0(GameObject)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardState : State, IPlayerDataListener, IHotfixable, ICompDialogCallBack
{
	private UIAnimationLocation _animEntry; // 0x50
	private Image _blurBackground; // 0x60
	private BuildingTwoContentNotify _socialRewardNotify; // 0x68
	private BuildingMessageLeaveBoardTopView _topView; // 0x70
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x78
	private BuildingMessageLeaveBoardVisitorView _visitorsView; // 0x80
	private BuildingMessageLeaveBoardRewardItemView _rewardItemView; // 0x88
	private BuildingMessageLeaveBoardBottomInfoView _bottomInfoView; // 0x90
	private BuildingMessageLeaveBoardStateBean m_stateBean; // 0x98
	private Boolean m_isInited; // 0xa0
	private Tween m_entryTween; // 0xa8
	private Int32 m_visitorInfoDlgInstId; // 0xb0
	private Int32 m_lastWeekRewardDlgInstId; // 0xb4
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__TryOpenLastWeekRewardView; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x28
	private static DelegateBridge __Hotfix0__InitViews; // 0x30
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x38
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x40
	private static DelegateBridge __Hotfix0__OnClickClose; // 0x48
	private static DelegateBridge __Hotfix0__OnGetSocialPointProceed; // 0x50
	private static DelegateBridge __Hotfix0__ShowSocialPointRewardToast; // 0x58
	private static DelegateBridge __Hotfix0__EventOnClickVisitorAvatar; // 0x60
	private static DelegateBridge __Hotfix0_EventOnClickGetSocialPointReward; // 0x68
	private static DelegateBridge __Hotfix0_OnEnable; // 0x70
	private static DelegateBridge __Hotfix0_OnDisable; // 0x78
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x80
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x3dc3294 VA: 0x75963db294
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3dc32fc VA: 0x75963db2fc
	private Void _InitIfNot() { }
	// RVA: 0x3dc352c VA: 0x75963db52c
	protected override Void OnEnter() { }
	// RVA: 0x3dc3ac0 VA: 0x75963dbac0
	private Boolean _TryOpenLastWeekRewardView(BuildingMessageLeaveBoardModel model) { }
	// RVA: 0x3dc3e50 VA: 0x75963dbe50
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x3dc3f08 VA: 0x75963dbf08
	public Void OnPlayerDataChanged() { }
	// RVA: 0x3dc3828 VA: 0x75963db828
	private Void _InitViews(BuildingMessageLeaveBoardProperty property) { }
	// RVA: 0x3dc3d9c VA: 0x75963dbd9c
	private IEnumerator _PlayEntryAnim() { }
	// RVA: 0x3dc3468 VA: 0x75963db468
	private Void _InitTopMenu() { }
	// RVA: 0x3dc40b8 VA: 0x75963dc0b8
	private Void _OnClickClose() { }
	// RVA: 0x3dc41f4 VA: 0x75963dc1f4
	private Void _OnGetSocialPointProceed(BuildingPayloadConfirmMessageBoardRewardResponse response) { }
	// RVA: 0x3dc4390 VA: 0x75963dc390
	private Void _ShowSocialPointRewardToast(Int32 rewardCount) { }
	// RVA: 0x3dc451c VA: 0x75963dc51c
	private Void _EventOnClickVisitorAvatar(IMessageBoardVisitorData visitorData) { }
	// RVA: 0x3dc47a4 VA: 0x75963dc7a4
	public Void EventOnClickGetSocialPointReward() { }
	// RVA: 0x3dc4984 VA: 0x75963dc984
	private Void OnEnable() { }
	// RVA: 0x3dc49f0 VA: 0x75963dc9f0
	private Void OnDisable() { }
	// RVA: 0x3dc4a5c VA: 0x75963dca5c
	private Void OnDestroy() { }
	// RVA: 0x3dc4b6c VA: 0x75963dcb6c
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x3dc4c20 VA: 0x75963dcc20
	public Void .ctor() { }
	// RVA: 0x3dc4c90 VA: 0x75963dcc90
	private Boolean <_PlayEntryAnim>b__20_0() { }
	// RVA: 0x3dc4ca4 VA: 0x75963dcca4
	private Void <_InitTopMenu>b__21_0(GameObject obj) { }
	// RVA: 0x3dc4d68 VA: 0x75963dcd68
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```