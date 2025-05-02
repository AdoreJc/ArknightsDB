# QCShopClassicViewModel

**Namespace:** `Torappu.UI.Shop`


## Methods

- `Void ApplyData(GetClassicGoodListResponse)`

- `Void CollectItemBase(ItemBundle)`

- `Boolean CheckShopChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopClassicViewModel : MonoBehaviour, IHotfixable
{
	public List`1 commonObjList; // 0x18
	public Dictionary`2 fesGachaCurrent; // 0x20
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_CollectItemBase; // 0x8
	private static DelegateBridge __Hotfix0_CheckShopChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x244f50c VA: 0x7594a6750c
	public Void ApplyData(GetClassicGoodListResponse response) { }
	// RVA: 0x244ffc4 VA: 0x7594a67fc4
	private Void CollectItemBase(ItemBundle item) { }
	// RVA: 0x244fd9c VA: 0x7594a67d9c
	public Boolean CheckShopChanged() { }
	// RVA: 0x2450128 VA: 0x7594a68128
	public Void .ctor() { }
}
```