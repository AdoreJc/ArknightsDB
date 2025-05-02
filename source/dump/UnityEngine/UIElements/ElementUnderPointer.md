# ElementUnderPointer

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Vector2 GetEventPointerPosition(EventBase)`

- `Void SetElementUnderPointer(VisualElement, Int32, EventBase, Boolean)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ElementUnderPointer
{
	private VisualElement[] m_PendingTopElementUnderPointer; // 0x10
	private VisualElement[] m_TopElementUnderPointer; // 0x18
	private IPointerEvent[] m_TriggerPointerEvent; // 0x20
	private IMouseEvent[] m_TriggerMouseEvent; // 0x28
	private Vector2[] m_PickingPointerPositions; // 0x30
	private Boolean[] m_IsPickingPointerTemporaries; // 0x38


	// RVA: 0x69deb4c VA: 0x7598ff6b4c
	internal VisualElement GetTopElementUnderPointer(Int32 pointerId, out Vector2 pickPosition, out Boolean isTemporary) { }
	// RVA: 0x69debc0 VA: 0x7598ff6bc0
	internal VisualElement GetTopElementUnderPointer(Int32 pointerId) { }
	// RVA: 0x69debf0 VA: 0x7598ff6bf0
	internal Void SetElementUnderPointer(VisualElement newElementUnderPointer, Int32 pointerId, Vector2 pointerPos) { }
	// RVA: 0x69ded78 VA: 0x7598ff6d78
	private Vector2 GetEventPointerPosition(EventBase triggerEvent) { }
	// RVA: 0x69def30 VA: 0x7598ff6f30
	internal Void SetTemporaryElementUnderPointer(VisualElement newElementUnderPointer, Int32 pointerId, EventBase triggerEvent) { }
	// RVA: 0x69df1ac VA: 0x7598ff71ac
	internal Void SetElementUnderPointer(VisualElement newElementUnderPointer, Int32 pointerId, EventBase triggerEvent) { }
	// RVA: 0x69def38 VA: 0x7598ff6f38
	private Void SetElementUnderPointer(VisualElement newElementUnderPointer, Int32 pointerId, EventBase triggerEvent, Boolean temporary) { }
	// RVA: 0x69df1b4 VA: 0x7598ff71b4
	internal Void CommitElementUnderPointers(EventDispatcher dispatcher, ContextType contextType) { }
	// RVA: 0x69e0588 VA: 0x7598ff8588
	public Void .ctor() { }
}
```