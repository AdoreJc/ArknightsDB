# CarvingMainShopGoodSlotItemModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Int32 <curSlotCnt>k__BackingField`

- `Int32 <maxSlotCnt>k__BackingField`

- `Int32 <price>k__BackingField`

- `Boolean <isEmpty>k__BackingField`

- `Boolean <isSelect>k__BackingField`


## Properties

- `Int32 curSlotCnt`

- `Int32 maxSlotCnt`

- `Int32 price`

- `Boolean isEmpty`

- `Boolean isSelect`


## Methods

- `Int32 get_curSlotCnt()`

- `Void set_curSlotCnt(Int32)`

- `Int32 get_maxSlotCnt()`

- `Void set_maxSlotCnt(Int32)`

- `Int32 get_price()`

- `Void set_price(Int32)`

- `Boolean get_isEmpty()`

- `Void set_isEmpty(Boolean)`

- `Boolean get_isSelect()`

- `Void set_isSelect(Boolean)`

- `Void SetData(Int32, Int32, Int32)`

- `Void SetSelect(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainShopGoodSlotItemModel : IHotfixable
{
	private const Int32 EMPTY_COIN_PRICE; // 0x0
	private Int32 <curSlotCnt>k__BackingField; // 0x10
	private Int32 <maxSlotCnt>k__BackingField; // 0x14
	private Int32 <price>k__BackingField; // 0x18
	private Boolean <isEmpty>k__BackingField; // 0x1c
	private Boolean <isSelect>k__BackingField; // 0x1d
	private static DelegateBridge __Hotfix0_get_curSlotCnt; // 0x0
	private static DelegateBridge __Hotfix0_set_curSlotCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_maxSlotCnt; // 0x10
	private static DelegateBridge __Hotfix0_set_maxSlotCnt; // 0x18
	private static DelegateBridge __Hotfix0_get_price; // 0x20
	private static DelegateBridge __Hotfix0_set_price; // 0x28
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x30
	private static DelegateBridge __Hotfix0_set_isEmpty; // 0x38
	private static DelegateBridge __Hotfix0_get_isSelect; // 0x40
	private static DelegateBridge __Hotfix0_set_isSelect; // 0x48
	private static DelegateBridge __Hotfix0_SetData; // 0x50
	private static DelegateBridge __Hotfix0_SetSelect; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Int32 curSlotCnt { get; set; }
	public Int32 maxSlotCnt { get; set; }
	public Int32 price { get; set; }
	public Boolean isEmpty { get; set; }
	public Boolean isSelect { get; set; }

	// RVA: 0x2dbe130 VA: 0x75953d6130
	public Int32 get_curSlotCnt() { }
	// RVA: 0x2dbe198 VA: 0x75953d6198
	private Void set_curSlotCnt(Int32 value) { }
	// RVA: 0x2dbe214 VA: 0x75953d6214
	public Int32 get_maxSlotCnt() { }
	// RVA: 0x2dbe27c VA: 0x75953d627c
	private Void set_maxSlotCnt(Int32 value) { }
	// RVA: 0x2dbad04 VA: 0x75953d2d04
	public Int32 get_price() { }
	// RVA: 0x2dbe2f8 VA: 0x75953d62f8
	private Void set_price(Int32 value) { }
	// RVA: 0x2dbd2f0 VA: 0x75953d52f0
	public Boolean get_isEmpty() { }
	// RVA: 0x2dbe374 VA: 0x75953d6374
	private Void set_isEmpty(Boolean value) { }
	// RVA: 0x2dbd358 VA: 0x75953d5358
	public Boolean get_isSelect() { }
	// RVA: 0x2dbe3f4 VA: 0x75953d63f4
	private Void set_isSelect(Boolean value) { }
	// RVA: 0x2dbd190 VA: 0x75953d5190
	public Void SetData(Int32 iCurSlotCnt, Int32 iMaxSlotCnt, Int32 iCoin) { }
	// RVA: 0x2dbd930 VA: 0x75953d5930
	public Void SetSelect(Boolean isSelect) { }
	// RVA: 0x2dbce10 VA: 0x75953d4e10
	public Void .ctor() { }
}
```