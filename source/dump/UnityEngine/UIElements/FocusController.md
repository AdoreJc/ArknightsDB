# FocusController

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Focusable m_LastFocusedElement`

- `Focusable m_LastPendingFocusedElement`

- `Int32 m_PendingFocusCount`

- `Int32 <imguiKeyboardControl>k__BackingField`


## Properties

- `IFocusRing focusRing`

- `Focusable focusedElement`


## Methods

- `IFocusRing get_focusRing()`

- `Focusable get_focusedElement()`

- `Boolean IsLocalElement(Focusable)`

- `Void AboutToReleaseFocus(Focusable, Focusable, FocusChangeDirection, DispatchMode)`

- `Void ReleaseFocus(Focusable, Focusable, FocusChangeDirection, DispatchMode)`

- `Void AboutToGrabFocus(Focusable, Focusable, FocusChangeDirection, DispatchMode)`

- `Void GrabFocus(Focusable, Focusable, FocusChangeDirection, Boolean, DispatchMode)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class FocusController
{
	private readonly IFocusRing <focusRing>k__BackingField; // 0x10
	private List`1 m_FocusedElements; // 0x18
	private Focusable m_LastFocusedElement; // 0x20
	private Focusable m_LastPendingFocusedElement; // 0x28
	private Int32 m_PendingFocusCount; // 0x30
	private Int32 <imguiKeyboardControl>k__BackingField; // 0x34

	private IFocusRing focusRing { get; }
	public Focusable focusedElement { get; }
	internal Int32 imguiKeyboardControl { get; set; }

	// RVA: 0x6937284 VA: 0x7598f4f284
	public Void .ctor(IFocusRing focusRing) { }
	// RVA: 0x6937334 VA: 0x7598f4f334
	private IFocusRing get_focusRing() { }
	// RVA: 0x6933910 VA: 0x7598f4b910
	public Focusable get_focusedElement() { }
	// RVA: 0x693757c VA: 0x7598f4f57c
	internal Boolean IsFocused(Focusable f) { }
	// RVA: 0x693733c VA: 0x7598f4f33c
	internal Focusable GetRetargetedFocusedElement(VisualElement retargetAgainst) { }
	// RVA: 0x69376f0 VA: 0x7598f4f6f0
	internal Focusable GetLeafFocusedElement() { }
	// RVA: 0x6937540 VA: 0x7598f4f540
	private Boolean IsLocalElement(Focusable f) { }
	// RVA: 0x6937794 VA: 0x7598f4f794
	internal Boolean IsPendingFocus(Focusable f) { }
	// RVA: 0x6937844 VA: 0x7598f4f844
	internal Void SetFocusToLastFocusedElement() { }
	// RVA: 0x69378cc VA: 0x7598f4f8cc
	internal Void BlurLastFocusedElement() { }
	// RVA: 0x6937968 VA: 0x7598f4f968
	internal Void DoFocusChange(Focusable f) { }
	// RVA: 0x6937b4c VA: 0x7598f4fb4c
	internal Focusable FocusNextInDirection(FocusChangeDirection direction) { }
	// RVA: 0x6937c38 VA: 0x7598f4fc38
	private Void AboutToReleaseFocus(Focusable focusable, Focusable willGiveFocusTo, FocusChangeDirection direction, DispatchMode dispatchMode) { }
	// RVA: 0x6937dfc VA: 0x7598f4fdfc
	private Void ReleaseFocus(Focusable focusable, Focusable willGiveFocusTo, FocusChangeDirection direction, DispatchMode dispatchMode) { }
	// RVA: 0x6937fc0 VA: 0x7598f4ffc0
	private Void AboutToGrabFocus(Focusable focusable, Focusable willTakeFocusFrom, FocusChangeDirection direction, DispatchMode dispatchMode) { }
	// RVA: 0x6938184 VA: 0x7598f50184
	private Void GrabFocus(Focusable focusable, Focusable willTakeFocusFrom, FocusChangeDirection direction, Boolean bIsFocusDelegated, DispatchMode dispatchMode) { }
	// RVA: 0x6936810 VA: 0x7598f4e810
	internal Void Blur(Focusable focusable, Boolean bIsFocusDelegated, DispatchMode dispatchMode) { }
	// RVA: 0x6936720 VA: 0x7598f4e720
	internal Void SwitchFocus(Focusable newFocusedElement, Boolean bIsFocusDelegated, DispatchMode dispatchMode) { }
	// RVA: 0x6936ed8 VA: 0x7598f4eed8
	internal Void SwitchFocus(Focusable newFocusedElement, FocusChangeDirection direction, Boolean bIsFocusDelegated, DispatchMode dispatchMode) { }
	// RVA: 0x6936a78 VA: 0x7598f4ea78
	internal Focusable SwitchFocusOnEvent(EventBase e) { }
	// RVA: 0x6938354 VA: 0x7598f50354
	internal Void ReevaluateFocus() { }
	// RVA: 0x6938414 VA: 0x7598f50414
	internal Boolean GetFocusableParentForPointerEvent(Focusable target, out Focusable effectiveTarget) { }
	// RVA: 0x6938548 VA: 0x7598f50548
	internal Int32 get_imguiKeyboardControl() { }
	// RVA: 0x6938550 VA: 0x7598f50550
	internal Void set_imguiKeyboardControl(Int32 value) { }
	// RVA: 0x6938558 VA: 0x7598f50558
	internal Void SyncIMGUIFocus(Int32 imguiKeyboardControlID, Focusable imguiContainerHavingKeyboardControl, Boolean forceSwitch) { }
}
```