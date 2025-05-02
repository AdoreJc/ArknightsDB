# ShopGPChooseItemViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `NormalGPItem item`

- `PlayerGoodItemData playerInfo`

- `Int32 boughtCount`


## Methods

- `PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPChooseItemViewModel : ShopGPCommonItemViewModel, IHotfixable
{
	public NormalGPItem item; // 0x30
	public PlayerGoodItemData playerInfo; // 0x38
	public Int32 boughtCount; // 0x40
	private static DelegateBridge __Hotfix0_ReturnCommonItem; // 0x0
	private static DelegateBridge __Hotfix0_ReturnPlayerInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2446cc8 VA: 0x7594a5ecc8
	public override NormalGPItem ReturnCommonItem() { }
	// RVA: 0x2446d30 VA: 0x7594a5ed30
	public override PlayerGoodItemData ReturnPlayerInfo() { }
	// RVA: 0x2446d98 VA: 0x7594a5ed98
	public Void .ctor() { }
	// RVA: 0x2446e04 VA: 0x7594a5ee04
	private PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo() { }
}
```