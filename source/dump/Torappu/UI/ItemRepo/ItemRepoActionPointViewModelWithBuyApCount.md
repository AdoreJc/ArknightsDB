# ItemRepoActionPointViewModelWithBuyApCount

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `IntProperty afterBuyProperty`

- `Int32 m_buyAPCount`

- `Boolean m_blockApCountRefresh`


## Properties

- `Int32 buyAPCount`

- `Boolean blockApCountRefresh`


## Methods

- `Int32 get_buyAPCount()`

- `Void set_buyAPCount(Int32)`

- `Boolean get_blockApCountRefresh()`

- `Void set_blockApCountRefresh(Boolean)`

- `Void <>xLuaBaseProxy_UpdateApInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoActionPointViewModelWithBuyApCount : ActionPointViewModel, IHotfixable
{
	public IntProperty afterBuyProperty; // 0x50
	private Int32 m_buyAPCount; // 0x58
	private Boolean m_blockApCountRefresh; // 0x5c
	private static DelegateBridge __Hotfix0_get_buyAPCount; // 0x0
	private static DelegateBridge __Hotfix0_set_buyAPCount; // 0x8
	private static DelegateBridge __Hotfix0_get_blockApCountRefresh; // 0x10
	private static DelegateBridge __Hotfix0_set_blockApCountRefresh; // 0x18
	private static DelegateBridge __Hotfix0_UpdateApInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Int32 buyAPCount { get; set; }
	public Boolean blockApCountRefresh { get; set; }

	// RVA: 0x2d30f48 VA: 0x7595348f48
	public Int32 get_buyAPCount() { }
	// RVA: 0x2d30fb0 VA: 0x7595348fb0
	public Void set_buyAPCount(Int32 value) { }
	// RVA: 0x2d3103c VA: 0x759534903c
	public Boolean get_blockApCountRefresh() { }
	// RVA: 0x2d310a4 VA: 0x75953490a4
	public Void set_blockApCountRefresh(Boolean value) { }
	// RVA: 0x2d31148 VA: 0x7595349148
	protected override Void UpdateApInfo() { }
	// RVA: 0x2d31230 VA: 0x7595349230
	public Void .ctor() { }
	// RVA: 0x2d312e0 VA: 0x75953492e0
	private Void <>xLuaBaseProxy_UpdateApInfo() { }
}
```