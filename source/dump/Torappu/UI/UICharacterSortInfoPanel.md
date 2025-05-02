# UICharacterSortInfoPanel

**Namespace:** `Torappu.UI`


## Fields

- `Image _maskColor`

- `Image _attrIcon`

- `Image _bgImage`

- `Text _attrValue`

- `String pageName`

- `Boolean m_isInited`

- `CharacterCardViewModel m_cachedViewModel`

- `CharacterHandbookStageStatus m_cachedStageStatus`

- `UIPageFinder m_pageFinder`


## Methods

- `Boolean RenderSortInfo(CharacterCardViewModel, CharacterSortType)`

- `Void _RenderCustomStyle(CharacterSortType, CharCardSortInfoStyleData)`

- `Void _RenderDefault(CharacterSortType)`

- `Void _RenderHandBookStageStyle(CharacterSortType, CharCardSortInfoStyleData)`

- `Void _SetHandBookCustomTextColor(Color)`

- `Color _GetHandBookCustomMaskColor(CharacterHandbookStageStatus, CharCardSortInfoStyleData)`

- `CharCardSortInfoStyleData _TryGetSortInfoStyle(CharacterSortType)`

- `Void _InitIfNot()`

- `String _GetAttrValueBySortType(CharacterSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortInfoPanel : MonoBehaviour, IHotfixable
{
	private Image _maskColor; // 0x18
	private Image _attrIcon; // 0x20
	private Image _bgImage; // 0x28
	private Text _attrValue; // 0x30
	private CharCardSortInfoStyleData[] _infoStyles; // 0x38
	public String pageName; // 0x40
	private Boolean m_isInited; // 0x48
	private CharacterCardViewModel m_cachedViewModel; // 0x50
	private CharacterHandbookStageStatus m_cachedStageStatus; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private static DelegateBridge __Hotfix0_RenderSortInfo; // 0x0
	private static DelegateBridge __Hotfix0__RenderCustomStyle; // 0x8
	private static DelegateBridge __Hotfix0__RenderDefault; // 0x10
	private static DelegateBridge __Hotfix0__RenderHandBookStageStyle; // 0x18
	private static DelegateBridge __Hotfix0__SetHandBookCustomTextColor; // 0x20
	private static DelegateBridge __Hotfix0__GetHandBookCustomMaskColor; // 0x28
	private static DelegateBridge __Hotfix0__TryGetSortInfoStyle; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__GetAttrValueBySortType; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2133748 VA: 0x759474b748
	public Boolean RenderSortInfo(CharacterCardViewModel viewModel, CharacterSortType sortType) { }
	// RVA: 0x2133dc4 VA: 0x759474bdc4
	private Void _RenderCustomStyle(CharacterSortType sortType, CharCardSortInfoStyleData style) { }
	// RVA: 0x2134030 VA: 0x759474c030
	private Void _RenderDefault(CharacterSortType sortType) { }
	// RVA: 0x2133eac VA: 0x759474beac
	private Void _RenderHandBookStageStyle(CharacterSortType sortType, CharCardSortInfoStyleData style) { }
	// RVA: 0x21341d0 VA: 0x759474c1d0
	private Void _SetHandBookCustomTextColor(Color textColor) { }
	// RVA: 0x2134104 VA: 0x759474c104
	private Color _GetHandBookCustomMaskColor(CharacterHandbookStageStatus status, CharCardSortInfoStyleData style) { }
	// RVA: 0x21339c4 VA: 0x759474b9c4
	private CharCardSortInfoStyleData _TryGetSortInfoStyle(CharacterSortType sortType) { }
	// RVA: 0x2133928 VA: 0x759474b928
	private Void _InitIfNot() { }
	// RVA: 0x2133b5c VA: 0x759474bb5c
	private String _GetAttrValueBySortType(CharacterSortType sortType) { }
	// RVA: 0x21342bc VA: 0x759474c2bc
	public Void .ctor() { }
}
```