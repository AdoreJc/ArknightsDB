# ShopGPMonthlySubItemViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `MonthlySubItem item`

- `PlayerMonthlySubPer playerInfo`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPMonthlySubItemViewModel : ShopGPCommonItemViewModel, IHotfixable
{
	public MonthlySubItem item; // 0x30
	public PlayerMonthlySubPer playerInfo; // 0x38
	private static DelegateBridge __Hotfix0_ReturnCommonItem; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2446ab4 VA: 0x7594a5eab4
	public override NormalGPItem ReturnCommonItem() { }
	// RVA: 0x2446b1c VA: 0x7594a5eb1c
	public Void .ctor() { }
}
```