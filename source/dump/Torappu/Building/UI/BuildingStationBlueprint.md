# BuildingStationBlueprint

**Namespace:** `Torappu.Building.UI`


## Fields

- `RectTransform _slotContainer`

- `BuildingStationBPSlot _slotPrefab`

- `Vector2 m_gridUnit`

- `Boolean m_isInited`

- `StationBPSlotStyle m_initSlotStyle`


## Methods

- `Void SetInitSlotStyle(StationBPSlotStyle)`

- `Vector2 GridToPixel(GridPosition)`

- `Void _Init(StationBPViewModel)`

- `Void _UpdateContent(StationBPViewModel)`

- `Void _CalcGridUnit(StationBPViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingStationBlueprint : DataBinder`1
{
	private RectTransform _slotContainer; // 0x20
	private BuildingStationBPSlot _slotPrefab; // 0x28
	private List`1 m_slotViews; // 0x30
	private Vector2 m_gridUnit; // 0x38
	private Boolean m_isInited; // 0x40
	private StationBPSlotStyle m_initSlotStyle; // 0x44
	private static DelegateBridge __Hotfix0_SetInitSlotStyle; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_GridToPixel; // 0x10
	private static DelegateBridge __Hotfix0__Init; // 0x18
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x20
	private static DelegateBridge __Hotfix0__CalcGridUnit; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3d39378 VA: 0x7596351378
	public Void SetInitSlotStyle(StationBPSlotStyle style) { }
	// RVA: 0x3d393f4 VA: 0x75963513f4
	public override Void OnValueChanged(StationBPProperty property) { }
	// RVA: 0x3d3985c VA: 0x759635185c
	public Vector2 GridToPixel(GridPosition grid) { }
	// RVA: 0x3d394ac VA: 0x75963514ac
	private Void _Init(StationBPViewModel viewModel) { }
	// RVA: 0x3d39720 VA: 0x7596351720
	private Void _UpdateContent(StationBPViewModel viewModel) { }
	// RVA: 0x3d398e4 VA: 0x75963518e4
	private Void _CalcGridUnit(StationBPViewModel viewModel) { }
	// RVA: 0x3d39be4 VA: 0x7596351be4
	public Void .ctor() { }
}
```