# CarvingMainCardViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String <actId>k__BackingField`

- `String <cardId>k__BackingField`

- `Int32 <cardLevel>k__BackingField`

- `String <cardPic>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `Boolean <isShopCard>k__BackingField`

- `Boolean <canUpgrade>k__BackingField`

- `Int32 <handCardLevel>k__BackingField`

- `CarvingCardBornType <bornType>k__BackingField`


## Properties

- `String actId`

- `String cardId`

- `Int32 cardLevel`

- `String cardPic`

- `Int32 sortId`

- `Boolean isShopCard`

- `Boolean canUpgrade`

- `Int32 handCardLevel`

- `CarvingCardBornType bornType`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_cardId()`

- `Void set_cardId(String)`

- `Int32 get_cardLevel()`

- `Void set_cardLevel(Int32)`

- `String get_cardPic()`

- `Void set_cardPic(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Boolean get_isShopCard()`

- `Void set_isShopCard(Boolean)`

- `Boolean get_canUpgrade()`

- `Void set_canUpgrade(Boolean)`

- `Int32 get_handCardLevel()`

- `Void set_handCardLevel(Int32)`

- `CarvingCardBornType get_bornType()`

- `Void set_bornType(CarvingCardBornType)`

- `Void LoadData(LoadParam)`

- `Void SetBornType(CarvingCardBornType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainCardViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private String <cardId>k__BackingField; // 0x18
	private Int32 <cardLevel>k__BackingField; // 0x20
	private String <cardPic>k__BackingField; // 0x28
	private Int32 <sortId>k__BackingField; // 0x30
	private Boolean <isShopCard>k__BackingField; // 0x34
	private Boolean <canUpgrade>k__BackingField; // 0x35
	private Int32 <handCardLevel>k__BackingField; // 0x38
	private CarvingCardBornType <bornType>k__BackingField; // 0x3c
	public List`1 inputMaterials; // 0x40
	public List`1 outputMaterials; // 0x48
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_cardId; // 0x10
	private static DelegateBridge __Hotfix0_set_cardId; // 0x18
	private static DelegateBridge __Hotfix0_get_cardLevel; // 0x20
	private static DelegateBridge __Hotfix0_set_cardLevel; // 0x28
	private static DelegateBridge __Hotfix0_get_cardPic; // 0x30
	private static DelegateBridge __Hotfix0_set_cardPic; // 0x38
	private static DelegateBridge __Hotfix0_get_sortId; // 0x40
	private static DelegateBridge __Hotfix0_set_sortId; // 0x48
	private static DelegateBridge __Hotfix0_get_isShopCard; // 0x50
	private static DelegateBridge __Hotfix0_set_isShopCard; // 0x58
	private static DelegateBridge __Hotfix0_get_canUpgrade; // 0x60
	private static DelegateBridge __Hotfix0_set_canUpgrade; // 0x68
	private static DelegateBridge __Hotfix0_get_handCardLevel; // 0x70
	private static DelegateBridge __Hotfix0_set_handCardLevel; // 0x78
	private static DelegateBridge __Hotfix0_get_bornType; // 0x80
	private static DelegateBridge __Hotfix0_set_bornType; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x90
	private static DelegateBridge __Hotfix0_SetBornType; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public String actId { get; set; }
	public String cardId { get; set; }
	public Int32 cardLevel { get; set; }
	public String cardPic { get; set; }
	public Int32 sortId { get; set; }
	public Boolean isShopCard { get; set; }
	public Boolean canUpgrade { get; set; }
	public Int32 handCardLevel { get; set; }
	public CarvingCardBornType bornType { get; set; }

	// RVA: 0x2daa54c VA: 0x75953c254c
	public String get_actId() { }
	// RVA: 0x2daab7c VA: 0x75953c2b7c
	private Void set_actId(String value) { }
	// RVA: 0x2da7f78 VA: 0x75953bff78
	public String get_cardId() { }
	// RVA: 0x2daac00 VA: 0x75953c2c00
	private Void set_cardId(String value) { }
	// RVA: 0x2da7748 VA: 0x75953bf748
	public Int32 get_cardLevel() { }
	// RVA: 0x2daac84 VA: 0x75953c2c84
	private Void set_cardLevel(Int32 value) { }
	// RVA: 0x2da7818 VA: 0x75953bf818
	public String get_cardPic() { }
	// RVA: 0x2daad00 VA: 0x75953c2d00
	private Void set_cardPic(String value) { }
	// RVA: 0x2da8ee0 VA: 0x75953c0ee0
	public Int32 get_sortId() { }
	// RVA: 0x2daad84 VA: 0x75953c2d84
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2daa4e4 VA: 0x75953c24e4
	public Boolean get_isShopCard() { }
	// RVA: 0x2daae00 VA: 0x75953c2e00
	private Void set_isShopCard(Boolean value) { }
	// RVA: 0x2da77b0 VA: 0x75953bf7b0
	public Boolean get_canUpgrade() { }
	// RVA: 0x2daae80 VA: 0x75953c2e80
	private Void set_canUpgrade(Boolean value) { }
	// RVA: 0x2daa47c VA: 0x75953c247c
	public Int32 get_handCardLevel() { }
	// RVA: 0x2daaf00 VA: 0x75953c2f00
	private Void set_handCardLevel(Int32 value) { }
	// RVA: 0x2daaf7c VA: 0x75953c2f7c
	public CarvingCardBornType get_bornType() { }
	// RVA: 0x2daafe4 VA: 0x75953c2fe4
	private Void set_bornType(CarvingCardBornType value) { }
	// RVA: 0x2da8574 VA: 0x75953c0574
	public Void LoadData(LoadParam loadParam) { }
	// RVA: 0x2da878c VA: 0x75953c078c
	public Void SetBornType(CarvingCardBornType type) { }
	// RVA: 0x2da8504 VA: 0x75953c0504
	public Void .ctor() { }
}
```