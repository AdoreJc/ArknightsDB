# CarvingMainShopGoodCardItemModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String <cardId>k__BackingField`

- `Int32 <price>k__BackingField`

- `Boolean <isEmpty>k__BackingField`

- `Boolean <isSelect>k__BackingField`

- `Int32 <pos>k__BackingField`

- `CarvingMainCardViewModel <cardModel>k__BackingField`


## Properties

- `String cardId`

- `Int32 price`

- `Boolean isEmpty`

- `Boolean isSelect`

- `Int32 pos`

- `CarvingMainCardViewModel cardModel`


## Methods

- `String get_cardId()`

- `Void set_cardId(String)`

- `Int32 get_price()`

- `Void set_price(Int32)`

- `Boolean get_isEmpty()`

- `Void set_isEmpty(Boolean)`

- `Boolean get_isSelect()`

- `Void set_isSelect(Boolean)`

- `Int32 get_pos()`

- `Void set_pos(Int32)`

- `CarvingMainCardViewModel get_cardModel()`

- `Void set_cardModel(CarvingMainCardViewModel)`

- `Void SetData(ShopGood, Int32, String, Boolean, Int32)`

- `Void SetSelect(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainShopGoodCardItemModel : IHotfixable
{
	private String <cardId>k__BackingField; // 0x10
	private Int32 <price>k__BackingField; // 0x18
	private Boolean <isEmpty>k__BackingField; // 0x1c
	private Boolean <isSelect>k__BackingField; // 0x1d
	private Int32 <pos>k__BackingField; // 0x20
	private CarvingMainCardViewModel <cardModel>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_cardId; // 0x0
	private static DelegateBridge __Hotfix0_set_cardId; // 0x8
	private static DelegateBridge __Hotfix0_get_price; // 0x10
	private static DelegateBridge __Hotfix0_set_price; // 0x18
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x20
	private static DelegateBridge __Hotfix0_set_isEmpty; // 0x28
	private static DelegateBridge __Hotfix0_get_isSelect; // 0x30
	private static DelegateBridge __Hotfix0_set_isSelect; // 0x38
	private static DelegateBridge __Hotfix0_get_pos; // 0x40
	private static DelegateBridge __Hotfix0_set_pos; // 0x48
	private static DelegateBridge __Hotfix0_get_cardModel; // 0x50
	private static DelegateBridge __Hotfix0_set_cardModel; // 0x58
	private static DelegateBridge __Hotfix0_SetData; // 0x60
	private static DelegateBridge __Hotfix0_SetSelect; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String cardId { get; set; }
	public Int32 price { get; set; }
	public Boolean isEmpty { get; set; }
	public Boolean isSelect { get; set; }
	public Int32 pos { get; set; }
	public CarvingMainCardViewModel cardModel { get; set; }

	// RVA: 0x2dbdd60 VA: 0x75953d5d60
	public String get_cardId() { }
	// RVA: 0x2dbddc8 VA: 0x75953d5dc8
	private Void set_cardId(String value) { }
	// RVA: 0x2dbac34 VA: 0x75953d2c34
	public Int32 get_price() { }
	// RVA: 0x2dbde4c VA: 0x75953d5e4c
	private Void set_price(Int32 value) { }
	// RVA: 0x2dbd288 VA: 0x75953d5288
	public Boolean get_isEmpty() { }
	// RVA: 0x2dbdec8 VA: 0x75953d5ec8
	private Void set_isEmpty(Boolean value) { }
	// RVA: 0x2dbd3c0 VA: 0x75953d53c0
	public Boolean get_isSelect() { }
	// RVA: 0x2dbdf48 VA: 0x75953d5f48
	private Void set_isSelect(Boolean value) { }
	// RVA: 0x2dbdfc8 VA: 0x75953d5fc8
	public Int32 get_pos() { }
	// RVA: 0x2dbe030 VA: 0x75953d6030
	private Void set_pos(Int32 value) { }
	// RVA: 0x2dbd640 VA: 0x75953d5640
	public CarvingMainCardViewModel get_cardModel() { }
	// RVA: 0x2dbe0ac VA: 0x75953d60ac
	private Void set_cardModel(CarvingMainCardViewModel value) { }
	// RVA: 0x2dbcfd0 VA: 0x75953d4fd0
	public Void SetData(ShopGood good, Int32 pos, String actId, Boolean hasSame, Int32 handCardLevel) { }
	// RVA: 0x2dbd8b0 VA: 0x75953d58b0
	public Void SetSelect(Boolean isSelect) { }
	// RVA: 0x2dbce80 VA: 0x75953d4e80
	public Void .ctor() { }
}
```