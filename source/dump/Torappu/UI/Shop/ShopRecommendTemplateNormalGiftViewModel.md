# ShopRecommendTemplateNormalGiftViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int64 m_showStartTs`

- `Int64 m_showEndTs`

- `String m_packName`

- `ShopCashInfo m_priceInfo`

- `String m_color`

- `Boolean m_haveMark`

- `String m_logoId`

- `Int32 m_availCount`


## Properties

- `Int64 showStartTs`

- `Int64 showEndTs`

- `String packName`

- `ShopCashInfo priceInfo`

- `String color`

- `Boolean haveMark`

- `String logoId`

- `Int32 availCount`


## Methods

- `Int64 get_showStartTs()`

- `Int64 get_showEndTs()`

- `String get_packName()`

- `ShopCashInfo get_priceInfo()`

- `String get_color()`

- `Boolean get_haveMark()`

- `String get_logoId()`

- `Int32 get_availCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendTemplateNormalGiftViewModel : ShopRecommendTemplateViewModelBase, IHotfixable
{
	protected Int64 m_showStartTs; // 0x18
	protected Int64 m_showEndTs; // 0x20
	private String m_packName; // 0x28
	private ShopCashInfo m_priceInfo; // 0x30
	private String m_color; // 0x40
	private Boolean m_haveMark; // 0x48
	private String m_logoId; // 0x50
	private Int32 m_availCount; // 0x58
	private static DelegateBridge __Hotfix0_get_showStartTs; // 0x0
	private static DelegateBridge __Hotfix0_get_showEndTs; // 0x8
	private static DelegateBridge __Hotfix0_get_packName; // 0x10
	private static DelegateBridge __Hotfix0_get_priceInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_color; // 0x20
	private static DelegateBridge __Hotfix0_get_haveMark; // 0x28
	private static DelegateBridge __Hotfix0_get_logoId; // 0x30
	private static DelegateBridge __Hotfix0_get_availCount; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int64 showStartTs { get; }
	public Int64 showEndTs { get; }
	public String packName { get; }
	public ShopCashInfo priceInfo { get; }
	public String color { get; }
	public Boolean haveMark { get; }
	public String logoId { get; }
	public Int32 availCount { get; }

	// RVA: 0x245fa4c VA: 0x7594a77a4c
	public Int64 get_showStartTs() { }
	// RVA: 0x245fab4 VA: 0x7594a77ab4
	public Int64 get_showEndTs() { }
	// RVA: 0x245fb80 VA: 0x7594a77b80
	public String get_packName() { }
	// RVA: 0x245fb1c VA: 0x7594a77b1c
	public ShopCashInfo get_priceInfo() { }
	// RVA: 0x245fed4 VA: 0x7594a77ed4
	public String get_color() { }
	// RVA: 0x245ff3c VA: 0x7594a77f3c
	public Boolean get_haveMark() { }
	// RVA: 0x245fbe8 VA: 0x7594a77be8
	public String get_logoId() { }
	// RVA: 0x245fe6c VA: 0x7594a77e6c
	public Int32 get_availCount() { }
	// RVA: 0x2460034 VA: 0x7594a78034
	public override Void LoadData(ShopRecommendItem recommendItem) { }
	// RVA: 0x2460174 VA: 0x7594a78174
	public Void .ctor() { }
}
```