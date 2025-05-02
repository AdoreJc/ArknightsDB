# CardModel

**Namespace:** ` `


## Fields

- `Card <card>k__BackingField`

- `LegionCardLibraryType <cardFromType>k__BackingField`

- `SelectInfoData <selectInfo>k__BackingField`

- `Int32 <inHandCardCount>k__BackingField`

- `Int32 <maxCardCount>k__BackingField`

- `Boolean <isChar>k__BackingField`

- `UInt32 <cardId>k__BackingField`

- `String <cardName>k__BackingField`


## Properties

- `Card card`

- `LegionCardLibraryType cardFromType`

- `SelectInfoData selectInfo`

- `Int32 inHandCardCount`

- `Int32 maxCardCount`

- `Boolean isChar`

- `UInt32 cardId`

- `String cardName`


## Methods

- `Card get_card()`

- `Void set_card(Card)`

- `LegionCardLibraryType get_cardFromType()`

- `Void set_cardFromType(LegionCardLibraryType)`

- `SelectInfoData get_selectInfo()`

- `Void set_selectInfo(SelectInfoData)`

- `Int32 get_inHandCardCount()`

- `Void set_inHandCardCount(Int32)`

- `Int32 get_maxCardCount()`

- `Void set_maxCardCount(Int32)`

- `Boolean get_isChar()`

- `Void set_isChar(Boolean)`

- `UInt32 get_cardId()`

- `Void set_cardId(UInt32)`

- `String get_cardName()`

- `Void set_cardName(String)`

- `Void InitData(Card, SelectInfoData, LegionCardLibraryType, Int32, Int32)`

- `Boolean IsCurSelectBeyondLimit(Int32)`

- `Void UpdateSelectState(Boolean, Int32)`

- `Void UpdateSelectIndex(Int32)`

- `Void UpdateSelectingCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CardModel : IHotfixable
{
	private Card <card>k__BackingField; // 0x10
	private LegionCardLibraryType <cardFromType>k__BackingField; // 0x18
	private SelectInfoData <selectInfo>k__BackingField; // 0x20
	private Int32 <inHandCardCount>k__BackingField; // 0x28
	private Int32 <maxCardCount>k__BackingField; // 0x2c
	private Boolean <isChar>k__BackingField; // 0x30
	private UInt32 <cardId>k__BackingField; // 0x34
	private String <cardName>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_card; // 0x0
	private static DelegateBridge __Hotfix0_set_card; // 0x8
	private static DelegateBridge __Hotfix0_get_cardFromType; // 0x10
	private static DelegateBridge __Hotfix0_set_cardFromType; // 0x18
	private static DelegateBridge __Hotfix0_get_selectInfo; // 0x20
	private static DelegateBridge __Hotfix0_set_selectInfo; // 0x28
	private static DelegateBridge __Hotfix0_get_inHandCardCount; // 0x30
	private static DelegateBridge __Hotfix0_set_inHandCardCount; // 0x38
	private static DelegateBridge __Hotfix0_get_maxCardCount; // 0x40
	private static DelegateBridge __Hotfix0_set_maxCardCount; // 0x48
	private static DelegateBridge __Hotfix0_get_isChar; // 0x50
	private static DelegateBridge __Hotfix0_set_isChar; // 0x58
	private static DelegateBridge __Hotfix0_get_cardId; // 0x60
	private static DelegateBridge __Hotfix0_set_cardId; // 0x68
	private static DelegateBridge __Hotfix0_get_cardName; // 0x70
	private static DelegateBridge __Hotfix0_set_cardName; // 0x78
	private static DelegateBridge __Hotfix0_InitData; // 0x80
	private static DelegateBridge __Hotfix0_IsCurSelectBeyondLimit; // 0x88
	private static DelegateBridge __Hotfix0_UpdateSelectState; // 0x90
	private static DelegateBridge __Hotfix0_UpdateSelectIndex; // 0x98
	private static DelegateBridge __Hotfix0_UpdateSelectingCount; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Card card { get; set; }
	public LegionCardLibraryType cardFromType { get; set; }
	public SelectInfoData selectInfo { get; set; }
	public Int32 inHandCardCount { get; set; }
	public Int32 maxCardCount { get; set; }
	public Boolean isChar { get; set; }
	public UInt32 cardId { get; set; }
	public String cardName { get; set; }

	// RVA: 0x1dc0c78 VA: 0x75943d8c78
	public Card get_card() { }
	// RVA: 0x1dc1670 VA: 0x75943d9670
	private Void set_card(Card value) { }
	// RVA: 0x1dc16f4 VA: 0x75943d96f4
	public LegionCardLibraryType get_cardFromType() { }
	// RVA: 0x1dc175c VA: 0x75943d975c
	private Void set_cardFromType(LegionCardLibraryType value) { }
	// RVA: 0x1dc0ce0 VA: 0x75943d8ce0
	public SelectInfoData get_selectInfo() { }
	// RVA: 0x1dc17d8 VA: 0x75943d97d8
	private Void set_selectInfo(SelectInfoData value) { }
	// RVA: 0x1dc185c VA: 0x75943d985c
	public Int32 get_inHandCardCount() { }
	// RVA: 0x1dc18c4 VA: 0x75943d98c4
	private Void set_inHandCardCount(Int32 value) { }
	// RVA: 0x1dc1940 VA: 0x75943d9940
	public Int32 get_maxCardCount() { }
	// RVA: 0x1dc19a8 VA: 0x75943d99a8
	private Void set_maxCardCount(Int32 value) { }
	// RVA: 0x1dc0db0 VA: 0x75943d8db0
	public Boolean get_isChar() { }
	// RVA: 0x1dc1a24 VA: 0x75943d9a24
	private Void set_isChar(Boolean value) { }
	// RVA: 0x1dc0d48 VA: 0x75943d8d48
	public UInt32 get_cardId() { }
	// RVA: 0x1dc1aa4 VA: 0x75943d9aa4
	private Void set_cardId(UInt32 value) { }
	// RVA: 0x1dc0e18 VA: 0x75943d8e18
	public String get_cardName() { }
	// RVA: 0x1dc1b20 VA: 0x75943d9b20
	private Void set_cardName(String value) { }
	// RVA: 0x1dc1ba4 VA: 0x75943d9ba4
	public Void InitData(Card cardInput, SelectInfoData selectInfoData, LegionCardLibraryType from, Int32 inHandCardNum, Int32 maxCardNum) { }
	// RVA: 0x1dc1248 VA: 0x75943d9248
	public Boolean IsCurSelectBeyondLimit(Int32 selectIndex) { }
	// RVA: 0x1dc1d20 VA: 0x75943d9d20
	public Void UpdateSelectState(Boolean select, Int32 index) { }
	// RVA: 0x1dc1dd4 VA: 0x75943d9dd4
	public Void UpdateSelectIndex(Int32 index) { }
	// RVA: 0x1dc1e6c VA: 0x75943d9e6c
	public Void UpdateSelectingCount(Int32 selectingCount) { }
	// RVA: 0x1dc1f04 VA: 0x75943d9f04
	public Void .ctor() { }
}
```