# SkinGoodListServerDataUtil

**Namespace:** `Torappu.UI.Shop`


## Fields

- `SkinGoodListDataFromServer m_goodListDataFromServer`


## Methods

- `Void _RequestSkinGoodListIfNeeded(Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SkinGoodListServerDataUtil : Singleton`1
{
	private SkinGoodListDataFromServer m_goodListDataFromServer; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadShopSkinData; // 0x8
	private static DelegateBridge __Hotfix0_GetAllShopSkinData; // 0x10
	private static DelegateBridge __Hotfix0_ClearCacheAfterBuySkin; // 0x18
	private static DelegateBridge __Hotfix0_ResetDataInSkinShop; // 0x20
	private static DelegateBridge __Hotfix0_RequestSkinGoodListIfNeeded; // 0x28
	private static DelegateBridge __Hotfix0__RequestSkinGoodListIfNeeded; // 0x30


	// RVA: 0x2469d1c VA: 0x7594a81d1c
	private Void .ctor() { }
	// RVA: 0x2469de8 VA: 0x7594a81de8
	public static Void LoadShopSkinData(String charId, ref List`1 result) { }
	// RVA: 0x246a01c VA: 0x7594a8201c
	public static List`1 GetAllShopSkinData() { }
	// RVA: 0x246510c VA: 0x7594a7d10c
	public static Void ClearCacheAfterBuySkin() { }
	// RVA: 0x246a0a4 VA: 0x7594a820a4
	public static Void ResetDataInSkinShop(GetSkinGoodListResponse response) { }
	// RVA: 0x246a1e0 VA: 0x7594a821e0
	public static Void RequestSkinGoodListIfNeeded(Action onFinished) { }
	// RVA: 0x246a26c VA: 0x7594a8226c
	private Void _RequestSkinGoodListIfNeeded(Action onFinished) { }
}
```