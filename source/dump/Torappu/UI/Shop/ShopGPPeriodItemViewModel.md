# ShopGPPeriodItemViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `PeriodicityGPItem item`

- `PlayerGoodItemData playerInfo`

- `Int64 endTime`

- `GPPeriodDetailType detailType`


## Methods

- `PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPPeriodItemViewModel : ShopGPCommonItemViewModel, IHotfixable
{
	public PeriodicityGPItem item; // 0x30
	public PlayerGoodItemData playerInfo; // 0x38
	public Int64 endTime; // 0x40
	public GPPeriodDetailType detailType; // 0x48
	private static DelegateBridge __Hotfix0_ReturnCommonItem; // 0x0
	private static DelegateBridge __Hotfix0_ReturnPlayerInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2446048 VA: 0x7594a5e048
	public override NormalGPItem ReturnCommonItem() { }
	// RVA: 0x24460b0 VA: 0x7594a5e0b0
	public override PlayerGoodItemData ReturnPlayerInfo() { }
	// RVA: 0x2446118 VA: 0x7594a5e118
	public Void .ctor() { }
	// RVA: 0x2446184 VA: 0x7594a5e184
	private PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo() { }
}
```