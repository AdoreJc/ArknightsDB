# CarvingMainCardDetailViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String <cardId>k__BackingField`

- `String <cardFace>k__BackingField`

- `String <cardName>k__BackingField`

- `String <cardDesc>k__BackingField`

- `Int32 <cardShowLevel>k__BackingField`

- `Int32 <handCardLevel>k__BackingField`

- `Boolean <canUpgrade>k__BackingField`

- `Boolean <isMaxLevel>k__BackingField`

- `Boolean <isShopCard>k__BackingField`

- `Int32 <selectSeqNum>k__BackingField`

- `Int32 <cardLevel>k__BackingField`


## Properties

- `String cardId`

- `String cardFace`

- `String cardName`

- `String cardDesc`

- `Int32 cardShowLevel`

- `Int32 handCardLevel`

- `Boolean canUpgrade`

- `Boolean isMaxLevel`

- `Boolean isShopCard`

- `Int32 selectSeqNum`

- `Int32 cardLevel`


## Methods

- `String get_cardId()`

- `Void set_cardId(String)`

- `String get_cardFace()`

- `Void set_cardFace(String)`

- `String get_cardName()`

- `Void set_cardName(String)`

- `String get_cardDesc()`

- `Void set_cardDesc(String)`

- `Int32 get_cardShowLevel()`

- `Void set_cardShowLevel(Int32)`

- `Int32 get_handCardLevel()`

- `Void set_handCardLevel(Int32)`

- `Boolean get_canUpgrade()`

- `Void set_canUpgrade(Boolean)`

- `Boolean get_isMaxLevel()`

- `Void set_isMaxLevel(Boolean)`

- `Boolean get_isShopCard()`

- `Void set_isShopCard(Boolean)`

- `Int32 get_selectSeqNum()`

- `Void set_selectSeqNum(Int32)`

- `Int32 get_cardLevel()`

- `Void set_cardLevel(Int32)`

- `Void LoadData(CarvingMainCardViewModel)`

