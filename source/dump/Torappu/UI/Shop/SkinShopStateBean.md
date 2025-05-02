# SkinShopStateBean

**Namespace:** `Torappu.UI.Shop`


## Methods

- `Void ApplyData(List`1)`

- `Boolean TryGetSkinIdByGoodId(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SkinShopStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public List`1 skinList; // 0x18
	private Dictionary`2 m_goodIdToSkinId; // 0x20
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_TryGetSkinIdByGoodId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x246c07c VA: 0x7594a8407c
	public Void ApplyData(List`1 shopList) { }
	// RVA: 0x246c928 VA: 0x7594a84928
	public Boolean TryGetSkinIdByGoodId(String goodId, out String skinId) { }
	// RVA: 0x246c9d4 VA: 0x7594a849d4
	public Void .ctor() { }
}
```