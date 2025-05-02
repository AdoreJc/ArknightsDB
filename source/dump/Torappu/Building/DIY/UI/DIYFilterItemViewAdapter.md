# DIYFilterItemViewAdapter

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject _furnitureViewPrefab`


## Methods

- `Void add_furnitureSelected(Action`1)`

- `Void remove_furnitureSelected(Action`1)`

- `Void add_infoSelected(Action`1)`

- `Void remove_infoSelected(Action`1)`

- `Void add_descSelected(Action`1)`

- `Void remove_descSelected(Action`1)`

- `Void _OnButtonPressed(DIYShopFilterViewData)`

- `Void _OnButtonInfoPressed(DIYShopFilterViewData)`

- `Void _OnButtonDescPressed(DIYShopFilterViewData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFilterItemViewAdapter : LoopScrollAdapter`2
{
	private GameObject _furnitureViewPrefab; // 0x58
	private Action`1 furnitureSelected; // 0x60
	private Action`1 infoSelected; // 0x68
	private Action`1 descSelected; // 0x70
	private static DelegateBridge __Hotfix0_add_furnitureSelected; // 0x0
	private static DelegateBridge __Hotfix0_remove_furnitureSelected; // 0x8
	private static DelegateBridge __Hotfix0_add_infoSelected; // 0x10
	private static DelegateBridge __Hotfix0_remove_infoSelected; // 0x18
	private static DelegateBridge __Hotfix0_add_descSelected; // 0x20
	private static DelegateBridge __Hotfix0_remove_descSelected; // 0x28
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0__OnButtonInfoPressed; // 0x38
	private static DelegateBridge __Hotfix0__OnButtonDescPressed; // 0x40
	private static DelegateBridge __Hotfix0_CreateView; // 0x48
	private static DelegateBridge __Hotfix0_UpdateView; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x37ff038 VA: 0x7595e17038
	public Void add_furnitureSelected(Action`1 value) { }
	// RVA: 0x37ff12c VA: 0x7595e1712c
	public Void remove_furnitureSelected(Action`1 value) { }
	// RVA: 0x37ff220 VA: 0x7595e17220
	public Void add_infoSelected(Action`1 value) { }
	// RVA: 0x37ff314 VA: 0x7595e17314
	public Void remove_infoSelected(Action`1 value) { }
	// RVA: 0x37ff408 VA: 0x7595e17408
	public Void add_descSelected(Action`1 value) { }
	// RVA: 0x37ff4fc VA: 0x7595e174fc
	public Void remove_descSelected(Action`1 value) { }
	// RVA: 0x37ff5f0 VA: 0x7595e175f0
	private Void _OnButtonPressed(DIYShopFilterViewData data) { }
	// RVA: 0x37ff690 VA: 0x7595e17690
	private Void _OnButtonInfoPressed(DIYShopFilterViewData data) { }
	// RVA: 0x37ff730 VA: 0x7595e17730
	private Void _OnButtonDescPressed(DIYShopFilterViewData data) { }
	// RVA: 0x37ff7d0 VA: 0x7595e177d0
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x37ff890 VA: 0x7595e17890
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, DIYShopFilterViewData data) { }
	// RVA: 0x37ffb28 VA: 0x7595e17b28
	public Void .ctor() { }
}
```