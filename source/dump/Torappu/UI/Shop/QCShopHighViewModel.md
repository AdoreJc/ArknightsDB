# QCShopHighViewModel

**Namespace:** `Torappu.UI.Shop`


## Methods

- `Void ApplyData(GetHighGoodListResponse)`

- `Void CollectItemBase(ItemBundle)`

- `Boolean CheckShopChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopHighViewModel : MonoBehaviour, IHotfixable
{
	public List`1 commonObjList; // 0x18
	public Dictionary`2 fesGachaCurrent; // 0x20
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_CollectItemBase; // 0x8
	private static DelegateBridge __Hotfix0_CheckShopChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2454d04 VA: 0x7594a6cd04
	public Void ApplyData(GetHighGoodListResponse response) { }
	// RVA: 0x245577c VA: 0x7594a6d77c
	private Void CollectItemBase(ItemBundle item) { }
	// RVA: 0x2455564 VA: 0x7594a6d564
	public Boolean CheckShopChanged() { }
	// RVA: 0x24558d8 VA: 0x7594a6d8d8
	public Void .ctor() { }
}
```