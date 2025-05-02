# UniEquipArchiveEntryCollectionNewEditionItemViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `String <uniEquipId>k__BackingField`

- `String <typeIcon>k__BackingField`

- `String <uniEquipName>k__BackingField`

- `UniEquipType <type>k__BackingField`

- `String <equipShiningColor>k__BackingField`

- `String <typeName1>k__BackingField`

- `String <typeName2>k__BackingField`

- `CharQuery <charQuery>k__BackingField`

- `Int32 <charInstId>k__BackingField`

- `String <charName>k__BackingField`

- `Color <charColor>k__BackingField`

- `ProfessionCategory <profession>k__BackingField`

- `String <subProfessionId>k__BackingField`

- `EntryCollectionEquipItemShowState <entryCollectionEquipItemShowState>k__BackingField`

- `EntryCollectionEquipItemUnlockState <entryCollectionEquipItemUnlockState>k__BackingField`

- `EntryCollectionEquipItemClickType <itemClickType>k__BackingField`

- `EntryCollectionEquipItemCharPartClickType <itemCharPartClickType>k__BackingField`

- `Boolean <isTmpl>k__BackingField`

- `Boolean <isCurrentTmpl>k__BackingField`

- `Int64 m_startGetTime`

- `RarityRank m_charRank`

- `String m_tmplId`

- `String m_currentTmplId`


## Properties

- `String uniEquipId`

- `String typeIcon`

- `String uniEquipName`

- `UniEquipType type`

- `String equipShiningColor`

- `String typeName1`

- `String typeName2`

- `CharQuery charQuery`

- `Int32 charInstId`

- `String charName`

- `Color charColor`

- `ProfessionCategory profession`

- `String subProfessionId`

- `EntryCollectionEquipItemShowState entryCollectionEquipItemShowState`

- `EntryCollectionEquipItemUnlockState entryCollectionEquipItemUnlockState`

- `EntryCollectionEquipItemClickType itemClickType`

- `EntryCollectionEquipItemCharPartClickType itemCharPartClickType`

- `Boolean isTmpl`

- `Boolean isCurrentTmpl`


## Methods

- `String get_uniEquipId()`

- `Void set_uniEquipId(String)`

- `String get_typeIcon()`

- `Void set_typeIcon(String)`

- `String get_uniEquipName()`

- `Void set_uniEquipName(String)`

- `UniEquipType get_type()`

- `Void set_type(UniEquipType)`

- `String get_equipShiningColor()`

- `Void set_equipShiningColor(String)`

- `String get_typeName1()`

- `Void set_typeName1(String)`

- `String get_typeName2()`

- `Void set_typeName2(String)`

- `CharQuery get_charQuery()`

- `Void set_charQuery(CharQuery)`

- `Int32 get_charInstId()`

- `Void set_charInstId(Int32)`

- `String get_charName()`

- `Void set_charName(String)`

- `Color get_charColor()`

- `Void set_charColor(Color)`

- `ProfessionCategory get_profession()`

- `Void set_profession(ProfessionCategory)`

- `String get_subProfessionId()`

- `Void set_subProfessionId(String)`

- `EntryCollectionEquipItemShowState get_entryCollectionEquipItemShowState()`

- `Void set_entryCollectionEquipItemShowState(EntryCollectionEquipItemShowState)`

- `EntryCollectionEquipItemUnlockState get_entryCollectionEquipItemUnlockState()`

- `Void set_entryCollectionEquipItemUnlockState(EntryCollectionEquipItemUnlockState)`

- `EntryCollectionEquipItemClickType get_itemClickType()`

- `Void set_itemClickType(EntryCollectionEquipItemClickType)`

- `EntryCollectionEquipItemCharPartClickType get_itemCharPartClickType()`

- `Void set_itemCharPartClickType(EntryCollectionEquipItemCharPartClickType)`

- `Boolean get_isTmpl()`

- `Void set_isTmpl(Boolean)`

- `Boolean get_isCurrentTmpl()`

- `Void set_isCurrentTmpl(Boolean)`

