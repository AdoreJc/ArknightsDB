# ReusableCollectionItem

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement <bindableElement>k__BackingField`

- `Int32 <index>k__BackingField`

- `Int32 <id>k__BackingField`

- `Boolean <isDragGhost>k__BackingField`


## Properties

- `VisualElement bindableElement`

- `Int32 index`

- `Int32 id`


## Methods

- `VisualElement get_bindableElement()`

- `Void set_bindableElement(VisualElement)`

- `Void set_animator(ValueAnimation`1)`

- `Int32 get_index()`

- `Void set_index(Int32)`

- `Int32 get_id()`

- `Void set_id(Int32)`

- `Void set_isDragGhost(Boolean)`

- `Void add_onGeometryChanged(Action`1)`

- `Void remove_onGeometryChanged(Action`1)`

- `Void OnGeometryChanged(GeometryChangedEvent)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ReusableCollectionItem
{
	private VisualElement <bindableElement>k__BackingField; // 0x10
	private ValueAnimation`1 <animator>k__BackingField; // 0x18
	private Int32 <index>k__BackingField; // 0x20
	private Int32 <id>k__BackingField; // 0x24
	private Boolean <isDragGhost>k__BackingField; // 0x28
	private Action`1 onGeometryChanged; // 0x30
	protected EventCallback`1 m_GeometryChangedEventCallback; // 0x38

	public virtual VisualElement rootElement { get; }
	public VisualElement bindableElement { get; set; }
	public ValueAnimation`1 animator { get; set; }
	public Int32 index { get; set; }
	public Int32 id { get; set; }
	internal Boolean isDragGhost { get; set; }

	// RVA: 0x69a2310 VA: 0x7598fba310
	public virtual VisualElement get_rootElement() { }
	// RVA: 0x69a2318 VA: 0x7598fba318
	public VisualElement get_bindableElement() { }
	// RVA: 0x69a2320 VA: 0x7598fba320
	protected Void set_bindableElement(VisualElement value) { }
	// RVA: 0x69a2328 VA: 0x7598fba328
	public ValueAnimation`1 get_animator() { }
	// RVA: 0x69a2330 VA: 0x7598fba330
	public Void set_animator(ValueAnimation`1 value) { }
	// RVA: 0x69a2338 VA: 0x7598fba338
	public Int32 get_index() { }
	// RVA: 0x69a2340 VA: 0x7598fba340
	public Void set_index(Int32 value) { }
	// RVA: 0x69a2348 VA: 0x7598fba348
	public Int32 get_id() { }
	// RVA: 0x69a2350 VA: 0x7598fba350
	public Void set_id(Int32 value) { }
	// RVA: 0x69a2358 VA: 0x7598fba358
	internal Boolean get_isDragGhost() { }
	// RVA: 0x69a2360 VA: 0x7598fba360
	private Void set_isDragGhost(Boolean value) { }
	// RVA: 0x69a236c VA: 0x7598fba36c
	public Void add_onGeometryChanged(Action`1 value) { }
	// RVA: 0x69a241c VA: 0x7598fba41c
	public Void remove_onGeometryChanged(Action`1 value) { }
	// RVA: 0x69a24cc VA: 0x7598fba4cc
	public Void .ctor() { }
	// RVA: 0x69a2564 VA: 0x7598fba564
	public virtual Void Init(VisualElement item) { }
	// RVA: 0x69a256c VA: 0x7598fba56c
	public virtual Void PreAttachElement() { }
	// RVA: 0x69a2628 VA: 0x7598fba628
	public virtual Void DetachElement() { }
	// RVA: 0x69a2734 VA: 0x7598fba734
	public virtual Void SetSelected(Boolean selected) { }
	// RVA: 0x69a2824 VA: 0x7598fba824
	public virtual Void SetDragGhost(Boolean dragGhost) { }
	// RVA: 0x69a29c4 VA: 0x7598fba9c4
	protected Void OnGeometryChanged(GeometryChangedEvent evt) { }
}
```