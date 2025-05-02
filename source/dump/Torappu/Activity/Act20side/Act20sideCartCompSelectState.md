# Act20sideCartCompSelectState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Act20sideCartCompSelectStateBean _stateBean`

- `AnimationWrapper _animWrapper`


## Methods

- `Void SetComp(String)`

- `Void SetPos(CartAccessoryPos)`

- `Void ConfirmSelectComp()`

- `Void _ConfirmBattle()`

- `Void _ConfirmExhibt()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <_ConfirmBattle>b__9_0(CarExhibitionPickResponse)`

- `Void <_ConfirmExhibt>b__10_0(ExhibitionCarConfirmResponse)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCartCompSelectState : PopupFloatState
{
	private const String ANIM_PARAM; // 0x0
	private Act20sideCartCompSelectStateBean _stateBean; // 0x70
	private AnimationWrapper _animWrapper; // 0x78
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_SetComp; // 0x18
	private static DelegateBridge __Hotfix0_SetPos; // 0x20
	private static DelegateBridge __Hotfix0_ConfirmSelectComp; // 0x28
	private static DelegateBridge __Hotfix0__ConfirmBattle; // 0x30
	private static DelegateBridge __Hotfix0__ConfirmExhibt; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x32efd14 VA: 0x7595907d14
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x32efea8 VA: 0x7595907ea8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32eff10 VA: 0x7595907f10
	protected override Void OnEnter() { }
	// RVA: 0x32effac VA: 0x7595907fac
	public Void SetComp(String compId) { }
	// RVA: 0x32f008c VA: 0x759590808c
	public Void SetPos(CartAccessoryPos pos) { }
	// RVA: 0x32f016c VA: 0x759590816c
	public Void ConfirmSelectComp() { }
	// RVA: 0x32f0214 VA: 0x7595908214
	private Void _ConfirmBattle() { }
	// RVA: 0x32f05d4 VA: 0x75959085d4
	private Void _ConfirmExhibt() { }
	// RVA: 0x32f09a4 VA: 0x75959089a4
	public Void .ctor() { }
	// RVA: 0x32f0a14 VA: 0x7595908a14
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x32f0a3c VA: 0x7595908a3c
	private Void <_ConfirmBattle>b__9_0(CarExhibitionPickResponse response) { }
	// RVA: 0x32f0af0 VA: 0x7595908af0
	private Void <_ConfirmExhibt>b__10_0(ExhibitionCarConfirmResponse response) { }
	// RVA: 0x32f0ba4 VA: 0x7595908ba4
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x32f0bcc VA: 0x7595908bcc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```