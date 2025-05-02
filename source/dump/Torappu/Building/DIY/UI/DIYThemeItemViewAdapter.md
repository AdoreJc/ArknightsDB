# DIYThemeItemViewAdapter

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject _furnitureViewPrefab`


## Methods

- `Void add_furnitureSelected(Action`1)`

- `Void remove_furnitureSelected(Action`1)`

- `Void _OnButtonPressed(DIYThemeItemViewData, ThemeFurnitureItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYThemeItemViewAdapter : LoopScrollAdapter`2
{
	private GameObject _furnitureViewPrefab; // 0x58
	private Action`1 furnitureSelected; // 0x60
	private static DelegateBridge __Hotfix0_add_furnitureSelected; // 0x0
	private static DelegateBridge __Hotfix0_remove_furnitureSelected; // 0x8
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x10
	private static DelegateBridge __Hotfix0_CreateView; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x380fefc VA: 0x7595e27efc
	public Void add_furnitureSelected(Action`1 value) { }
	// RVA: 0x380fff0 VA: 0x7595e27ff0
	public Void remove_furnitureSelected(Action`1 value) { }
	// RVA: 0x38100e4 VA: 0x7595e280e4
	private Void _OnButtonPressed(DIYThemeItemViewData data, ThemeFurnitureItemView view) { }
	// RVA: 0x381018c VA: 0x7595e2818c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x381024c VA: 0x7595e2824c
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, DIYThemeItemViewData data) { }
	// RVA: 0x38103fc VA: 0x7595e283fc
	public Void .ctor() { }
}
```