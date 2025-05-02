# BuildingManufactListAdapter

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Transform _recycleParent`

- `BuildingManufactFormulaItemView _itemPrefab`

- `GameObjectPool m_objectPool`

- `String selectedItemId`

- `Int32 m_totalCountCache`

- `Boolean m_AVGIsFirstItemRegistered`


## Methods

- `Void _TryRegisterAVGFirstItem(BuildingManufactFormulaItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactListAdapter : LoopScrollAdapter`2
{
	private Transform _recycleParent; // 0x58
	private BuildingManufactFormulaItemView _itemPrefab; // 0x60
	private GameObjectPool m_objectPool; // 0x68
	public String selectedItemId; // 0x70
	public Action`1 onFormulaClicked; // 0x78
	private Int32 m_totalCountCache; // 0x80
	private Boolean m_AVGIsFirstItemRegistered; // 0x84
	private static DelegateBridge __Hotfix0_CreateView; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x10
	private static DelegateBridge __Hotfix0__TryRegisterAVGFirstItem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3e0b3f4 VA: 0x75964233f4
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3e0b4c4 VA: 0x75964234c4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, MFormulaViewModel data) { }
	// RVA: 0x3e0b768 VA: 0x7596423768
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x3e0b624 VA: 0x7596423624
	private Void _TryRegisterAVGFirstItem(BuildingManufactFormulaItemView view) { }
	// RVA: 0x3e0b81c VA: 0x759642381c
	public Void .ctor() { }
}
```