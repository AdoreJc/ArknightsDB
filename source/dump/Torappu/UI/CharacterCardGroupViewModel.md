# CharacterCardGroupViewModel

**Namespace:** `Torappu.UI`


## Fields

- `CharacterFilterViewModel filter`

- `Boolean m_filterPanelShow`

- `CharacterSortType m_sortTypeCache`

- `Boolean m_isStarMarkTopSelected`

- `Boolean m_isEnableStarMarkEdit`

- `Boolean m_isTrackPointFilterSelected`


## Properties

- `CharacterSortType sortType`

- `Boolean isStarMarkTopSelected`

- `Boolean isEnableStarMarkEdit`

- `Boolean isTrackPointFilterSelected`

- `Boolean isFilterPanelShow`


## Methods

- `Void set_overrideCharListSort(Action`3)`

- `Void set_dataSource(List`1)`

- `CharacterSortType get_sortType()`

- `Void set_sortType(CharacterSortType)`

- `Boolean get_isStarMarkTopSelected()`

- `Void set_isStarMarkTopSelected(Boolean)`

- `Boolean get_isEnableStarMarkEdit()`

- `Void set_isEnableStarMarkEdit(Boolean)`

- `Boolean get_isTrackPointFilterSelected()`

- `Void set_isTrackPointFilterSelected(Boolean)`

- `Boolean get_isFilterPanelShow()`

- `Void set_isFilterPanelShow(Boolean)`

- `Void NotifyFilterChanged(CharacterFilterViewModel)`

- `Boolean _IsCardSelectedOrStarMarked(CharacterCardViewModel)`

- `Int32 _FindCardSelectIndex(CharacterCardViewModel)`

- `Boolean _GetCardStarMarkSelected(CharacterCardViewModel)`

- `Boolean StarMarkEditModeAddChar(Int32)`

- `Boolean StarMarkEditModeRemoveChar(Int32)`

- `Void StarMarkEditModeClearChar()`

- `Void set_starMarkedSelectedChrInsts(HashSet`1)`

- `Void _EnsureStarMarkEditList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CharacterCardGroupViewModel
{
	public CharacterFilterViewModel filter; // 0x10
	public List`1 selectedChrInstIds; // 0x18
	private HashSet`1 m_starMarkSelectedChrInstIds; // 0x20
	private HashSet`1 m_starMarkEditModeChrInstIds; // 0x28
	private Boolean m_filterPanelShow; // 0x30
	private List`1 m_characterViewModels; // 0x38
	private List`1 m_cardListCache; // 0x40
	private CharacterSortType m_sortTypeCache; // 0x48
	private Dictionary`2 m_charId2TrackPointDataMapCache; // 0x50
	private Action`3 m_overrideCharListSort; // 0x58
	private Boolean m_isStarMarkTopSelected; // 0x60
	private Boolean m_isEnableStarMarkEdit; // 0x61
	private Boolean m_isTrackPointFilterSelected; // 0x62

	private Action`3 overrideCharListSort { get; set; }
	public List`1 dataSource { get; set; }
	public Dictionary`2 charId2TrackPointDataMap { get; }
	public CharacterSortType sortType { get; set; }
	public Boolean isStarMarkTopSelected { get; set; }
	public Boolean isEnableStarMarkEdit { get; set; }
	public Boolean isTrackPointFilterSelected { get; set; }
	public Boolean isFilterPanelShow { get; set; }
	public List`1 cardList { get; }
	public HashSet`1 starMarkedSelectedChrInsts { get; set; }

	// RVA: 0x211fea8 VA: 0x7594737ea8
	private Action`3 get_overrideCharListSort() { }
	// RVA: 0x211feb0 VA: 0x7594737eb0
	public Void set_overrideCharListSort(Action`3 value) { }
	// RVA: 0x211fed4 VA: 0x7594737ed4
	public List`1 get_dataSource() { }
	// RVA: 0x211fedc VA: 0x7594737edc
	public Void set_dataSource(List`1 value) { }
	// RVA: 0x211ff10 VA: 0x7594737f10
	public Dictionary`2 get_charId2TrackPointDataMap() { }
	// RVA: 0x21200cc VA: 0x75947380cc
	public CharacterSortType get_sortType() { }
	// RVA: 0x21200d4 VA: 0x75947380d4
	public Void set_sortType(CharacterSortType value) { }
	// RVA: 0x21200f4 VA: 0x75947380f4
	public Boolean get_isStarMarkTopSelected() { }
	// RVA: 0x21200fc VA: 0x75947380fc
	public Void set_isStarMarkTopSelected(Boolean value) { }
	// RVA: 0x2120120 VA: 0x7594738120
	public Boolean get_isEnableStarMarkEdit() { }
	// RVA: 0x2120128 VA: 0x7594738128
	public Void set_isEnableStarMarkEdit(Boolean value) { }
	// RVA: 0x212034c VA: 0x759473834c
	public Boolean get_isTrackPointFilterSelected() { }
	// RVA: 0x2120354 VA: 0x7594738354
	public Void set_isTrackPointFilterSelected(Boolean value) { }
	// RVA: 0x2120378 VA: 0x7594738378
	public Boolean get_isFilterPanelShow() { }
	// RVA: 0x2120380 VA: 0x7594738380
	public Void set_isFilterPanelShow(Boolean value) { }
	// RVA: 0x2120398 VA: 0x7594738398
	public Void NotifyFilterChanged(CharacterFilterViewModel filter) { }
	// RVA: 0x21203c4 VA: 0x75947383c4
	private List`1 _AchieveSortedAndFilteredCharacters(Func`2 filterWhiteList) { }
	// RVA: 0x211ff50 VA: 0x7594737f50
	private Dictionary`2 _AchieveCharTrackPointMap() { }
	// RVA: 0x2120880 VA: 0x7594738880
	public List`1 get_cardList() { }
	// RVA: 0x21208c4 VA: 0x75947388c4
	private List`1 _ProcessSelectedCharTopMode(Boolean isStarTopMode) { }
	// RVA: 0x2120c70 VA: 0x7594738c70
	private List`1 _ProcessStarMarkCharTopMode(List`1 cardList) { }
	// RVA: 0x2120fa4 VA: 0x7594738fa4
	private Boolean _IsCardSelectedOrStarMarked(CharacterCardViewModel cardModel) { }
	// RVA: 0x2120bb4 VA: 0x7594738bb4
	private Int32 _FindCardSelectIndex(CharacterCardViewModel cardModel) { }
	// RVA: 0x2120738 VA: 0x7594738738
	private Boolean _GetCardStarMarkSelected(CharacterCardViewModel cardModel) { }
	// RVA: 0x2120fe0 VA: 0x7594738fe0
	public Boolean StarMarkEditModeAddChar(Int32 chrInstId) { }
	// RVA: 0x2121038 VA: 0x7594739038
	public Boolean StarMarkEditModeRemoveChar(Int32 chrInstId) { }
	// RVA: 0x2121090 VA: 0x7594739090
	public Void StarMarkEditModeClearChar() { }
	// RVA: 0x21210e0 VA: 0x75947390e0
	public HashSet`1 get_starMarkedSelectedChrInsts() { }
	// RVA: 0x21210fc VA: 0x75947390fc
	public Void set_starMarkedSelectedChrInsts(HashSet`1 value) { }
	// RVA: 0x2120180 VA: 0x7594738180
	private Void _EnsureStarMarkEditList() { }
	// RVA: 0x2121104 VA: 0x7594739104
	public Void .ctor() { }
}
```