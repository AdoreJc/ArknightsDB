# MedalBarListState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalShowBarListView _barListView`

- `MedalListStateBean _stateBean`


## Methods

- `Void OnGetMedalReward(MedalCommonViewModel)`

- `Void _OnReceiveItemSucceed(GetRewardMedalResponse)`

- `IEnumerator ReceiveItemsCoroutine(List`1)`

- `Void OnClickMedalEvent(MedalCommonViewModel)`

- `Void OnJumpToGroupList(String)`

- `Void OnJumpToMedal(String)`

- `Void <get_cacheHandler>b__5_1(StateRuntime)`

- `Void <ReceiveItemsCoroutine>b__12_0()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalBarListState : PopupFadeState, IMedalListFilterHandler
{
	private MedalShowBarListView _barListView; // 0x70
	private MedalListStateBean _stateBean; // 0x78
	private StateCacheHandler`1 m_cacheHandler; // 0x80
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnGetMedalReward; // 0x28
	private static DelegateBridge __Hotfix0__OnReceiveItemSucceed; // 0x30
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_OnClickMedalEvent; // 0x40
	private static DelegateBridge __Hotfix0_OnJumpToGroupList; // 0x48
	private static DelegateBridge __Hotfix0_OnJumpToMedal; // 0x50
	private static DelegateBridge __Hotfix0_OnMedalFilterChanged; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2794940 VA: 0x7594dac940
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2794b30 VA: 0x7594dacb30
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2794b98 VA: 0x7594dacb98
	protected override Void OnExit() { }
	// RVA: 0x2794c28 VA: 0x7594dacc28
	protected override Void OnEnter() { }
	// RVA: 0x2794d6c VA: 0x7594dacd6c
	protected override Void OnResume() { }
	// RVA: 0x2794e24 VA: 0x7594dace24
	public Void OnGetMedalReward(MedalCommonViewModel viewModel) { }
	// RVA: 0x2795060 VA: 0x7594dad060
	private Void _OnReceiveItemSucceed(GetRewardMedalResponse response) { }
	// RVA: 0x2795150 VA: 0x7594dad150
	public IEnumerator ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x2795248 VA: 0x7594dad248
	public Void OnClickMedalEvent(MedalCommonViewModel viewModel) { }
	// RVA: 0x27952c8 VA: 0x7594dad2c8
	public Void OnJumpToGroupList(String groupId) { }
	// RVA: 0x2795398 VA: 0x7594dad398
	public Void OnJumpToMedal(String medalId) { }
	// RVA: 0x27954cc VA: 0x7594dad4cc
	public virtual Void OnMedalFilterChanged() { }
	// RVA: 0x279554c VA: 0x7594dad54c
	public Void .ctor() { }
	// RVA: 0x27955bc VA: 0x7594dad5bc
	private Void <get_cacheHandler>b__5_1(StateRuntime runtime) { }
	// RVA: 0x2795650 VA: 0x7594dad650
	private Void <ReceiveItemsCoroutine>b__12_0() { }
	// RVA: 0x279568c VA: 0x7594dad68c
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x2795694 VA: 0x7594dad694
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x279569c VA: 0x7594dad69c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27956a4 VA: 0x7594dad6a4
	private Void <>xLuaBaseProxy_OnResume() { }
}
```