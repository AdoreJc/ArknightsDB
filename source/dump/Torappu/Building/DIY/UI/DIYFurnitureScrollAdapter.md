# DIYFurnitureScrollAdapter

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject _furnitureViewPrefab`


## Methods

- `Void add_furnitureSubButtonPressed(Func`2)`

- `Void remove_furnitureSubButtonPressed(Func`2)`

- `Void add_renameButtonPressed(Func`2)`

- `Void remove_renameButtonPressed(Func`2)`

- `Void _OnButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void _OnSubButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void _OnRenameButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void _OnInfoButtonPressed(DIYItemViewData, FurnitureItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureScrollAdapter : LoopScrollAdapter`2
{
	private GameObject _furnitureViewPrefab; // 0x58
	public Func`2 furnitureSelected; // 0x60
	private Func`2 furnitureSubButtonPressed; // 0x68
	private Func`2 renameButtonPressed; // 0x70
	public Func`2 infoButtonPressed; // 0x78
	private static DelegateBridge __Hotfix0_add_furnitureSubButtonPressed; // 0x0
	private static DelegateBridge __Hotfix0_remove_furnitureSubButtonPressed; // 0x8
	private static DelegateBridge __Hotfix0_add_renameButtonPressed; // 0x10
	private static DelegateBridge __Hotfix0_remove_renameButtonPressed; // 0x18
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x20
	private static DelegateBridge __Hotfix0__OnSubButtonPressed; // 0x28
	private static DelegateBridge __Hotfix0__OnRenameButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0__OnInfoButtonPressed; // 0x38
	private static DelegateBridge __Hotfix0_UpdateView; // 0x40
	private static DelegateBridge __Hotfix0_CreateView; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x381cc5c VA: 0x7595e34c5c
	public Void add_furnitureSubButtonPressed(Func`2 value) { }
	// RVA: 0x381cd50 VA: 0x7595e34d50
	public Void remove_furnitureSubButtonPressed(Func`2 value) { }
	// RVA: 0x381ce44 VA: 0x7595e34e44
	public Void add_renameButtonPressed(Func`2 value) { }
	// RVA: 0x381cf38 VA: 0x7595e34f38
	public Void remove_renameButtonPressed(Func`2 value) { }
	// RVA: 0x381d02c VA: 0x7595e3502c
	private Void _OnButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x381db4c VA: 0x7595e35b4c
	private Void _OnSubButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x381dc44 VA: 0x7595e35c44
	private Void _OnRenameButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x381dd3c VA: 0x7595e35d3c
	private Void _OnInfoButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x381de34 VA: 0x7595e35e34
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, DIYItemViewData data) { }
	// RVA: 0x381e9d4 VA: 0x7595e369d4
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x381ea94 VA: 0x7595e36a94
	public Void .ctor() { }
}
```