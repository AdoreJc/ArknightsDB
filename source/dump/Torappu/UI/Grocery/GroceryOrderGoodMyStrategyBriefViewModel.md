# GroceryOrderGoodMyStrategyBriefViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <goodId>k__BackingField`

- `String <goodDesc>k__BackingField`

- `Int32 <index>k__BackingField`

- `String <strategy>k__BackingField`


## Properties

- `String goodId`

- `String goodDesc`

- `Int32 index`

- `String strategy`


## Methods

- `String get_goodId()`

- `Void set_goodId(String)`

- `String get_goodDesc()`

- `Void set_goodDesc(String)`

- `Int32 get_index()`

- `Void set_index(Int32)`

- `String get_strategy()`

- `Void set_strategy(String)`

- `Void LoadData(String, String, List`1)`

- `Void RefreshStrategy(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderGoodMyStrategyBriefViewModel : IHotfixable
{
	private String <goodId>k__BackingField; // 0x10
	private String <goodDesc>k__BackingField; // 0x18
	private Int32 <index>k__BackingField; // 0x20
	private String <strategy>k__BackingField; // 0x28
	private List`1 m_strategyNameList; // 0x30
	private static DelegateBridge __Hotfix0_get_goodId; // 0x0
	private static DelegateBridge __Hotfix0_set_goodId; // 0x8
	private static DelegateBridge __Hotfix0_get_goodDesc; // 0x10
	private static DelegateBridge __Hotfix0_set_goodDesc; // 0x18
	private static DelegateBridge __Hotfix0_get_index; // 0x20
	private static DelegateBridge __Hotfix0_set_index; // 0x28
	private static DelegateBridge __Hotfix0_get_strategy; // 0x30
	private static DelegateBridge __Hotfix0_set_strategy; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshStrategy; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String goodId { get; set; }
	public String goodDesc { get; set; }
	public Int32 index { get; set; }
	public String strategy { get; set; }

	// RVA: 0x2889008 VA: 0x7594ea1008
	public String get_goodId() { }
	// RVA: 0x2892398 VA: 0x7594eaa398
	private Void set_goodId(String value) { }
	// RVA: 0x2889070 VA: 0x7594ea1070
	public String get_goodDesc() { }
	// RVA: 0x289241c VA: 0x7594eaa41c
	private Void set_goodDesc(String value) { }
	// RVA: 0x28924a0 VA: 0x7594eaa4a0
	public Int32 get_index() { }
	// RVA: 0x2892508 VA: 0x7594eaa508
	private Void set_index(Int32 value) { }
	// RVA: 0x28890d8 VA: 0x7594ea10d8
	public String get_strategy() { }
	// RVA: 0x2892584 VA: 0x7594eaa584
	private Void set_strategy(String value) { }
	// RVA: 0x2892608 VA: 0x7594eaa608
	public Void LoadData(String goodId, String goodDesc, List`1 strategyNameList) { }
	// RVA: 0x28926cc VA: 0x7594eaa6cc
	public Void RefreshStrategy(Int32 strategyIndex) { }
	// RVA: 0x28927e4 VA: 0x7594eaa7e4
	public Void .ctor() { }
}
```