# SiracusaCharTaskRingRewardState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaCharTaskRingRewardView _view`

- `UIAnimationLocation _enterAnim`


## Methods

- `Void EventOnBtnReward()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext, Boolean)`

- `Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharTaskRingRewardState : PopupFloatState, ISiracusaReplaceable
{
	private SiracusaCharTaskRingRewardView _view; // 0x70
	private UIAnimationLocation _enterAnim; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_DealWithOtherStateBeforeTransStart; // 0x18
	private static DelegateBridge __Hotfix0_DealWithOtherStateWenTransEnd; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBtnReward; // 0x28
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x23eb334 VA: 0x7594a03334
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23eb398 VA: 0x7594a03398
	protected override Void OnEnter() { }
	// RVA: 0x23eb674 VA: 0x7594a03674
	protected override Void OnExit() { }
	// RVA: 0x23eb770 VA: 0x7594a03770
	protected sealed override Void DealWithOtherStateBeforeTransStart(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x23eb8c8 VA: 0x7594a038c8
	protected sealed override Void DealWithOtherStateWenTransEnd(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x23eba20 VA: 0x7594a03a20
	public Void EventOnBtnReward() { }
	// RVA: 0x23ebdc4 VA: 0x7594a03dc4
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x23ebeac VA: 0x7594a03eac
	public Void .ctor() { }
	// RVA: 0x23ebf1c VA: 0x7594a03f1c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x23ebf24 VA: 0x7594a03f24
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x23ebf2c VA: 0x7594a03f2c
	private Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext P0, Boolean P1) { }
	// RVA: 0x23ebf58 VA: 0x7594a03f58
	private Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext P0, Boolean P1) { }
}
```