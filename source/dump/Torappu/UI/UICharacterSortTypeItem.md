# UICharacterSortTypeItem

**Namespace:** `Torappu.UI`


## Fields

- `CharacterSortType _firstSortType`

- `CharacterSortType _secondSortType`

- `GameObject _lightMask`

- `String m_pageName`

- `ThreeStateToggle m_toggle`

- `Boolean m_isInited`


## Methods

- `Void set_onSortTypeChanged(Action`1)`

- `Void _InitIfNot()`

- `Void _OnToggleClick(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortTypeItem : UICharacterSortCommonItem
{
	private CharacterSortType _firstSortType; // 0x18
	private CharacterSortType _secondSortType; // 0x1c
	private Text[] _sortTitles; // 0x20
	private Image[] _sortIcons; // 0x28
	private GameObject _lightMask; // 0x30
	private String m_pageName; // 0x38
	private ThreeStateToggle m_toggle; // 0x40
	private Boolean m_isInited; // 0x48
	private Action`1 <onSortTypeChanged>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onSortTypeChanged; // 0x0
	private static DelegateBridge __Hotfix0_set_onSortTypeChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnToggleClick; // 0x18
	private static DelegateBridge __Hotfix0_RenderSortItem; // 0x20
	private static DelegateBridge __Hotfix0_NotifySortTypeChanged; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onSortTypeChanged { get; set; }

	// RVA: 0x213574c VA: 0x759474d74c
	private Action`1 get_onSortTypeChanged() { }
	// RVA: 0x21333d4 VA: 0x759474b3d4
	public Void set_onSortTypeChanged(Action`1 value) { }
	// RVA: 0x21357b4 VA: 0x759474d7b4
	private Void _InitIfNot() { }
	// RVA: 0x21358e0 VA: 0x759474d8e0
	private Void _OnToggleClick(State state) { }
	// RVA: 0x21359bc VA: 0x759474d9bc
	public override Void RenderSortItem(CharacterSortTypePair sortPair, Boolean lightMode) { }
	// RVA: 0x2135bf0 VA: 0x759474dbf0
	public override Void NotifySortTypeChanged(CharacterSortType sortType) { }
	// RVA: 0x2135cb0 VA: 0x759474dcb0
	public Void .ctor() { }
}
```