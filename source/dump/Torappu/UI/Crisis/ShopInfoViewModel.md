# ShopInfoViewModel

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `String seasonId`

- `Boolean isFirstTimeToRender`

- `CrisisShopVer shopVer`


## Methods

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class ShopInfoViewModel : IHotfixable
{
	public String seasonId; // 0x10
	public Boolean isFirstTimeToRender; // 0x18
	public List`1 longTermShopList; // 0x20
	public List`1 seasonShopList; // 0x28
	public CrisisShopVer shopVer; // 0x30
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2c365a4 VA: 0x759524e5a4
	public Void RefreshPlayerData() { }
	// RVA: 0x2c36b2c VA: 0x759524eb2c
	public Void .ctor() { }
}
```