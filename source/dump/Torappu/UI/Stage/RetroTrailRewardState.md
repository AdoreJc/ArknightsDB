# RetroTrailRewardState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageStateBean m_stateBean`

- `RetroTrailRewardView _view`

- `TopMenuDynamicPrefabInstHolder _instHolder`

- `SideStoryViewModel m_cacheViewModel`


## Methods

- `IEnumerator ReceiveItemsCoroutine(List`1)`

- `Void OnTrailRewardGet(String)`

- `Void ToCharacterPotentialState()`

- `Void ToTrailRuleState()`

- `Void _OnJumpToUpPotentialState(IStateBean)`

- `Void _TopMenuProcessor(GameObject)`

- `Void <OnTrailRewardGet>b__6_0(RetroTrailRewardResponse)`

- `Void <_TopMenuProcessor>b__11_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class RetroTrailRewardState : PopupFadeState
{
	private StageStateBean m_stateBean; // 0x70
	private RetroTrailRewardView _view; // 0x78
	private TopMenuDynamicPrefabInstHolder _instHolder; // 0x80
	private SideStoryViewModel m_cacheViewModel; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_OnTrailRewardGet; // 0x10
	private static DelegateBridge __Hotfix0_ToCharacterPotentialState; // 0x18
	private static DelegateBridge __Hotfix0_ToTrailRuleState; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0__OnJumpToUpPotentialState; // 0x30
	private static DelegateBridge __Hotfix0__TopMenuProcessor; // 0x38
	private static DelegateBridge __Hotfix0_OnEnter; // 0x40
	private static DelegateBridge __Hotfix0_OnResume; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2f635dc VA: 0x759557b5dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f63644 VA: 0x759557b644
	public IEnumerator ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x2f6373c VA: 0x759557b73c
	public Void OnTrailRewardGet(String i_rewardId) { }
	// RVA: 0x2f63944 VA: 0x759557b944
	public Void ToCharacterPotentialState() { }
	// RVA: 0x2f63a48 VA: 0x759557ba48
	public Void ToTrailRuleState() { }
	// RVA: 0x2f63b54 VA: 0x759557bb54
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2f63ccc VA: 0x759557bccc
	private Void _OnJumpToUpPotentialState(IStateBean stateBean) { }
	// RVA: 0x2f63e70 VA: 0x759557be70
	private Void _TopMenuProcessor(GameObject topMenuObj) { }
	// RVA: 0x2f63f70 VA: 0x759557bf70
	protected override Void OnEnter() { }
	// RVA: 0x2f640d0 VA: 0x759557c0d0
	protected override Void OnResume() { }
	// RVA: 0x2f641b8 VA: 0x759557c1b8
	public Void .ctor() { }
	// RVA: 0x2f64228 VA: 0x759557c228
	private Void <OnTrailRewardGet>b__6_0(RetroTrailRewardResponse response) { }
	// RVA: 0x2f64320 VA: 0x759557c320
	private Void <_TopMenuProcessor>b__11_0() { }
	// RVA: 0x2f64340 VA: 0x759557c340
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2f64348 VA: 0x759557c348
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f64350 VA: 0x759557c350
	private Void <>xLuaBaseProxy_OnResume() { }
}
```