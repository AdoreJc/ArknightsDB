# ItemRepoChooseCharEvolveStateBean

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `UIItemViewModel <itemViewModel>k__BackingField`

- `RarityRank <rarity>k__BackingField`

- `Boolean <clickable>k__BackingField`

- `String <titleText>k__BackingField`

- `String <emptyText>k__BackingField`

- `CharCardType <charCardType>k__BackingField`

- `Int32 <selectedCharInstId>k__BackingField`


## Properties

- `UIItemViewModel itemViewModel`

- `RarityRank rarity`

- `Boolean clickable`

- `String titleText`

- `String emptyText`

- `CharCardType charCardType`

- `Int32 selectedCharInstId`


## Methods

- `UIItemViewModel get_itemViewModel()`

- `Void set_itemViewModel(UIItemViewModel)`

- `RarityRank get_rarity()`

- `Void set_rarity(RarityRank)`

- `Boolean get_clickable()`

- `Void set_clickable(Boolean)`

- `String get_titleText()`

- `Void set_titleText(String)`

- `String get_emptyText()`

- `Void set_emptyText(String)`

- `CharCardType get_charCardType()`

- `Void set_charCardType(CharCardType)`

- `Int32 get_selectedCharInstId()`

- `Void set_selectedCharInstId(Int32)`

- `Void set_characterSorter(CharacterSorter`1)`

- `Void set_characterFilter(CharacterFilter`1)`

- `Void GenerateInput(UIItemViewModel, Boolean)`

- `Boolean _FilterEvolveChar(CharacterCardViewModel)`

- `Boolean _FilterLevelMaxChar(CharacterCardViewModel)`

- `Boolean _FilterSkillMaxChar(CharacterCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharEvolveStateBean : IStateBean, IHotfixable
{
	private UIItemViewModel <itemViewModel>k__BackingField; // 0x10
	private RarityRank <rarity>k__BackingField; // 0x18
	private Boolean <clickable>k__BackingField; // 0x1c
	private String <titleText>k__BackingField; // 0x20
	private String <emptyText>k__BackingField; // 0x28
	private CharCardType <charCardType>k__BackingField; // 0x30
	private Int32 <selectedCharInstId>k__BackingField; // 0x34
	private CharacterSorter`1 <characterSorter>k__BackingField; // 0x38
	private CharacterFilter`1 <characterFilter>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_itemViewModel; // 0x0
	private static DelegateBridge __Hotfix0_set_itemViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_rarity; // 0x10
	private static DelegateBridge __Hotfix0_set_rarity; // 0x18
	private static DelegateBridge __Hotfix0_get_clickable; // 0x20
	private static DelegateBridge __Hotfix0_set_clickable; // 0x28
	private static DelegateBridge __Hotfix0_get_titleText; // 0x30
	private static DelegateBridge __Hotfix0_set_titleText; // 0x38
	private static DelegateBridge __Hotfix0_get_emptyText; // 0x40
	private static DelegateBridge __Hotfix0_set_emptyText; // 0x48
	private static DelegateBridge __Hotfix0_get_charCardType; // 0x50
	private static DelegateBridge __Hotfix0_set_charCardType; // 0x58
	private static DelegateBridge __Hotfix0_get_selectedCharInstId; // 0x60
	private static DelegateBridge __Hotfix0_set_selectedCharInstId; // 0x68
	private static DelegateBridge __Hotfix0_get_characterSorter; // 0x70
	private static DelegateBridge __Hotfix0_set_characterSorter; // 0x78
	private static DelegateBridge __Hotfix0_get_characterFilter; // 0x80
	private static DelegateBridge __Hotfix0_set_characterFilter; // 0x88
	private static DelegateBridge __Hotfix0_GenerateInput; // 0x90
	private static DelegateBridge __Hotfix0__FilterEvolveChar; // 0x98
	private static DelegateBridge __Hotfix0__FilterLevelMaxChar; // 0xa0
	private static DelegateBridge __Hotfix0__FilterSkillMaxChar; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public UIItemViewModel itemViewModel { get; set; }
	public RarityRank rarity { get; set; }
	public Boolean clickable { get; set; }
	public String titleText { get; set; }
	public String emptyText { get; set; }
	public CharCardType charCardType { get; set; }
	public Int32 selectedCharInstId { get; set; }
	public CharacterSorter`1 characterSorter { get; set; }
	public CharacterFilter`1 characterFilter { get; set; }

	// RVA: 0x2d1af4c VA: 0x7595332f4c
	public UIItemViewModel get_itemViewModel() { }
	// RVA: 0x2d1afb4 VA: 0x7595332fb4
	private Void set_itemViewModel(UIItemViewModel value) { }
	// RVA: 0x2d1b038 VA: 0x7595333038
	public RarityRank get_rarity() { }
	// RVA: 0x2d1b0a0 VA: 0x75953330a0
	private Void set_rarity(RarityRank value) { }
	// RVA: 0x2d1b11c VA: 0x759533311c
	public Boolean get_clickable() { }
	// RVA: 0x2d1b184 VA: 0x7595333184
	private Void set_clickable(Boolean value) { }
	// RVA: 0x2d1b204 VA: 0x7595333204
	public String get_titleText() { }
	// RVA: 0x2d1b26c VA: 0x759533326c
	private Void set_titleText(String value) { }
	// RVA: 0x2d1b2f0 VA: 0x75953332f0
	public String get_emptyText() { }
	// RVA: 0x2d1b358 VA: 0x7595333358
	private Void set_emptyText(String value) { }
	// RVA: 0x2d1b3dc VA: 0x75953333dc
	public CharCardType get_charCardType() { }
	// RVA: 0x2d1b444 VA: 0x7595333444
	private Void set_charCardType(CharCardType value) { }
	// RVA: 0x2d1b4c0 VA: 0x75953334c0
	public Int32 get_selectedCharInstId() { }
	// RVA: 0x2d1b528 VA: 0x7595333528
	public Void set_selectedCharInstId(Int32 value) { }
	// RVA: 0x2d1b5a4 VA: 0x75953335a4
	public CharacterSorter`1 get_characterSorter() { }
	// RVA: 0x2d1b60c VA: 0x759533360c
	private Void set_characterSorter(CharacterSorter`1 value) { }
	// RVA: 0x2d1b690 VA: 0x7595333690
	public CharacterFilter`1 get_characterFilter() { }
	// RVA: 0x2d1b6f8 VA: 0x75953336f8
	private Void set_characterFilter(CharacterFilter`1 value) { }
	// RVA: 0x2d1b77c VA: 0x759533377c
	public Void GenerateInput(UIItemViewModel itemViewModel, Boolean clickable) { }
	// RVA: 0x2d1bdc0 VA: 0x7595333dc0
	private Boolean _FilterEvolveChar(CharacterCardViewModel charInfo) { }
	// RVA: 0x2d1be54 VA: 0x7595333e54
	private Boolean _FilterLevelMaxChar(CharacterCardViewModel charInfo) { }
	// RVA: 0x2d1bf34 VA: 0x7595333f34
	private Boolean _FilterSkillMaxChar(CharacterCardViewModel charInfo) { }
	// RVA: 0x2d1c06c VA: 0x759533406c
	public Void .ctor() { }
}
```