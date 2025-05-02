# SiracusaCharSelectGotoState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaCharSelectGotoView _view`

- `Coroutine m_coCloseSelf`


## Methods

- `Void CloseSelfDirectly()`

- `Void _CloseSelf(Boolean)`

- `IEnumerator _CoCloseSelf(Boolean)`

- `Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext, Boolean)`

- `Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectGotoState : PopupFloatState, ISiracusaReplaceable
{
	private SiracusaCharSelectGotoView _view; // 0x70
	private const Single CLOSE_SELF_DELAY; // 0x0
	private Coroutine m_coCloseSelf; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_DealWithOtherStateBeforeTransStart; // 0x8
	private static DelegateBridge __Hotfix0_DealWithOtherStateWenTransEnd; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_CloseSelfDirectly; // 0x20
	private static DelegateBridge __Hotfix0__CloseSelf; // 0x28
	private static DelegateBridge __Hotfix0__CoCloseSelf; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x23ecbac VA: 0x7594a04bac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23ecc10 VA: 0x7594a04c10
	protected sealed override Void DealWithOtherStateBeforeTransStart(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x23ecd68 VA: 0x7594a04d68
	protected sealed override Void DealWithOtherStateWenTransEnd(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x23ecec0 VA: 0x7594a04ec0
	protected override Void OnEnter() { }
	// RVA: 0x23ed1cc VA: 0x7594a051cc
	public Void CloseSelfDirectly() { }
	// RVA: 0x23ed08c VA: 0x7594a0508c
	private Void _CloseSelf(Boolean hasDelay) { }
	// RVA: 0x23ed238 VA: 0x7594a05238
	private IEnumerator _CoCloseSelf(Boolean hasDelay) { }
	// RVA: 0x23ed328 VA: 0x7594a05328
	public Void .ctor() { }
	// RVA: 0x23ed398 VA: 0x7594a05398
	private Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext P0, Boolean P1) { }
	// RVA: 0x23ed3c4 VA: 0x7594a053c4
	private Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext P0, Boolean P1) { }
	// RVA: 0x23ed3f0 VA: 0x7594a053f0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```