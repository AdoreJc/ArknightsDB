# ShopGPCondTrigItemViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `CondTrigGPItem item`

- `PlayerGoodItemData playerInfo`

- `Int64 endTime`

- `Int32 currCheckInDay`

- `Int32 totalCheckInDay`

- `Boolean isCheckInPackage`

- `Int32 availCount`

- `Int32 boughtCount`


## Methods

- `Void LoadData(CondTrigGPItem)`

- `Void _LoadReturnOnceData()`

- `Void _LoadReturnProgressData()`

- `Void _LoadNewProgressData()`

- `PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPCondTrigItemViewModel : ShopGPCommonItemViewModel, IHotfixable
{
	public CondTrigGPItem item; // 0x30
	public PlayerGoodItemData playerInfo; // 0x38
	public Int64 endTime; // 0x40
	public Int32 currCheckInDay; // 0x48
	public Int32 totalCheckInDay; // 0x4c
	public Boolean isCheckInPackage; // 0x50
	public Int32 availCount; // 0x54
	public Int32 boughtCount; // 0x58
	private static DelegateBridge __Hotfix0_ReturnCommonItem; // 0x0
	private static DelegateBridge __Hotfix0_ReturnPlayerInfo; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0__LoadReturnOnceData; // 0x18
	private static DelegateBridge __Hotfix0__LoadReturnProgressData; // 0x20
	private static DelegateBridge __Hotfix0__LoadNewProgressData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2446188 VA: 0x7594a5e188
	public override NormalGPItem ReturnCommonItem() { }
	// RVA: 0x24461f0 VA: 0x7594a5e1f0
	public override PlayerGoodItemData ReturnPlayerInfo() { }
	// RVA: 0x2446258 VA: 0x7594a5e258
	public Void LoadData(CondTrigGPItem item) { }
	// RVA: 0x2446390 VA: 0x7594a5e390
	private Void _LoadReturnOnceData() { }
	// RVA: 0x2446504 VA: 0x7594a5e504
	private Void _LoadReturnProgressData() { }
	// RVA: 0x2446708 VA: 0x7594a5e708
	private Void _LoadNewProgressData() { }
	// RVA: 0x2446904 VA: 0x7594a5e904
	public Void .ctor() { }
	// RVA: 0x2446970 VA: 0x7594a5e970
	private PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo() { }
}
```