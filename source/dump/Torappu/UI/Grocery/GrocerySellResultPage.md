# GrocerySellResultPage

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String m_actId`

- `SellGoodState m_sellGoodState`


## Properties

- `String activityId`

- `SellGoodState sellGoodState`


## Methods

- `String get_activityId()`

- `SellGoodState get_sellGoodState()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultPage : StateEnginePage, IHotfixable
{
	private String m_actId; // 0xe8
	private SellGoodState m_sellGoodState; // 0xf0
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_get_sellGoodState; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String activityId { get; }
	public SellGoodState sellGoodState { get; }

	// RVA: 0x28a408c VA: 0x7594ebc08c
	public String get_activityId() { }
	// RVA: 0x28a40f4 VA: 0x7594ebc0f4
	public SellGoodState get_sellGoodState() { }
	// RVA: 0x28a6c64 VA: 0x7594ebec64
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x28a6d2c VA: 0x7594ebed2c
	public Void .ctor() { }
	// RVA: 0x28a6d9c VA: 0x7594ebed9c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```