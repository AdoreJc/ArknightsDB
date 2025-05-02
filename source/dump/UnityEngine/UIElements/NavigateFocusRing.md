# NavigateFocusRing

**Namespace:** `UnityEngine.UIElements`


## Properties

- `FocusController focusController`


## Methods

- `FocusController get_focusController()`

- `FocusChangeDirection GetFocusChangeDirection(Focusable, EventBase)`

- `Focusable GetNextFocusable2D(Focusable, ChangeDirection)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class NavigateFocusRing : IFocusRing
{
	public static readonly ChangeDirection Left; // 0x0
	public static readonly ChangeDirection Right; // 0x8
	public static readonly ChangeDirection Up; // 0x10
	public static readonly ChangeDirection Down; // 0x18
	public static readonly ChangeDirection Next; // 0x20
	public static readonly ChangeDirection Previous; // 0x28
	private readonly VisualElement m_Root; // 0x10
	private readonly VisualElementFocusRing m_Ring; // 0x18

	private FocusController focusController { get; }

	// RVA: 0x69ff49c VA: 0x759901749c
	private FocusController get_focusController() { }
	// RVA: 0x69ff4c0 VA: 0x75990174c0
	public Void .ctor(VisualElement root) { }
	// RVA: 0x69ff558 VA: 0x7599017558
	public FocusChangeDirection GetFocusChangeDirection(Focusable currentFocusable, EventBase e) { }
	// RVA: 0x69ff990 VA: 0x7599017990
	public virtual Focusable GetNextFocusable(Focusable currentFocusable, FocusChangeDirection direction) { }
	// RVA: 0x69ffc44 VA: 0x7599017c44
	private Focusable GetNextFocusable2D(Focusable currentFocusable, ChangeDirection direction) { }
	// RVA: 0x6a002c0 VA: 0x75990182c0
	private static Boolean IsActive(VisualElement v) { }
	// RVA: 0x6a00398 VA: 0x7599018398
	private static Boolean IsNavigable(Focusable focusable) { }
	// RVA: 0x6a003f8 VA: 0x75990183f8
	private static Void .cctor() { }
}
```