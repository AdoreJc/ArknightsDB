# BuildingStationSelectCharAdapter

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `BuildingStationSelectCharItemView _charPrefab`

- `IPlugin m_selectPlugin`

- `Boolean m_AVGIsFirstItemRegistered`

- `CharSortType m_sortType`

- `StationSelectStateBeanInputType m_selectType`

- `Int32 maxSelectCount`


## Methods

- `Void SetParams(List`1, CharSortType, StationSelectStateBeanInputType, IPlugin)`

- `Void _TryRegisterAVGFirstItem(BuildingStationSelectCharItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectCharAdapter : LoopScrollAdapter`2
{
	private BuildingStationSelectCharItemView _charPrefab; // 0x58
	private List`1 m_selectedCharInsts; // 0x60
	private IPlugin m_selectPlugin; // 0x68
	private Boolean m_AVGIsFirstItemRegistered; // 0x70
	private CharSortType m_sortType; // 0x74
	private StationSelectStateBeanInputType m_selectType; // 0x78
	public Action`1 onCharClicked; // 0x80
	public Int32 maxSelectCount; // 0x88
	private static DelegateBridge __Hotfix0_get_selectedCharInsts; // 0x0
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0_SetParams; // 0x20
	private static DelegateBridge __Hotfix0__TryRegisterAVGFirstItem; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 selectedCharInsts { get; }

	// RVA: 0x3d99688 VA: 0x75963b1688
	public List`1 get_selectedCharInsts() { }
	// RVA: 0x3d996f0 VA: 0x75963b16f0
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x3d99774 VA: 0x75963b1774
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3d99844 VA: 0x75963b1844
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, StationCharViewModel data) { }
	// RVA: 0x3d9a038 VA: 0x75963b2038
	public Void SetParams(List`1 selectedChrInstIds, CharSortType sortType, StationSelectStateBeanInputType selectType, IPlugin plugin) { }
	// RVA: 0x3d99ef4 VA: 0x75963b1ef4
	private Void _TryRegisterAVGFirstItem(BuildingStationSelectCharItemView cardView) { }
	// RVA: 0x3d9a0f8 VA: 0x75963b20f8
	public Void .ctor() { }
}
```