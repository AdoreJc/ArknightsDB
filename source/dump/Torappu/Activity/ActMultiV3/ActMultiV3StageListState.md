# ActMultiV3StageListState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _viewHolder`

- `RectTransform _topMenuContainer`

- `ActMultiV3StageListView _viewPrefab`

- `Image _imgToken`

- `Boolean m_inited`

- `ActMultiV3StageListView m_view`

- `StateBean m_stateBean`

- `UICompDialogMgr m_dialogMgr`

- `Int32 m_infoDialogInst`

- `Int32 m_rewardDialogInst`


## Methods

- `Void _InitIfNot()`

- `Void _OnJumpToStageListDetailState(IStateBean)`

- `Boolean _CheckUIStable()`

- `Void _OnTabClicked(Int64)`

- `Void _OnStageClicked(String)`

- `Void _OnBtnInfoClicked()`

- `Void _ClearStageNewTrackpoint()`

- `Void OnBackClicked()`

- `Void OnBtnRewardClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListState : ActMultiV3StageListViewState
{
	private RectTransform _viewHolder; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private ActMultiV3StageListView _viewPrefab; // 0x80
	private Image _imgToken; // 0x88
	private Boolean m_inited; // 0x90
	private ActMultiV3StageListView m_view; // 0x98
	private StateBean m_stateBean; // 0xa0
	private UICompDialogMgr m_dialogMgr; // 0xa8
	private Int32 m_infoDialogInst; // 0xb0
	private Int32 m_rewardDialogInst; // 0xb4
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x28
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToStageListDetailState; // 0x38
	private static DelegateBridge __Hotfix0__CheckUIStable; // 0x40
	private static DelegateBridge __Hotfix0__OnTabClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnStageClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnBtnInfoClicked; // 0x58
	private static DelegateBridge __Hotfix0__ClearStageNewTrackpoint; // 0x60
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x68
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x70
	private static DelegateBridge __Hotfix0_OnBtnRewardClicked; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x314d81c VA: 0x759576581c
	private Void _InitIfNot() { }
	// RVA: 0x314d9f0 VA: 0x75957659f0
	protected override Void OnEnter() { }
	// RVA: 0x314db80 VA: 0x7595765b80
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x314de08 VA: 0x7595765e08
	protected override Void OnExit() { }
	// RVA: 0x314e058 VA: 0x7595766058
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x314e5e4 VA: 0x75957665e4
	public override Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x314e668 VA: 0x7595766668
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x314e7e0 VA: 0x75957667e0
	private Void _OnJumpToStageListDetailState(IStateBean stateBean) { }
	// RVA: 0x314ec7c VA: 0x7595766c7c
	private Boolean _CheckUIStable() { }
	// RVA: 0x314e168 VA: 0x7595766168
	private Void _OnTabClicked(Int64 msg) { }
	// RVA: 0x314e260 VA: 0x7595766260
	private Void _OnStageClicked(String stageId) { }
	// RVA: 0x314e420 VA: 0x7595766420
	private Void _OnBtnInfoClicked() { }
	// RVA: 0x314de7c VA: 0x7595765e7c
	private Void _ClearStageNewTrackpoint() { }
	// RVA: 0x314eec4 VA: 0x7595766ec4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x314ef2c VA: 0x7595766f2c
	public Void OnBackClicked() { }
	// RVA: 0x314f038 VA: 0x7595767038
	public Void OnBtnRewardClicked() { }
	// RVA: 0x314f1fc VA: 0x75957671fc
	public Void .ctor() { }
	// RVA: 0x314f350 VA: 0x7595767350
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x314f358 VA: 0x7595767358
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x314f364 VA: 0x7595767364
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x314f36c VA: 0x759576736c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```