# MouseEventDispatchingStrategy

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Boolean CanDispatchEvent(EventBase)`

- `Void DispatchEvent(EventBase, IPanel)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class MouseEventDispatchingStrategy : IEventDispatchingStrategy
{


	// RVA: 0x69e36b8 VA: 0x7598ffb6b8
	public Boolean CanDispatchEvent(EventBase evt) { }
	// RVA: 0x69e370c VA: 0x7598ffb70c
	public Void DispatchEvent(EventBase evt, IPanel iPanel) { }
	// RVA: 0x69e38a0 VA: 0x7598ffb8a0
	private static Boolean SendEventToTarget(EventBase evt, BaseVisualElementPanel panel) { }
	// RVA: 0x69e38dc VA: 0x7598ffb8dc
	private static Boolean SendEventToRegularTarget(EventBase evt, BaseVisualElementPanel panel) { }
	// RVA: 0x69e3914 VA: 0x7598ffb914
	private static Boolean SendEventToIMGUIContainer(EventBase evt, BaseVisualElementPanel panel) { }
	// RVA: 0x69e3814 VA: 0x7598ffb814
	private static Void SetBestTargetForEvent(EventBase evt, BaseVisualElementPanel panel) { }
	// RVA: 0x69e3b3c VA: 0x7598ffbb3c
	private static Void UpdateElementUnderMouse(EventBase evt, BaseVisualElementPanel panel, out VisualElement elementUnderMouse) { }
	// RVA: 0x69e3af4 VA: 0x7598ffbaf4
	private static Boolean IsDone(EventBase evt) { }
	// RVA: 0x69e3e48 VA: 0x7598ffbe48
	public Void .ctor() { }
}
```