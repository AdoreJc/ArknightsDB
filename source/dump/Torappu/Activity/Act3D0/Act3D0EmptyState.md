# Act3D0EmptyState

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `GameObject _topMenu`

- `Act3D0GachaBoxStateBean _stateBean`


## Methods

- `Void _OnCampSelected(Object)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0EmptyState : State
{
	private GameObject _topMenu; // 0x50
	private Act3D0GachaBoxStateBean _stateBean; // 0x58
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0__OnCampSelected; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x322e220 VA: 0x7595846220
	public override IStateBean GetCacheBean() { }
	// RVA: 0x322e288 VA: 0x7595846288
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x322e464 VA: 0x7595846464
	protected override Void OnEnter() { }
	// RVA: 0x322e618 VA: 0x7595846618
	protected override Void OnExit() { }
	// RVA: 0x322e798 VA: 0x7595846798
	private Void _OnCampSelected(Object _) { }
	// RVA: 0x322e82c VA: 0x759584682c
	protected override Void OnResume() { }
	// RVA: 0x322e8dc VA: 0x75958468dc
	public Void .ctor() { }
	// RVA: 0x322e94c VA: 0x759584694c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x322e954 VA: 0x7595846954
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x322e95c VA: 0x759584695c
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x322e964 VA: 0x7595846964
	private Void <>xLuaBaseProxy_OnResume() { }
}
```