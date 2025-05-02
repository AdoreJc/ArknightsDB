# HomeActivityAvgState

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeMainStateBean _stateBean`


## Methods

- `Void _OnStoryEnd(Story)`

- `IEnumerator _TryDissmissSelf()`

- `Void <>n__0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeActivityAvgState : State
{
	private HomeMainStateBean _stateBean; // 0x50
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0__OnStoryEnd; // 0x18
	private static DelegateBridge __Hotfix0__TryDissmissSelf; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x27e132c VA: 0x7594df932c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27e1394 VA: 0x7594df9394
	protected override Void OnEnter() { }
	// RVA: 0x27e1598 VA: 0x7594df9598
	protected override Void OnExit() { }
	// RVA: 0x27e14e4 VA: 0x7594df94e4
	private Void _OnStoryEnd(Story story) { }
	// RVA: 0x27e1648 VA: 0x7594df9648
	private IEnumerator _TryDissmissSelf() { }
	// RVA: 0x27e171c VA: 0x7594df971c
	public Void .ctor() { }
	// RVA: 0x27e178c VA: 0x7594df978c
	private Void <>n__0() { }
	// RVA: 0x27e1794 VA: 0x7594df9794
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27e179c VA: 0x7594df979c
	private Void <>xLuaBaseProxy_OnExit() { }
}
```