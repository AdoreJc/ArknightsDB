# TreeViewReorderableDragAndDropController

**Namespace:** `UnityEngine.UIElements`


## Fields

- `DropData m_DropData`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TreeViewReorderableDragAndDropController : BaseReorderableDragAndDropController
{
	protected DropData m_DropData; // 0x28
	protected readonly TreeView m_TreeView; // 0x30


	// RVA: 0x69dc868 VA: 0x7598ff4868
	public Void .ctor(TreeView view) { }
	// RVA: 0x69dc918 VA: 0x7598ff4918
	protected override Int32 CompareId(Int32 id1, Int32 id2) { }
	// RVA: 0x69dcf68 VA: 0x7598ff4f68
	public override StartDragArgs SetupDragAndDrop(IEnumerable`1 itemIds, Boolean skipText) { }
	// RVA: 0x69dd018 VA: 0x7598ff5018
	public override DragVisualMode HandleDragAndDrop(IListDragAndDropArgs args) { }
	// RVA: 0x69dd160 VA: 0x7598ff5160
	public override Void OnDrop(IListDragAndDropArgs args) { }
	// RVA: 0x69dd868 VA: 0x7598ff5868
	public override Void DragCleanup() { }
}
```