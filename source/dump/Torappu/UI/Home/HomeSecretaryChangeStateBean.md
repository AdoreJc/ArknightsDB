# HomeSecretaryChangeStateBean

**Namespace:** `Torappu.UI.Home`


## Fields

- `BoolProperty starMarkSelectedProperty`

- `CharacterCardSortTypeViewProperty sortTypeProperty`

- `HomeSecretaryChangeCardGroupViewProperty cardGroupProperty`


## Properties

- `Boolean starMarkTopState`

- `String displayChrId`

- `Int32 displayChrInstId`

- `String displaySkinId`


## Methods

- `Boolean get_starMarkTopState()`

- `String get_displayChrId()`

- `Int32 get_displayChrInstId()`

- `String get_displaySkinId()`

- `Void set_fromSelectSkinCharIds(List`1)`

- `Void LoadData(InputParams)`

- `Void ToggleStarMarkTopSelected()`

- `Void SetSortType(CharacterSortType, Boolean)`

- `Void SetCardFilter(CharacterFilterViewModel)`

- `Void UpdateSelectedInfos(Int32)`

- `Void _LoadAllCards(InputParams)`

- `Void _SetStarMarkTopState(Boolean, Boolean)`

- `Void _UpdateDisplayCharInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretaryChangeStateBean : IStateBean, IHotfixable
{
	public BoolProperty starMarkSelectedProperty; // 0x10
	public CharacterCardSortTypeViewProperty sortTypeProperty; // 0x18
	public HomeSecretaryChangeCardGroupViewProperty cardGroupProperty; // 0x20
	private List`1 <fromSelectSkinCharIds>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_starMarkTopState; // 0x0
	private static DelegateBridge __Hotfix0_get_displayChrId; // 0x8
	private static DelegateBridge __Hotfix0_get_displayChrInstId; // 0x10
	private static DelegateBridge __Hotfix0_get_displaySkinId; // 0x18
	private static DelegateBridge __Hotfix0_get_fromSelectSkinCharIds; // 0x20
	private static DelegateBridge __Hotfix0_set_fromSelectSkinCharIds; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_ToggleStarMarkTopSelected; // 0x38
	private static DelegateBridge __Hotfix0_SetSortType; // 0x40
	private static DelegateBridge __Hotfix0_SetCardFilter; // 0x48
	private static DelegateBridge __Hotfix0_UpdateSelectedInfos; // 0x50
	private static DelegateBridge __Hotfix0__LoadAllCards; // 0x58
	private static DelegateBridge __Hotfix0__SetStarMarkTopState; // 0x60
	private static DelegateBridge __Hotfix0__UpdateDisplayCharInfo; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean starMarkTopState { get; }
	public String displayChrId { get; }
	public Int32 displayChrInstId { get; }
	public String displaySkinId { get; }
	private List`1 fromSelectSkinCharIds { get; set; }

	// RVA: 0x281575c VA: 0x7594e2d75c
	public Boolean get_starMarkTopState() { }
	// RVA: 0x28157e4 VA: 0x7594e2d7e4
	public String get_displayChrId() { }
	// RVA: 0x281586c VA: 0x7594e2d86c
	public Int32 get_displayChrInstId() { }
	// RVA: 0x28158f4 VA: 0x7594e2d8f4
	public String get_displaySkinId() { }
	// RVA: 0x281597c VA: 0x7594e2d97c
	private List`1 get_fromSelectSkinCharIds() { }
	// RVA: 0x28159e4 VA: 0x7594e2d9e4
	public Void set_fromSelectSkinCharIds(List`1 value) { }
	// RVA: 0x2815a68 VA: 0x7594e2da68
	public Void LoadData(InputParams param) { }
	// RVA: 0x28168e4 VA: 0x7594e2e8e4
	public Void ToggleStarMarkTopSelected() { }
	// RVA: 0x2816590 VA: 0x7594e2e590
	public Void SetSortType(CharacterSortType sortType, Boolean notify) { }
	// RVA: 0x2816960 VA: 0x7594e2e960
	public Void SetCardFilter(CharacterFilterViewModel filter) { }
	// RVA: 0x2816a24 VA: 0x7594e2ea24
	public Void UpdateSelectedInfos(Int32 chrInstId) { }
	// RVA: 0x2815d20 VA: 0x7594e2dd20
	private Void _LoadAllCards(InputParams param) { }
	// RVA: 0x2816700 VA: 0x7594e2e700
	private Void _SetStarMarkTopState(Boolean state, Boolean notify) { }
	// RVA: 0x2816850 VA: 0x7594e2e850
	private Void _UpdateDisplayCharInfo() { }
	// RVA: 0x2816b2c VA: 0x7594e2eb2c
	public Void .ctor() { }
}
```