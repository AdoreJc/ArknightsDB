# ActivityFirstMicroMapState

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityFirstStateBean _stateBean`

- `GameObject _topMenu`


## Methods

- `Void OnConfirm()`

- `Void ChangeZoneSelected(String)`

- `Void ChangeZoneLeft()`

- `Void ChangeZoneRight()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMicroMapState : PopupFloatState
{
	private ActivityFirstStateBean _stateBean; // 0x70
	private GameObject _topMenu; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x10
	private static DelegateBridge __Hotfix0_ChangeZoneSelected; // 0x18
	private static DelegateBridge __Hotfix0_ChangeZoneLeft; // 0x20
	private static DelegateBridge __Hotfix0_ChangeZoneRight; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x348d6bc VA: 0x7595aa56bc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x348d724 VA: 0x7595aa5724
	protected override Void OnEnter() { }
	// RVA: 0x348d80c VA: 0x7595aa580c
	public Void OnConfirm() { }
	// RVA: 0x348d9c4 VA: 0x7595aa59c4
	public Void ChangeZoneSelected(String zoneId) { }
	// RVA: 0x348da98 VA: 0x7595aa5a98
	public Void ChangeZoneLeft() { }
	// RVA: 0x348dcb4 VA: 0x7595aa5cb4
	public Void ChangeZoneRight() { }
	// RVA: 0x348ded8 VA: 0x7595aa5ed8
	public Void .ctor() { }
	// RVA: 0x348df48 VA: 0x7595aa5f48
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```