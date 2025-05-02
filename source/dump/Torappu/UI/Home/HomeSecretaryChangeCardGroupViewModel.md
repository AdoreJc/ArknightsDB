# HomeSecretaryChangeCardGroupViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `CharacterFilterViewModel filter`

- `Int32 m_displayChrInstId`

- `String displayCharId`

- `String displayCharSkinId`

- `String displayCharRealName`

- `String displayCharNickName`

- `Int32 maxSelectCharNum`

- `String presetInstId`

- `CharacterSortType m_sortTypeCache`

- `Boolean m_isStarMarkTopSelected`


## Properties

- `Int32 displayChrInstId`

- `Int32 defaultDisplayCharInstId`

- `CharacterSortType sortType`

- `Boolean isStarMarkTopSelected`


## Methods

- `Int32 get_displayChrInstId()`

- `Int32 get_defaultDisplayCharInstId()`

- `InputParams GenerateChangeSkinParams()`

- `CharacterSortType get_sortType()`

- `Void set_sortType(CharacterSortType)`

- `Boolean get_isStarMarkTopSelected()`

- `Void set_isStarMarkTopSelected(Boolean)`

- `Void set_dataSource(List`1)`

- `Void UpdateFilter(CharacterFilterViewModel)`

- `Void UpdateCardCache(HomeSecretaryCardViewModel)`

- `Void SelectChar(Int32)`

- `Void RemoveChar(Int32)`

- `Boolean IsCharSelected(Int32)`

- `Void UpdateDisplayCharInfo()`

- `Void _ProcessSelectedCharTopMode(ref)`

- `Void _ProcessStarMarkCharTopMode(ref)`

- `Boolean _IsCardSelected(HomeSecretaryCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretaryChangeCardGroupViewModel : IHotfixable
{
	public CharacterFilterViewModel filter; // 0x10
	public HashSet`1 starMarkSelectedChrInstIds; // 0x18
	private Int32 m_displayChrInstId; // 0x20
	public String displayCharId; // 0x28
	public String displayCharSkinId; // 0x30
	public String displayCharRealName; // 0x38
	public String displayCharNickName; // 0x40
	public Int32 maxSelectCharNum; // 0x48
	public Dictionary`2 inPresetSkinDict; // 0x50
	public String presetInstId; // 0x58
	public HashSet`1 selectedCharInstIds; // 0x60
	private List`1 m_playerSelectRecords; // 0x68
	private List`1 m_cardListCache; // 0x70
	private CharacterSortType m_sortTypeCache; // 0x78
	private Boolean m_isStarMarkTopSelected; // 0x7c
	private List`1 m_secretaryCardViewModels; // 0x80
	private static DelegateBridge __Hotfix0_get_displayChrInstId; // 0x0
	private static DelegateBridge __Hotfix0_get_defaultDisplayCharInstId; // 0x8
	private static DelegateBridge __Hotfix0_GenerateChangeSkinParams; // 0x10
	private static DelegateBridge __Hotfix0_get_cardListCache; // 0x18
	private static DelegateBridge __Hotfix0_get_cardList; // 0x20
	private static DelegateBridge __Hotfix0_get_sortType; // 0x28
	private static DelegateBridge __Hotfix0_set_sortType; // 0x30
	private static DelegateBridge __Hotfix0_get_isStarMarkTopSelected; // 0x38
	private static DelegateBridge __Hotfix0_set_isStarMarkTopSelected; // 0x40
	private static DelegateBridge __Hotfix0_get_dataSource; // 0x48
	private static DelegateBridge __Hotfix0_set_dataSource; // 0x50
	private static DelegateBridge __Hotfix0_UpdateFilter; // 0x58
	private static DelegateBridge __Hotfix0_UpdateCardCache; // 0x60
	private static DelegateBridge __Hotfix0_SelectChar; // 0x68
	private static DelegateBridge __Hotfix0_RemoveChar; // 0x70
	private static DelegateBridge __Hotfix0_IsCharSelected; // 0x78
	private static DelegateBridge __Hotfix0_UpdateDisplayCharInfo; // 0x80
	private static DelegateBridge __Hotfix0__GetCharCardList; // 0x88
	private static DelegateBridge __Hotfix0__ProcessSelectedCharTopMode; // 0x90
	private static DelegateBridge __Hotfix0__ProcessStarMarkCharTopMode; // 0x98
	private static DelegateBridge __Hotfix0__IsCardSelected; // 0xa0
	private static DelegateBridge __Hotfix0__AchieveSortedAndFilterCharacters; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public Int32 displayChrInstId { get; }
	public Int32 defaultDisplayCharInstId { get; }
	public List`1 cardListCache { get; }
	public List`1 cardList { get; }
	public CharacterSortType sortType { get; set; }
	public Boolean isStarMarkTopSelected { get; set; }
	public List`1 dataSource { get; set; }

	// RVA: 0x2812ac8 VA: 0x7594e2aac8
	public Int32 get_displayChrInstId() { }
	// RVA: 0x2812d1c VA: 0x7594e2ad1c
	public Int32 get_defaultDisplayCharInstId() { }
	// RVA: 0x2800d44 VA: 0x7594e18d44
	public InputParams GenerateChangeSkinParams() { }
	// RVA: 0x2812f44 VA: 0x7594e2af44
	public List`1 get_cardListCache() { }
	// RVA: 0x2812e28 VA: 0x7594e2ae28
	public List`1 get_cardList() { }
	// RVA: 0x281309c VA: 0x7594e2b09c
	public CharacterSortType get_sortType() { }
	// RVA: 0x2813104 VA: 0x7594e2b104
	public Void set_sortType(CharacterSortType value) { }
	// RVA: 0x28131a8 VA: 0x7594e2b1a8
	public Boolean get_isStarMarkTopSelected() { }
	// RVA: 0x2813210 VA: 0x7594e2b210
	public Void set_isStarMarkTopSelected(Boolean value) { }
	// RVA: 0x28132bc VA: 0x7594e2b2bc
	public List`1 get_dataSource() { }
	// RVA: 0x2813324 VA: 0x7594e2b324
	public Void set_dataSource(List`1 value) { }
	// RVA: 0x28133b8 VA: 0x7594e2b3b8
	public Void UpdateFilter(CharacterFilterViewModel filterViewModel) { }
	// RVA: 0x2813454 VA: 0x7594e2b454
	public Void UpdateCardCache(HomeSecretaryCardViewModel model) { }
	// RVA: 0x2813604 VA: 0x7594e2b604
	public Void SelectChar(Int32 charInstId) { }
	// RVA: 0x2813780 VA: 0x7594e2b780
	public Void RemoveChar(Int32 charInstId) { }
	// RVA: 0x2813850 VA: 0x7594e2b850
	public Boolean IsCharSelected(Int32 charInstId) { }
	// RVA: 0x2812b44 VA: 0x7594e2ab44
	public Void UpdateDisplayCharInfo() { }
	// RVA: 0x2812fac VA: 0x7594e2afac
	private List`1 _GetCharCardList() { }
	// RVA: 0x2813db8 VA: 0x7594e2bdb8
	private Void _ProcessSelectedCharTopMode(ref List`1 dataList) { }
	// RVA: 0x2813b3c VA: 0x7594e2bb3c
	private Void _ProcessStarMarkCharTopMode(ref List`1 dataList) { }
	// RVA: 0x2812eb4 VA: 0x7594e2aeb4
	private Boolean _IsCardSelected(HomeSecretaryCardViewModel cardModel) { }
	// RVA: 0x28138f0 VA: 0x7594e2b8f0
	private List`1 _AchieveSortedAndFilterCharacters(Func`2 filterWhiteList) { }
	// RVA: 0x2814008 VA: 0x7594e2c008
	public Void .ctor() { }
}
```