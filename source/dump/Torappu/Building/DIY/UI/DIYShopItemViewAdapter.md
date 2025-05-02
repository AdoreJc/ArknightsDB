# DIYShopItemViewAdapter

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject _furnitureViewPrefab`


## Methods

- `Void add_furnitureSelected(Action`1)`

- `Void remove_furnitureSelected(Action`1)`

- `Void _OnButtonPressed(DIYShopItemViewData, ShopFurnitureItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYShopItemViewAdapter : LoopScrollAdapter`2
{
	private GameObject _furnitureViewPrefab; // 0x58
	private Action`1 furnitureSelected; // 0x60
	private static DelegateBridge __Hotfix0_add_furnitureSelected; // 0x0
	private static DelegateBridge __Hotfix0_remove_furnitureSelected; // 0x8
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x10
	private static DelegateBridge __Hotfix0_CreateView; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3804c80 VA: 0x7595e1cc80
	public Void add_furnitureSelected(Action`1 value) { }
	// RVA: 0x3804d74 VA: 0x7595e1cd74
	public Void remove_furnitureSelected(Action`1 value) { }
	// RVA: 0x3804e68 VA: 0x7595e1ce68
	private Void _OnButtonPressed(DIYShopItemViewData data, ShopFurnitureItemView view) { }
	// RVA: 0x3804f10 VA: 0x7595e1cf10
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3804fd0 VA: 0x7595e1cfd0
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, DIYShopItemViewData data) { }
	// RVA: 0x3805180 VA: 0x7595e1d180
	public Void .ctor() { }
}
```