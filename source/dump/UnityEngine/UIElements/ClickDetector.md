# ClickDetector

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Void StartClickTracking(EventBase)`

- `Void SendClickEvent(EventBase)`

- `Void CancelClickTracking(EventBase)`

- `Void ProcessEvent(EventBase)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ClickDetector
{
	private List`1 m_ClickStatus; // 0x10
	private static Int32 <s_DoubleClickTime>k__BackingField; // 0x0

	internal static Int32 s_DoubleClickTime { get; set; }

	// RVA: 0x6930e80 VA: 0x7598f48e80
	internal static Int32 get_s_DoubleClickTime() { }
	// RVA: 0x6930ed8 VA: 0x7598f48ed8
	internal static Void set_s_DoubleClickTime(Int32 value) { }
	// RVA: 0x6930f34 VA: 0x7598f48f34
	public Void .ctor() { }
	// RVA: 0x69311b0 VA: 0x7598f491b0
	private Void StartClickTracking(EventBase evt) { }
	// RVA: 0x693149c VA: 0x7598f4949c
	private Void SendClickEvent(EventBase evt) { }
	// RVA: 0x69319c8 VA: 0x7598f499c8
	private Void CancelClickTracking(EventBase evt) { }
	// RVA: 0x6931ac4 VA: 0x7598f49ac4
	public Void ProcessEvent(EventBase evt) { }
	// RVA: 0x6931884 VA: 0x7598f49884
	private static Boolean ContainsPointer(VisualElement element, Vector2 position) { }
	// RVA: 0x6931fe0 VA: 0x7598f49fe0
	internal Void Cleanup(List`1 elements) { }
	// RVA: 0x6932164 VA: 0x7598f4a164
	private static Void .cctor() { }
}
```