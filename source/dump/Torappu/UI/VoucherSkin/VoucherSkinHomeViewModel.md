# VoucherSkinHomeViewModel

**Namespace:** `Torappu.UI.VoucherSkin`


## Fields

- `Int64 startTime`

- `Int64 endTime`


## Methods

- `Void LoadData(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherSkin
public class VoucherSkinHomeViewModel : IHotfixable
{
	public List`1 shopGoodList; // 0x10
	public List`1 skinShopGoodModels; // 0x18
	public List`1 voucherSkinGoodModels; // 0x20
	public Int64 startTime; // 0x28
	public Int64 endTime; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2293414 VA: 0x75948ab414
	public Void LoadData(List`1 shopGoodList) { }
	// RVA: 0x2293880 VA: 0x75948ab880
	public Void .ctor() { }
}
```