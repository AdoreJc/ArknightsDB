# BuildingToDoNotifyItemViewHolder

**Namespace:** `Torappu.Building.UI.ToDoNotify`


## Fields

- `BuildingToDoNotifyItemBase _normalItem`

- `BuildingToDoNotifyItemBase _workItem`

- `BuildingToDoNotifyItemBase _restItem`


## Methods

- `Void Render(BuildingToDoCategory, BuildingToDoNotifyItemModel, Boolean, ItemClickStatusData)`

- `Void _OnItemAnimEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.ToDoNotify
public class BuildingToDoNotifyItemViewHolder : MonoBehaviour, IHotfixable
{
	private BuildingToDoNotifyItemBase _normalItem; // 0x18
	private BuildingToDoNotifyItemBase _workItem; // 0x20
	private BuildingToDoNotifyItemBase _restItem; // 0x28
	public Action`1 onClicked; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__OnItemAnimEnd; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d8c5a0 VA: 0x75963a45a0
	public Void Render(BuildingToDoCategory category, BuildingToDoNotifyItemModel itemModel, Boolean isSelected, ItemClickStatusData itemClickStatusData) { }
	// RVA: 0x3d8c8f0 VA: 0x75963a48f0
	private Void _OnItemAnimEnd() { }
	// RVA: 0x3d8c968 VA: 0x75963a4968
	public Void .ctor() { }
}
```