# BuildingStationBPSlot

**Namespace:** `Torappu.Building.UI`


## Fields

- `Image _imgBkg`

- `GameObject _selectedMask`

- `ColorConfig _lightConfig`

- `ColorConfig _darkConfig`

- `StationBPSlotStructModel m_slotModel`

- `ColorConfig m_colorConfig`


## Properties

- `String slotId`


## Methods

- `String get_slotId()`

- `Void Init(BuildingStationBlueprint, StationBPSlotStructModel, StationBPSlotStyle)`

- `Void UpdateContent(StationBPSlotStructModel, Boolean)`

- `Void _UpdateRectTransform(BuildingStationBlueprint, StationBPSlotStructModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingStationBPSlot : MonoBehaviour
{
	private Image _imgBkg; // 0x18
	private GameObject _selectedMask; // 0x20
	private ColorConfig _lightConfig; // 0x28
	private ColorConfig _darkConfig; // 0x68
	private StationBPSlotStructModel m_slotModel; // 0xa8
	private ColorConfig m_colorConfig; // 0xc8

	public String slotId { get; }

	// RVA: 0x3d39a78 VA: 0x7596351a78
	public String get_slotId() { }
	// RVA: 0x3d39a04 VA: 0x7596351a04
	public Void Init(BuildingStationBlueprint layoutView, StationBPSlotStructModel slotModel, StationBPSlotStyle style) { }
	// RVA: 0x3d39a80 VA: 0x7596351a80
	public Void UpdateContent(StationBPSlotStructModel slotModel, Boolean force) { }
	// RVA: 0x3d39cd0 VA: 0x7596351cd0
	private Void _UpdateRectTransform(BuildingStationBlueprint layoutView, StationBPSlotStructModel slotModel) { }
	// RVA: 0x3d39d68 VA: 0x7596351d68
	public Void .ctor() { }
}
```