- `Void NotifySelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainCardDetailViewModel : IHotfixable
{
	private String <cardId>k__BackingField; // 0x10
	private String <cardFace>k__BackingField; // 0x18
	private String <cardName>k__BackingField; // 0x20
	private String <cardDesc>k__BackingField; // 0x28
	private Int32 <cardShowLevel>k__BackingField; // 0x30
	private Int32 <handCardLevel>k__BackingField; // 0x34
	private Boolean <canUpgrade>k__BackingField; // 0x38
	private Boolean <isMaxLevel>k__BackingField; // 0x39
	private Boolean <isShopCard>k__BackingField; // 0x3a
	private Int32 <selectSeqNum>k__BackingField; // 0x3c
	private Int32 <cardLevel>k__BackingField; // 0x40
	public List`1 inputMaterials; // 0x48
	public List`1 outputMaterials; // 0x50
	private static DelegateBridge __Hotfix0_get_cardId; // 0x0
	private static DelegateBridge __Hotfix0_set_cardId; // 0x8
	private static DelegateBridge __Hotfix0_get_cardFace; // 0x10
	private static DelegateBridge __Hotfix0_set_cardFace; // 0x18
	private static DelegateBridge __Hotfix0_get_cardName; // 0x20
	private static DelegateBridge __Hotfix0_set_cardName; // 0x28
	private static DelegateBridge __Hotfix0_get_cardDesc; // 0x30
	private static DelegateBridge __Hotfix0_set_cardDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_cardShowLevel; // 0x40
	private static DelegateBridge __Hotfix0_set_cardShowLevel; // 0x48
	private static DelegateBridge __Hotfix0_get_handCardLevel; // 0x50
	private static DelegateBridge __Hotfix0_set_handCardLevel; // 0x58
	private static DelegateBridge __Hotfix0_get_canUpgrade; // 0x60
	private static DelegateBridge __Hotfix0_set_canUpgrade; // 0x68
	private static DelegateBridge __Hotfix0_get_isMaxLevel; // 0x70
	private static DelegateBridge __Hotfix0_set_isMaxLevel; // 0x78
	private static DelegateBridge __Hotfix0_get_isShopCard; // 0x80
	private static DelegateBridge __Hotfix0_set_isShopCard; // 0x88
	private static DelegateBridge __Hotfix0_get_selectSeqNum; // 0x90
	private static DelegateBridge __Hotfix0_set_selectSeqNum; // 0x98
	private static DelegateBridge __Hotfix0_get_cardLevel; // 0xa0
	private static DelegateBridge __Hotfix0_set_cardLevel; // 0xa8
	private static DelegateBridge __Hotfix0_LoadData; // 0xb0
	private static DelegateBridge __Hotfix0_NotifySelect; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public String cardId { get; set; }
	public String cardFace { get; set; }
	public String cardName { get; set; }
	public String cardDesc { get; set; }
	public Int32 cardShowLevel { get; set; }
	public Int32 handCardLevel { get; set; }
	public Boolean canUpgrade { get; set; }
	public Boolean isMaxLevel { get; set; }
	public Boolean isShopCard { get; set; }
	public Int32 selectSeqNum { get; set; }
	private Int32 cardLevel { get; set; }

	// RVA: 0x2da5754 VA: 0x75953bd754
	public String get_cardId() { }
	// RVA: 0x2da9af8 VA: 0x75953c1af8
	private Void set_cardId(String value) { }
	// RVA: 0x2da6098 VA: 0x75953be098
	public String get_cardFace() { }
	// RVA: 0x2da9b7c VA: 0x75953c1b7c
	private Void set_cardFace(String value) { }
	// RVA: 0x2da5e90 VA: 0x75953bde90
	public String get_cardName() { }
	// RVA: 0x2da9c00 VA: 0x75953c1c00
	private Void set_cardName(String value) { }
	// RVA: 0x2da5ef8 VA: 0x75953bdef8
	public String get_cardDesc() { }
	// RVA: 0x2da9c84 VA: 0x75953c1c84
	private Void set_cardDesc(String value) { }
	// RVA: 0x2da5fc8 VA: 0x75953bdfc8
	public Int32 get_cardShowLevel() { }
	// RVA: 0x2da9d08 VA: 0x75953c1d08
	private Void set_cardShowLevel(Int32 value) { }
	// RVA: 0x2da6030 VA: 0x75953be030
	public Int32 get_handCardLevel() { }
	// RVA: 0x2da9d84 VA: 0x75953c1d84
	private Void set_handCardLevel(Int32 value) { }
	// RVA: 0x2da5f60 VA: 0x75953bdf60
	public Boolean get_canUpgrade() { }
	// RVA: 0x2da9e00 VA: 0x75953c1e00
	private Void set_canUpgrade(Boolean value) { }
	// RVA: 0x2da5e28 VA: 0x75953bde28
	public Boolean get_isMaxLevel() { }
	// RVA: 0x2da9e80 VA: 0x75953c1e80
	private Void set_isMaxLevel(Boolean value) { }
	// RVA: 0x2da9f00 VA: 0x75953c1f00
	public Boolean get_isShopCard() { }
	// RVA: 0x2da9f68 VA: 0x75953c1f68
	private Void set_isShopCard(Boolean value) { }
	// RVA: 0x2da6100 VA: 0x75953be100
	public Int32 get_selectSeqNum() { }
	// RVA: 0x2da9fe8 VA: 0x75953c1fe8
	private Void set_selectSeqNum(Int32 value) { }
	// RVA: 0x2daa064 VA: 0x75953c2064
	private Int32 get_cardLevel() { }
	// RVA: 0x2daa0cc VA: 0x75953c20cc
	private Void set_cardLevel(Int32 value) { }
	// RVA: 0x2daa148 VA: 0x75953c2148
	public Void LoadData(CarvingMainCardViewModel cardViewModel) { }
	// RVA: 0x2daa5b4 VA: 0x75953c25b4
	public Void NotifySelect() { }
	// RVA: 0x2daa628 VA: 0x75953c2628
	public Void .ctor() { }
}
```