- `Void LoadData(UniEquipData)`

- `Void RefreshInfoData(UniEquipArchiveCollectionEquipInfoData)`

- `Int32 CompareTo(UniEquipArchiveEntryCollectionNewEditionItemViewModel)`

- `Void _LoadBasicData(UniEquipData)`

- `Void _RefreshClickType(EntryCollectionEquipItemShowState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEntryCollectionNewEditionItemViewModel : IHotfixable, IComparable`1
{
	private String <uniEquipId>k__BackingField; // 0x10
	private String <typeIcon>k__BackingField; // 0x18
	private String <uniEquipName>k__BackingField; // 0x20
	private UniEquipType <type>k__BackingField; // 0x28
	private String <equipShiningColor>k__BackingField; // 0x30
	private String <typeName1>k__BackingField; // 0x38
	private String <typeName2>k__BackingField; // 0x40
	private CharQuery <charQuery>k__BackingField; // 0x48
	private Int32 <charInstId>k__BackingField; // 0x60
	private String <charName>k__BackingField; // 0x68
	private Color <charColor>k__BackingField; // 0x70
	private ProfessionCategory <profession>k__BackingField; // 0x80
	private String <subProfessionId>k__BackingField; // 0x88
	private EntryCollectionEquipItemShowState <entryCollectionEquipItemShowState>k__BackingField; // 0x90
	private EntryCollectionEquipItemUnlockState <entryCollectionEquipItemUnlockState>k__BackingField; // 0x94
	private EntryCollectionEquipItemClickType <itemClickType>k__BackingField; // 0x98
	private EntryCollectionEquipItemCharPartClickType <itemCharPartClickType>k__BackingField; // 0x9c
	private Boolean <isTmpl>k__BackingField; // 0xa0
	private Boolean <isCurrentTmpl>k__BackingField; // 0xa1
	private Int64 m_startGetTime; // 0xa8
	private RarityRank m_charRank; // 0xb0
	private String m_tmplId; // 0xb8
	private String m_currentTmplId; // 0xc0
	private static DelegateBridge __Hotfix0_get_uniEquipId; // 0x0
	private static DelegateBridge __Hotfix0_set_uniEquipId; // 0x8
	private static DelegateBridge __Hotfix0_get_typeIcon; // 0x10
	private static DelegateBridge __Hotfix0_set_typeIcon; // 0x18
	private static DelegateBridge __Hotfix0_get_uniEquipName; // 0x20
	private static DelegateBridge __Hotfix0_set_uniEquipName; // 0x28
	private static DelegateBridge __Hotfix0_get_type; // 0x30
	private static DelegateBridge __Hotfix0_set_type; // 0x38
	private static DelegateBridge __Hotfix0_get_equipShiningColor; // 0x40
	private static DelegateBridge __Hotfix0_set_equipShiningColor; // 0x48
	private static DelegateBridge __Hotfix0_get_typeName1; // 0x50
	private static DelegateBridge __Hotfix0_set_typeName1; // 0x58
	private static DelegateBridge __Hotfix0_get_typeName2; // 0x60
	private static DelegateBridge __Hotfix0_set_typeName2; // 0x68
	private static DelegateBridge __Hotfix0_get_charQuery; // 0x70
	private static DelegateBridge __Hotfix0_set_charQuery; // 0x78
	private static DelegateBridge __Hotfix0_get_charInstId; // 0x80
	private static DelegateBridge __Hotfix0_set_charInstId; // 0x88
	private static DelegateBridge __Hotfix0_get_charName; // 0x90
	private static DelegateBridge __Hotfix0_set_charName; // 0x98
	private static DelegateBridge __Hotfix0_get_charColor; // 0xa0
	private static DelegateBridge __Hotfix0_set_charColor; // 0xa8
	private static DelegateBridge __Hotfix0_get_profession; // 0xb0
	private static DelegateBridge __Hotfix0_set_profession; // 0xb8
	private static DelegateBridge __Hotfix0_get_subProfessionId; // 0xc0
	private static DelegateBridge __Hotfix0_set_subProfessionId; // 0xc8
	private static DelegateBridge __Hotfix0_get_entryCollectionEquipItemShowState; // 0xd0
	private static DelegateBridge __Hotfix0_set_entryCollectionEquipItemShowState; // 0xd8
	private static DelegateBridge __Hotfix0_get_entryCollectionEquipItemUnlockState; // 0xe0
	private static DelegateBridge __Hotfix0_set_entryCollectionEquipItemUnlockState; // 0xe8
	private static DelegateBridge __Hotfix0_get_itemClickType; // 0xf0
	private static DelegateBridge __Hotfix0_set_itemClickType; // 0xf8
	private static DelegateBridge __Hotfix0_get_itemCharPartClickType; // 0x100
	private static DelegateBridge __Hotfix0_set_itemCharPartClickType; // 0x108
	private static DelegateBridge __Hotfix0_get_isTmpl; // 0x110
	private static DelegateBridge __Hotfix0_set_isTmpl; // 0x118
	private static DelegateBridge __Hotfix0_get_isCurrentTmpl; // 0x120
	private static DelegateBridge __Hotfix0_set_isCurrentTmpl; // 0x128
	private static DelegateBridge __Hotfix0_LoadData; // 0x130
	private static DelegateBridge __Hotfix0_RefreshInfoData; // 0x138
	private static DelegateBridge __Hotfix0_CompareTo; // 0x140
	private static DelegateBridge __Hotfix0__LoadBasicData; // 0x148
	private static DelegateBridge __Hotfix0__RefreshClickType; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	public String uniEquipId { get; set; }
	public String typeIcon { get; set; }
	public String uniEquipName { get; set; }
	public UniEquipType type { get; set; }
	public String equipShiningColor { get; set; }
	public String typeName1 { get; set; }
	public String typeName2 { get; set; }
	public CharQuery charQuery { get; set; }
	public Int32 charInstId { get; set; }
	public String charName { get; set; }
	public Color charColor { get; set; }
	public ProfessionCategory profession { get; set; }
	public String subProfessionId { get; set; }
	public EntryCollectionEquipItemShowState entryCollectionEquipItemShowState { get; set; }
	public EntryCollectionEquipItemUnlockState entryCollectionEquipItemUnlockState { get; set; }
	public EntryCollectionEquipItemClickType itemClickType { get; set; }
	public EntryCollectionEquipItemCharPartClickType itemCharPartClickType { get; set; }
	public Boolean isTmpl { get; set; }
	public Boolean isCurrentTmpl { get; set; }

	// RVA: 0x22ee5a8 VA: 0x75949065a8
	public String get_uniEquipId() { }
	// RVA: 0x22f5984 VA: 0x759490d984
	private Void set_uniEquipId(String value) { }
	// RVA: 0x22ee610 VA: 0x7594906610
	public String get_typeIcon() { }
	// RVA: 0x22f5a08 VA: 0x759490da08
	private Void set_typeIcon(String value) { }
	// RVA: 0x22ee678 VA: 0x7594906678
	public String get_uniEquipName() { }
	// RVA: 0x22f5a8c VA: 0x759490da8c
	private Void set_uniEquipName(String value) { }
	// RVA: 0x22ee910 VA: 0x7594906910
	public UniEquipType get_type() { }
	// RVA: 0x22f5b10 VA: 0x759490db10
	private Void set_type(UniEquipType value) { }
	// RVA: 0x22ee978 VA: 0x7594906978
	public String get_equipShiningColor() { }
	// RVA: 0x22f5b8c VA: 0x759490db8c
	private Void set_equipShiningColor(String value) { }
	// RVA: 0x22eea48 VA: 0x7594906a48
	public String get_typeName1() { }
	// RVA: 0x22f5c10 VA: 0x759490dc10
	private Void set_typeName1(String value) { }
	// RVA: 0x22ee9e0 VA: 0x75949069e0
	public String get_typeName2() { }
	// RVA: 0x22f5c94 VA: 0x759490dc94
	private Void set_typeName2(String value) { }
	// RVA: 0x22ee6e0 VA: 0x75949066e0
	public CharQuery get_charQuery() { }
	// RVA: 0x22f5d18 VA: 0x759490dd18
	private Void set_charQuery(CharQuery value) { }
	// RVA: 0x22f5dc8 VA: 0x759490ddc8
	public Int32 get_charInstId() { }
	// RVA: 0x22f5e30 VA: 0x759490de30
	private Void set_charInstId(Int32 value) { }
	// RVA: 0x22ee770 VA: 0x7594906770
	public String get_charName() { }
	// RVA: 0x22f5eac VA: 0x759490deac
	private Void set_charName(String value) { }
	// RVA: 0x22ee7d8 VA: 0x75949067d8
	public Color get_charColor() { }
	// RVA: 0x22f5f30 VA: 0x759490df30
	private Void set_charColor(Color value) { }
	// RVA: 0x22ee840 VA: 0x7594906840
	public ProfessionCategory get_profession() { }
	// RVA: 0x22f5fd4 VA: 0x759490dfd4
	private Void set_profession(ProfessionCategory value) { }
	// RVA: 0x22ee8a8 VA: 0x75949068a8
	public String get_subProfessionId() { }
	// RVA: 0x22f6050 VA: 0x759490e050
	private Void set_subProfessionId(String value) { }
	// RVA: 0x22eeab0 VA: 0x7594906ab0
	public EntryCollectionEquipItemShowState get_entryCollectionEquipItemShowState() { }
	// RVA: 0x22f60d4 VA: 0x759490e0d4
	private Void set_entryCollectionEquipItemShowState(EntryCollectionEquipItemShowState value) { }
	// RVA: 0x22f6150 VA: 0x759490e150
	public EntryCollectionEquipItemUnlockState get_entryCollectionEquipItemUnlockState() { }
	// RVA: 0x22f61b8 VA: 0x759490e1b8
	private Void set_entryCollectionEquipItemUnlockState(EntryCollectionEquipItemUnlockState value) { }
	// RVA: 0x22f6234 VA: 0x759490e234
	public EntryCollectionEquipItemClickType get_itemClickType() { }
	// RVA: 0x22f629c VA: 0x759490e29c
	private Void set_itemClickType(EntryCollectionEquipItemClickType value) { }
	// RVA: 0x22eeb18 VA: 0x7594906b18
	public EntryCollectionEquipItemCharPartClickType get_itemCharPartClickType() { }
	// RVA: 0x22f6318 VA: 0x759490e318
	private Void set_itemCharPartClickType(EntryCollectionEquipItemCharPartClickType value) { }
	// RVA: 0x22f6394 VA: 0x759490e394
	public Boolean get_isTmpl() { }
	// RVA: 0x22f63fc VA: 0x759490e3fc
	private Void set_isTmpl(Boolean value) { }
	// RVA: 0x22f647c VA: 0x759490e47c
	public Boolean get_isCurrentTmpl() { }
	// RVA: 0x22f64e4 VA: 0x759490e4e4
	private Void set_isCurrentTmpl(Boolean value) { }
	// RVA: 0x22f4f04 VA: 0x759490cf04
	public Void LoadData(UniEquipData equipData) { }
	// RVA: 0x22f4fec VA: 0x759490cfec
	public Void RefreshInfoData(UniEquipArchiveCollectionEquipInfoData itemInfoData) { }
	// RVA: 0x22f6874 VA: 0x759490e874
	public Int32 CompareTo(UniEquipArchiveEntryCollectionNewEditionItemViewModel other) { }
	// RVA: 0x22f6564 VA: 0x759490e564
	private Void _LoadBasicData(UniEquipData equipData) { }
	// RVA: 0x22f6798 VA: 0x759490e798
	private Void _RefreshClickType(EntryCollectionEquipItemShowState itemShowState) { }
	// RVA: 0x22f4e94 VA: 0x759490ce94
	public Void .ctor() { }
}
```