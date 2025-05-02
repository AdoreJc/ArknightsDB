# MedalGroupState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalListStateBean _stateBean`

- `MedalGroupTemplateListView _listView`


## Methods

- `Void OnJumpToBarListGroup(String)`

- `Void OnMedalFilterChanged()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupState : PopupFadeState, IMedalListFilterHandler
{
	private MedalListStateBean _stateBean; // 0x70
	private MedalGroupTemplateListView _listView; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnJumpToBarListGroup; // 0x10
	private static DelegateBridge __Hotfix0_OnMedalFilterChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2796c64 VA: 0x7594daec64
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2796ccc VA: 0x7594daeccc
	protected override Void OnEnter() { }
	// RVA: 0x2796e00 VA: 0x7594daee00
	public Void OnJumpToBarListGroup(String groupId) { }
	// RVA: 0x2796ed0 VA: 0x7594daeed0
	public Void OnMedalFilterChanged() { }
	// RVA: 0x2797010 VA: 0x7594daf010
	public Void .ctor() { }
	// RVA: 0x2797080 VA: 0x7594daf080
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```