# ActivityFirstEmptyState

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityFirstStateBean _stateBean`

- `GameObject _topMenu`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstEmptyState : State
{
	private ActivityFirstStateBean _stateBean; // 0x50
	private GameObject _topMenu; // 0x58
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x348d290 VA: 0x7595aa5290
	public override IStateBean GetCacheBean() { }
	// RVA: 0x348d2f8 VA: 0x7595aa52f8
	protected override Void OnEnter() { }
	// RVA: 0x348d440 VA: 0x7595aa5440
	protected override Void OnResume() { }
	// RVA: 0x348d4e4 VA: 0x7595aa54e4
	public Void .ctor() { }
	// RVA: 0x348d554 VA: 0x7595aa5554
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x348d55c VA: 0x7595aa555c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```