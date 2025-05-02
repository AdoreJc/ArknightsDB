# PointerDispatchState

**Namespace:** `UnityEngine.UIElements`


## Methods

- `IEventHandler GetCapturingElement(Int32)`

- `Boolean HasPointerCapture(IEventHandler, Int32)`

- `Void CapturePointer(IEventHandler, Int32)`

- `Void ReleasePointer(Int32)`

- `Void ReleasePointer(IEventHandler, Int32)`

- `Void ProcessPointerCapture(Int32)`

- `Void ActivateCompatibilityMouseEvents(Int32)`

- `Void PreventCompatibilityMouseEvents(Int32)`

- `Boolean ShouldSendCompatibilityMouseEvents(IPointerEvent)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class PointerDispatchState
{
	private IEventHandler[] m_PendingPointerCapture; // 0x10
	private IEventHandler[] m_PointerCapture; // 0x18
	private Boolean[] m_ShouldSendCompatibilityMouseEvents; // 0x20


	// RVA: 0x693526c VA: 0x7598f4d26c
	public Void .ctor() { }
	// RVA: 0x6943078 VA: 0x7598f5b078
	internal Void Reset() { }
	// RVA: 0x693c078 VA: 0x7598f54078
	public IEventHandler GetCapturingElement(Int32 pointerId) { }
	// RVA: 0x6942004 VA: 0x7598f5a004
	public Boolean HasPointerCapture(IEventHandler handler, Int32 pointerId) { }
	// RVA: 0x694203c VA: 0x7598f5a03c
	public Void CapturePointer(IEventHandler handler, Int32 pointerId) { }
	// RVA: 0x6942350 VA: 0x7598f5a350
	public Void ReleasePointer(Int32 pointerId) { }
	// RVA: 0x694217c VA: 0x7598f5a17c
	public Void ReleasePointer(IEventHandler handler, Int32 pointerId) { }
	// RVA: 0x6942704 VA: 0x7598f5a704
	public Void ProcessPointerCapture(Int32 pointerId) { }
	// RVA: 0x6942448 VA: 0x7598f5a448
	public Void ActivateCompatibilityMouseEvents(Int32 pointerId) { }
	// RVA: 0x694247c VA: 0x7598f5a47c
	public Void PreventCompatibilityMouseEvents(Int32 pointerId) { }
	// RVA: 0x69425d0 VA: 0x7598f5a5d0
	public Boolean ShouldSendCompatibilityMouseEvents(IPointerEvent evt) { }
}
```