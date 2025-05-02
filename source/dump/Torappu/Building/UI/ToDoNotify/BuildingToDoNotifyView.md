# BuildingToDoNotifyView

**Namespace:** `Torappu.Building.UI.ToDoNotify`


## Fields

- `SimpleLayoutContent _layout`

- `BuildingToDoCategory m_selectedCategory`

- `BuildingToDoType m_selectedType`

- `Boolean m_isInited`

- `ItemAdapter m_adapter`

- `ItemClickStatusData m_itemClickStatusData`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(BuildingToDoNotifyModel, BuildingToDoCategory, BuildingToDoType)`

- `Void _UpdateSelectedList(BuildingToDoNotifyModel, BuildingToDoCategory)`

- `Void _InitSelectedList(BuildingToDoNotifyModel, BuildingToDoCategory)`

- `Void _InitIfNot()`

- `Boolean _IsNotifyItemSelected(BuildingToDoNotifyItemModel)`

- `Void _HilightRoomSlots(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.ToDoNotify
public class BuildingToDoNotifyView : MonoBehaviour
{
	private SimpleLayoutContent _layout; // 0x18
	private BuildingToDoCategory m_selectedCategory; // 0x20
	private BuildingToDoType m_selectedType; // 0x24
	private Dictionary`2 m_prefSelectedDict; // 0x28
	private List`1 m_selectedList; // 0x30
	private Boolean m_isInited; // 0x38
	private ItemAdapter m_adapter; // 0x40
	private ItemClickStatusData m_itemClickStatusData; // 0x48
	private List`1 m_selectedSlotIds; // 0x50
	private Action`1 <onClicked>k__BackingField; // 0x58

	private Action`1 onClicked { get; set; }

	// RVA: 0x3d8c9d8 VA: 0x75963a49d8
	private Action`1 get_onClicked() { }
	// RVA: 0x3d8c9e0 VA: 0x75963a49e0
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x3d8c9e8 VA: 0x75963a49e8
	public Void Render(BuildingToDoNotifyModel viewModel, BuildingToDoCategory selectedCategory, BuildingToDoType selectedType) { }
	// RVA: 0x3d8cf54 VA: 0x75963a4f54
	private Void _UpdateSelectedList(BuildingToDoNotifyModel viewModel, BuildingToDoCategory selectedCategory) { }
	// RVA: 0x3d8cce8 VA: 0x75963a4ce8
	private Void _InitSelectedList(BuildingToDoNotifyModel viewModel, BuildingToDoCategory selectedCategory) { }
	// RVA: 0x3d8cbfc VA: 0x75963a4bfc
	private Void _InitIfNot() { }
	// RVA: 0x3d8d778 VA: 0x75963a5778
	private Boolean _IsNotifyItemSelected(BuildingToDoNotifyItemModel model) { }
	// RVA: 0x3d8d5f4 VA: 0x75963a55f4
	private Void _HilightRoomSlots(List`1 slotIds) { }
	// RVA: 0x3d8d858 VA: 0x75963a5858
	public Void .ctor() { }
}
```