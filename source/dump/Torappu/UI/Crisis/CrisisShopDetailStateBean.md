# CrisisShopDetailStateBean

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `CrisisShopVer shopVer`

- `CrisisShopWrapped shopViewModel`


## Properties

- `Int32 coin`


## Methods

- `Int32 get_coin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopDetailStateBean : IStateBean, IHotfixable
{
	public CrisisShopVer shopVer; // 0x10
	public CrisisShopWrapped shopViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_coin; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Int32 coin { get; }

	// RVA: 0x2c1aefc VA: 0x7595232efc
	public Int32 get_coin() { }
	// RVA: 0x2c1afe8 VA: 0x7595232fe8
	public Void .ctor() { }
}
```