# UIBuildCostScrollAdapter

**Namespace:** `Torappu.Building.UI`


## Fields

- `GameObject _costItemPrefab`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIBuildCostScrollAdapter : LoopScrollAdapter`2
{
	private GameObject _costItemPrefab; // 0x58
	private static DelegateBridge __Hotfix0_CreateView; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d4f814 VA: 0x7596367814
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3d4f8d4 VA: 0x75963678d4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, ArchiCostItemModel data) { }
	// RVA: 0x3d4f9fc VA: 0x75963679fc
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x3d4fa68 VA: 0x7596367a68
	public Void .ctor() { }
}
```