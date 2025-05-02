# ShopGPOnceItemViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `NormalGPItem item`

- `PlayerGoodItemData playerInfo`


## Methods

- `PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPOnceItemViewModel : ShopGPCommonItemViewModel, IHotfixable
{
	public NormalGPItem item; // 0x30
	public PlayerGoodItemData playerInfo; // 0x38
	private static DelegateBridge __Hotfix0_ReturnCommonItem; // 0x0
	private static DelegateBridge __Hotfix0_ReturnPlayerInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2446b88 VA: 0x7594a5eb88
	public override NormalGPItem ReturnCommonItem() { }
	// RVA: 0x2446bf0 VA: 0x7594a5ebf0
	public override PlayerGoodItemData ReturnPlayerInfo() { }
	// RVA: 0x2446c58 VA: 0x7594a5ec58
	public Void .ctor() { }
	// RVA: 0x2446cc4 VA: 0x7594a5ecc4
	private PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo() { }
}
```