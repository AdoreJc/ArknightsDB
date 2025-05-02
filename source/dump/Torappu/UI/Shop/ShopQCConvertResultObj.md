# ShopQCConvertResultObj

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _itemName`

- `Text _countText`

- `Text _finalCountText`

- `UIItemCard _itemCard`

- `Single _itemScale`

- `Transform _itemContainer`


## Methods

- `Void InitData(UIItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopQCConvertResultObj : MonoBehaviour, IHotfixable
{
	private Text _itemName; // 0x18
	private Text _countText; // 0x20
	private Text _finalCountText; // 0x28
	private UIItemCard _itemCard; // 0x30
	private Single _itemScale; // 0x38
	private Transform _itemContainer; // 0x40
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2459c50 VA: 0x7594a71c50
	public Void InitData(UIItemViewModel viewModel) { }
	// RVA: 0x245a054 VA: 0x7594a72054
	public Void .ctor() { }
}
```