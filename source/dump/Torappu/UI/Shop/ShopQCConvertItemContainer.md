# ShopQCConvertItemContainer

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Transform _resultContainer`

- `ShopQCConvertResultObj _resultObj`

- `ShopQCConvertListAdapter _listAdapter`


## Methods

- `Void InitData(List`1)`

- `Void InitResult(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopQCConvertItemContainer : MonoBehaviour, IHotfixable
{
	private Transform _resultContainer; // 0x18
	private ShopQCConvertResultObj _resultObj; // 0x20
	private ShopQCConvertListAdapter _listAdapter; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_InitResult; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2459a58 VA: 0x7594a71a58
	public Void InitData(List`1 itemList) { }
	// RVA: 0x2459af8 VA: 0x7594a71af8
	public Void InitResult(List`1 itemList) { }
	// RVA: 0x2459fdc VA: 0x7594a71fdc
	public Void .ctor() { }
}
```