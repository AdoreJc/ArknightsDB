# UICharacterSortFilterState

**Namespace:** `Torappu.UI`


## Fields

- `UICharacterSortFilterStateBean _stateBean`

- `UICharacterSortGroupOnFloat _sortGroup`

- `UICharacterFilterGroupOnFloat _filterGroup`


## Methods

- `Void OnBackgroundClicked()`

- `Void OnConfirmClicked()`

- `Void OnCancelClicked()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortFilterState : PopupFloatState
{
	private const Single ANIMATION_DURATION; // 0x0
	private UICharacterSortFilterStateBean _stateBean; // 0x70
	private UICharacterSortGroupOnFloat _sortGroup; // 0x78
	private UICharacterFilterGroupOnFloat _filterGroup; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnBackgroundClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2117bf0 VA: 0x759472fbf0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2117c58 VA: 0x759472fc58
	protected override Void OnResume() { }
	// RVA: 0x2117d00 VA: 0x759472fd00
	public Void OnBackgroundClicked() { }
	// RVA: 0x2117d74 VA: 0x759472fd74
	public Void OnConfirmClicked() { }
	// RVA: 0x2117eb0 VA: 0x759472feb0
	public Void OnCancelClicked() { }
	// RVA: 0x2117f24 VA: 0x759472ff24
	public Void .ctor() { }
	// RVA: 0x2117f94 VA: 0x759472ff94
	private Void <>xLuaBaseProxy_OnResume() { }
}
```