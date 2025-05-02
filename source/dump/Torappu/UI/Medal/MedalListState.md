# MedalListState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalGroupListView _listView`

- `MedalListStateBean _stateBean`


## Methods

- `Void OnGetMedalReward(MedalCommonViewModel)`

- `Void _OnReceiveItemSucceed(GetRewardMedalResponse)`

- `IEnumerator ReceiveItemsCoroutine(List`1)`

- `Void OnClickMedalEvent(MedalCommonViewModel)`

- `Void OnJumpToGroupList(String)`

- `Void <ReceiveItemsCoroutine>b__8_0()`

- `Void <>xLuaBaseProxy_SetRootViewActive(CanvasGroup, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListState : PopupFadeState, IMedalListFilterHandler
{
	private MedalGroupListView _listView; // 0x70
	private MedalListStateBean _stateBean; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_SetRootViewActive; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnGetMedalReward; // 0x20
	private static DelegateBridge __Hotfix0__OnReceiveItemSucceed; // 0x28
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_OnClickMedalEvent; // 0x38
	private static DelegateBridge __Hotfix0_OnJumpToGroupList; // 0x40
	private static DelegateBridge __Hotfix0_OnMedalFilterChanged; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2797088 VA: 0x7594daf088
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27970f0 VA: 0x7594daf0f0
	protected override Void SetRootViewActive(CanvasGroup rootView, Boolean active) { }
	// RVA: 0x279717c VA: 0x7594daf17c
	protected override Void OnEnter() { }
	// RVA: 0x27972e4 VA: 0x7594daf2e4
	protected override Void OnResume() { }
	// RVA: 0x2797574 VA: 0x7594daf574
	public Void OnGetMedalReward(MedalCommonViewModel viewModel) { }
	// RVA: 0x27977b0 VA: 0x7594daf7b0
	private Void _OnReceiveItemSucceed(GetRewardMedalResponse response) { }
	// RVA: 0x27978a0 VA: 0x7594daf8a0
	public IEnumerator ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x2797998 VA: 0x7594daf998
	public Void OnClickMedalEvent(MedalCommonViewModel viewModel) { }
	// RVA: 0x2797b40 VA: 0x7594dafb40
	public Void OnJumpToGroupList(String groupId) { }
	// RVA: 0x2797c10 VA: 0x7594dafc10
	public virtual Void OnMedalFilterChanged() { }
	// RVA: 0x2797c90 VA: 0x7594dafc90
	public Void .ctor() { }
	// RVA: 0x2797d00 VA: 0x7594dafd00
	private Void <ReceiveItemsCoroutine>b__8_0() { }
	// RVA: 0x2797d3c VA: 0x7594dafd3c
	private Void <>xLuaBaseProxy_SetRootViewActive(CanvasGroup P0, Boolean P1) { }
	// RVA: 0x2797d48 VA: 0x7594dafd48
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2797d50 VA: 0x7594dafd50
	private Void <>xLuaBaseProxy_OnResume() { }
}
```