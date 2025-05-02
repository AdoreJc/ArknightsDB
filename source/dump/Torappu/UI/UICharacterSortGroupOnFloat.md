# UICharacterSortGroupOnFloat

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _sortItemContainer`

- `UICharacterSortCommonItem _sortItemPrefab`

- `CharacterSortType m_sortType`

- `String pageName`

- `Boolean useCustomePrefab`

- `Boolean m_isInited`

- `UICharacterHandbookStageCountItem m_stageCntItem`


## Properties

- `CharacterSortType sortType`

- `UICharacterHandbookStageCountItem stageCountItem`


## Methods

- `Void RenderSortGroup()`

- `Void _InitIfNot()`

- `UICharacterSortCommonItem _DealWithCustomItem(CharacterSortTypePair, Boolean)`

- `UICharacterSortTypeItem _GenNormalSortTypeItem(CharacterSortTypePair, Boolean)`

- `Boolean _EnsureShowHandBookSort()`

- `UICharacterSortTypePanelItem _DealWithHandBookSort(CharacterSortTypePair, Boolean)`

- `UICharacterSortTypePanelItem _GenCustomSortTypeItem(CharacterSortTypePair, Boolean)`

- `Void _ClearSortItems()`

- `CharacterSortType get_sortType()`

- `Void set_sortType(CharacterSortType)`

- `UICharacterHandbookStageCountItem get_stageCountItem()`

- `Void _ChangeSortType(CharacterSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortGroupOnFloat : MonoBehaviour, IHotfixable
{
	private RectTransform _sortItemContainer; // 0x18
	private UICharacterSortCommonItem _sortItemPrefab; // 0x20
	private CharacterSortType m_sortType; // 0x28
	public Action`1 onSortCallback; // 0x30
	public String pageName; // 0x38
	public Boolean useCustomePrefab; // 0x40
	private Boolean m_isInited; // 0x41
	private List`1 m_sortItems; // 0x48
	private UICharacterHandbookStageCountItem m_stageCntItem; // 0x50
	private static DelegateBridge __Hotfix0_RenderSortGroup; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__DealWithCustomItem; // 0x10
	private static DelegateBridge __Hotfix0__GenNormalSortTypeItem; // 0x18
	private static DelegateBridge __Hotfix0__EnsureShowHandBookSort; // 0x20
	private static DelegateBridge __Hotfix0__DealWithHandBookSort; // 0x28
	private static DelegateBridge __Hotfix0__GenCustomSortTypeItem; // 0x30
	private static DelegateBridge __Hotfix0__ClearSortItems; // 0x38
	private static DelegateBridge __Hotfix0_get_sortType; // 0x40
	private static DelegateBridge __Hotfix0_set_sortType; // 0x48
	private static DelegateBridge __Hotfix0_get_stageCountItem; // 0x50
	private static DelegateBridge __Hotfix0__ChangeSortType; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public CharacterSortType sortType { get; set; }
	public UICharacterHandbookStageCountItem stageCountItem { get; }

	// RVA: 0x2131ec8 VA: 0x7594749ec8
	public Void RenderSortGroup() { }
	// RVA: 0x2132a84 VA: 0x759474aa84
	private Void _InitIfNot() { }
	// RVA: 0x2132d88 VA: 0x759474ad88
	private UICharacterSortCommonItem _DealWithCustomItem(CharacterSortTypePair sortpair, Boolean lightColorFlag) { }
	// RVA: 0x2132e80 VA: 0x759474ae80
	private UICharacterSortTypeItem _GenNormalSortTypeItem(CharacterSortTypePair sortPair, Boolean lightColor) { }
	// RVA: 0x2133038 VA: 0x759474b038
	private Boolean _EnsureShowHandBookSort() { }
	// RVA: 0x21330e0 VA: 0x759474b0e0
	private UICharacterSortTypePanelItem _DealWithHandBookSort(CharacterSortTypePair sortPair, Boolean lightColor) { }
	// RVA: 0x213320c VA: 0x759474b20c
	private UICharacterSortTypePanelItem _GenCustomSortTypeItem(CharacterSortTypePair sortPair, Boolean lightColor) { }
	// RVA: 0x2132d18 VA: 0x759474ad18
	private Void _ClearSortItems() { }
	// RVA: 0x2133544 VA: 0x759474b544
	public CharacterSortType get_sortType() { }
	// RVA: 0x2131f30 VA: 0x7594749f30
	public Void set_sortType(CharacterSortType value) { }
	// RVA: 0x2131fb0 VA: 0x7594749fb0
	public UICharacterHandbookStageCountItem get_stageCountItem() { }
	// RVA: 0x21335ac VA: 0x759474b5ac
	private Void _ChangeSortType(CharacterSortType sortType) { }
	// RVA: 0x21336cc VA: 0x759474b6cc
	public Void .ctor() { }
}
```