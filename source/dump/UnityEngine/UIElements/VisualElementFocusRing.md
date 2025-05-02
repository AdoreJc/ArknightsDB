# VisualElementFocusRing

**Namespace:** `UnityEngine.UIElements`


## Fields

- `DefaultFocusOrder <defaultFocusOrder>k__BackingField`


## Properties

- `FocusController focusController`

- `DefaultFocusOrder defaultFocusOrder`


## Methods

- `FocusController get_focusController()`

- `DefaultFocusOrder get_defaultFocusOrder()`

- `Void set_defaultFocusOrder(DefaultFocusOrder)`

- `Int32 FocusRingAutoIndexSort(FocusRingRecord, FocusRingRecord)`

- `Int32 FocusRingSort(FocusRingRecord, FocusRingRecord)`

- `Void DoUpdate()`

- `Void BuildRingForScopeRecursive(VisualElement, ref, List`1)`

- `Void SortAndFlattenScopeLists(List`1)`

- `Int32 GetFocusableInternalIndex(Focusable)`

- `FocusChangeDirection GetFocusChangeDirection(Focusable, EventBase)`

- `Focusable GetNextFocusable(Focusable, FocusChangeDirection)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class VisualElementFocusRing : IFocusRing
{
	private readonly VisualElement root; // 0x10
	private DefaultFocusOrder <defaultFocusOrder>k__BackingField; // 0x18
	private List`1 m_FocusRing; // 0x20

	private FocusController focusController { get; }
	public DefaultFocusOrder defaultFocusOrder { get; set; }

	// RVA: 0x6994d98 VA: 0x7598facd98
	public Void .ctor(VisualElement root, DefaultFocusOrder dfo) { }
	// RVA: 0x6994e44 VA: 0x7598face44
	private FocusController get_focusController() { }
	// RVA: 0x6994e68 VA: 0x7598face68
	public DefaultFocusOrder get_defaultFocusOrder() { }
	// RVA: 0x6994e70 VA: 0x7598face70
	public Void set_defaultFocusOrder(DefaultFocusOrder value) { }
	// RVA: 0x6994e78 VA: 0x7598face78
	private Int32 FocusRingAutoIndexSort(FocusRingRecord a, FocusRingRecord b) { }
	// RVA: 0x69952c8 VA: 0x7598fad2c8
	private Int32 FocusRingSort(FocusRingRecord a, FocusRingRecord b) { }
	// RVA: 0x69953b8 VA: 0x7598fad3b8
	private Void DoUpdate() { }
	// RVA: 0x6995490 VA: 0x7598fad490
	private Void BuildRingForScopeRecursive(VisualElement ve, ref Int32 scopeIndex, List`1 scopeList) { }
	// RVA: 0x69957d8 VA: 0x7598fad7d8
	private Void SortAndFlattenScopeLists(List`1 rootScopeList) { }
	// RVA: 0x6995ac4 VA: 0x7598fadac4
	private Int32 GetFocusableInternalIndex(Focusable f) { }
	// RVA: 0x6995b6c VA: 0x7598fadb6c
	public FocusChangeDirection GetFocusChangeDirection(Focusable currentFocusable, EventBase e) { }
	// RVA: 0x6995de8 VA: 0x7598fadde8
	internal static FocusChangeDirection GetKeyDownFocusChangeDirection(EventBase e) { }
	// RVA: 0x6995fec VA: 0x7598fadfec
	public Focusable GetNextFocusable(Focusable currentFocusable, FocusChangeDirection direction) { }
	// RVA: 0x69963dc VA: 0x7598fae3dc
	internal static Focusable GetNextFocusableInTree(VisualElement currentFocusable) { }
	// RVA: 0x6996478 VA: 0x7598fae478
	internal static Focusable GetPreviousFocusableInTree(VisualElement currentFocusable) { }
}
```