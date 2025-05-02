# UICharacterSortTypeGroup

**Namespace:** `Torappu.UI`


## Fields

- `UICharacterSortTypeCustomableItem _customSortTypeItem`

- `Action m_btnFilterClickListener`

- `Boolean m_isInited`


## Properties

- `Action btnFilterClickListener`


## Methods

- `Void _InitIfNot()`

- `Void set_sortTypeListener(Action`1)`

- `Void set_btnFilterClickListener(Action)`

- `Void Render(CharacterSortType)`

- `Void Render(CharacterCardSortTypeViewModel)`

- `Void _OnSortTypeChange(CharacterSortType)`

- `Void _OnSortPanelShow()`

- `Void EventOnBtnFilterClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortTypeGroup : MonoBehaviour, IHotfixable
{
	private UICharacterSortTypeItem[] _sortTypeItems; // 0x18
	private UICharacterSortTypeCustomableItem _customSortTypeItem; // 0x20
	private Action`1 m_sortTypeListener; // 0x28
	private Action m_btnFilterClickListener; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_set_sortTypeListener; // 0x8
	private static DelegateBridge __Hotfix0_set_btnFilterClickListener; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix1_Render; // 0x20
	private static DelegateBridge __Hotfix0__OnSortTypeChange; // 0x28
	private static DelegateBridge __Hotfix0__OnSortPanelShow; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnFilterClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Action`1 sortTypeListener { set; }
	public Action btnFilterClickListener { set; }

	// RVA: 0x2134bec VA: 0x759474cbec
	private Void _InitIfNot() { }
	// RVA: 0x2134df8 VA: 0x759474cdf8
	public Void set_sortTypeListener(Action`1 value) { }
	// RVA: 0x2134e7c VA: 0x759474ce7c
	public Void set_btnFilterClickListener(Action value) { }
	// RVA: 0x2134f00 VA: 0x759474cf00
	public Void Render(CharacterSortType sortType) { }
	// RVA: 0x2134fdc VA: 0x759474cfdc
	public Void Render(CharacterCardSortTypeViewModel viewModel) { }
	// RVA: 0x21350cc VA: 0x759474d0cc
	private Void _OnSortTypeChange(CharacterSortType sortType) { }
	// RVA: 0x213516c VA: 0x759474d16c
	private Void _OnSortPanelShow() { }
	// RVA: 0x21351f0 VA: 0x759474d1f0
	public Void EventOnBtnFilterClick() { }
	// RVA: 0x2135258 VA: 0x759474d258
	public Void .ctor() { }
}
```