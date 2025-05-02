# ShopGPLevelItemViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `LevelGPItem item`

- `PlayerGoodItemData playerInfo`


## Methods

- `PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPLevelItemViewModel : ShopGPCommonItemViewModel, IHotfixable
{
	public LevelGPItem item; // 0x30
	public PlayerGoodItemData playerInfo; // 0x38
	private static DelegateBridge __Hotfix0_ReturnCommonItem; // 0x0
	private static DelegateBridge __Hotfix0_ReturnPlayerInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2446974 VA: 0x7594a5e974
	public override NormalGPItem ReturnCommonItem() { }
	// RVA: 0x24469dc VA: 0x7594a5e9dc
	public override PlayerGoodItemData ReturnPlayerInfo() { }
	// RVA: 0x2446a44 VA: 0x7594a5ea44
	public Void .ctor() { }
	// RVA: 0x2446ab0 VA: 0x7594a5eab0
	private PlayerGoodItemData <>xLuaBaseProxy_ReturnPlayerInfo() { }
}
```