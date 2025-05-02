# BuildingShopFormulaAdapter

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `Transform _recycleParent`

- `BuildingShopFormulaItemView _itemPrefab`

- `Int32 m_totalCountCache`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopFormulaAdapter : LoopScrollAdapter`2
{
	private Transform _recycleParent; // 0x58
	private BuildingShopFormulaItemView _itemPrefab; // 0x60
	private Int32 m_totalCountCache; // 0x68
	public Action`1 onFormulaClicked; // 0x70
	private static DelegateBridge __Hotfix0_CreateView; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3dbe804 VA: 0x75963d6804
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3dbe8d4 VA: 0x75963d68d4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, SFormulaViewModel data) { }
	// RVA: 0x3dbeb20 VA: 0x75963d6b20
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x3dbebd0 VA: 0x75963d6bd0
	public Void .ctor() { }
}
```