# DefaultDragAndDropClient

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Label m_DraggedInfoLabel`

- `DragVisualMode m_VisualMode`


## Properties

- `DragAndDropData data`


## Methods

- `Void StartDrag(StartDragArgs, Vector3)`

- `Void UpdateDrag(Vector3)`

- `Void AcceptDrag()`

- `Void SetVisualMode(DragVisualMode)`

- `Void DragCleanup()`

- `DragAndDropData get_data()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class DefaultDragAndDropClient : DragAndDropData, IDragAndDrop
{
	private readonly Hashtable m_GenericData; // 0x10
	private Label m_DraggedInfoLabel; // 0x18
	private DragVisualMode m_VisualMode; // 0x20
	private IEnumerable`1 m_UnityObjectReferences; // 0x28

	public override Object source { get; }
	public DragAndDropData data { get; }

	// RVA: 0x69d543c VA: 0x7598fed43c
	public override Object get_source() { }
	// RVA: 0x69d548c VA: 0x7598fed48c
	public override Object GetGenericData(String key) { }
	// RVA: 0x69d54f0 VA: 0x7598fed4f0
	public Void StartDrag(StartDragArgs args, Vector3 pointerPosition) { }
	// RVA: 0x69d5bbc VA: 0x7598fedbbc
	public Void UpdateDrag(Vector3 pointerPosition) { }
	// RVA: 0x69d5d50 VA: 0x7598fedd50
	public Void AcceptDrag() { }
	// RVA: 0x69d5d54 VA: 0x7598fedd54
	public Void SetVisualMode(DragVisualMode mode) { }
	// RVA: 0x69d5d5c VA: 0x7598fedd5c
	public Void DragCleanup() { }
	// RVA: 0x69d5dbc VA: 0x7598feddbc
	public DragAndDropData get_data() { }
	// RVA: 0x69d53c8 VA: 0x7598fed3c8
	public Void .ctor() { }
}
```