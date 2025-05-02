# PointerEventDispatchingStrategy

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Boolean CanDispatchEvent(EventBase)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class PointerEventDispatchingStrategy : IEventDispatchingStrategy
{


	// RVA: 0x69e6614 VA: 0x7598ffe614
	public Boolean CanDispatchEvent(EventBase evt) { }
	// RVA: 0x69e6668 VA: 0x7598ffe668
	public virtual Void DispatchEvent(EventBase evt, IPanel panel) { }
	// RVA: 0x69e68c8 VA: 0x7598ffe8c8
	private static Void SendEventToTarget(EventBase evt) { }
	// RVA: 0x69e66a0 VA: 0x7598ffe6a0
	private static Void SetBestTargetForEvent(EventBase evt, IPanel panel) { }
	// RVA: 0x69e68ec VA: 0x7598ffe8ec
	private static Void UpdateElementUnderPointer(EventBase evt, IPanel panel, out VisualElement elementUnderPointer) { }
	// RVA: 0x69e6ba4 VA: 0x7598ffeba4
	public Void .ctor() { }
}
```