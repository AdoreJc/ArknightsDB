# CommonCharSelectShuffleDefaultView

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `UICharacterStarMarkTopSortItem _startMark`

- `UICharacterSortTypeGroup _sortTypeGrp`

- `UICharacterSortFilterPanel _sortFilterPanel`

- `Boolean m_inited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnStartMarkTopToggle()`

- `Void _EventOnSetSortType(CharacterSortType)`

- `Void _EventOnSetCustomSortType(CharacterSortType)`

- `Void _EventOnSetFilter(CharacterFilterViewModel)`

- `Void _EventOnShowSortPanel()`

- `Void EventOnShowFilterPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectShuffleDefaultView : TemplateCharSelectShuffleViewBase`1
{
	private UICharacterStarMarkTopSortItem _startMark; // 0x30
	private UICharacterSortTypeGroup _sortTypeGrp; // 0x38
	private UICharacterSortFilterPanel _sortFilterPanel; // 0x40
	private Boolean m_inited; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private static DelegateBridge __Hotfix0_OnRenderViewModel; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__EventOnStartMarkTopToggle; // 0x10
	private static DelegateBridge __Hotfix0__EventOnSetSortType; // 0x18
	private static DelegateBridge __Hotfix0__EventOnSetCustomSortType; // 0x20
	private static DelegateBridge __Hotfix0__EventOnSetFilter; // 0x28
	private static DelegateBridge __Hotfix0__EventOnShowSortPanel; // 0x30
	private static DelegateBridge __Hotfix0_EventOnShowFilterPanel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2c55bb8 VA: 0x759526dbb8
	protected override Void OnRenderViewModel() { }
	// RVA: 0x2c55d00 VA: 0x759526dd00
	private Void _InitIfNot() { }
	// RVA: 0x2c55f84 VA: 0x759526df84
	private Void _EventOnStartMarkTopToggle() { }
	// RVA: 0x2c560c8 VA: 0x759526e0c8
	private Void _EventOnSetSortType(CharacterSortType sortType) { }
	// RVA: 0x2c56224 VA: 0x759526e224
	private Void _EventOnSetCustomSortType(CharacterSortType sortType) { }
	// RVA: 0x2c56394 VA: 0x759526e394
	private Void _EventOnSetFilter(CharacterFilterViewModel filter) { }
	// RVA: 0x2c56668 VA: 0x759526e668
	private Void _EventOnShowSortPanel() { }
	// RVA: 0x2c566dc VA: 0x759526e6dc
	public Void EventOnShowFilterPanel() { }
	// RVA: 0x2c56804 VA: 0x759526e804
	public Void .ctor() { }
}
```