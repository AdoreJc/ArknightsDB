# UIElementsUtility

**Namespace:** `UnityEngine.UIElements`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class UIElementsUtility : IUIElementsUtility
{
	private static Stack`1 s_ContainerStack; // 0x0
	private static Dictionary`2 s_UIElementsCache; // 0x8
	private static Event s_EventInstance; // 0x10
	internal static Color editorPlayModeTintColor; // 0x18
	internal static Single singleLineHeight; // 0x28
	private static UIElementsUtility s_Instance; // 0x30
	internal static List`1 s_PanelsIterationList; // 0x38
	internal static readonly String s_RepaintProfilerMarkerName; // 0x40
	internal static readonly String s_EventProfilerMarkerName; // 0x48
	private static readonly ProfilerMarker s_RepaintProfilerMarker; // 0x50
	private static readonly ProfilerMarker s_EventProfilerMarker; // 0x58
	internal static Char[] s_Modifiers; // 0x60


	// RVA: 0x6991e28 VA: 0x7598fa9e28
	private Void .ctor() { }
	// RVA: 0x6991e88 VA: 0x7598fa9e88
	private Boolean UnityEngine.UIElements.IUIElementsUtility.MakeCurrentIMGUIContainerDirty() { }
	// RVA: 0x6991f54 VA: 0x7598fa9f54
	private Boolean UnityEngine.UIElements.IUIElementsUtility.TakeCapture() { }
	// RVA: 0x69920c4 VA: 0x7598faa0c4
	private Boolean UnityEngine.UIElements.IUIElementsUtility.ReleaseCapture() { }
	// RVA: 0x69920cc VA: 0x7598faa0cc
	private Boolean UnityEngine.UIElements.IUIElementsUtility.ProcessEvent(Int32 instanceID, IntPtr nativeEventPtr, ref Boolean eventHandled) { }
	// RVA: 0x6992934 VA: 0x7598faa934
	private Boolean UnityEngine.UIElements.IUIElementsUtility.CleanupRoots() { }
	// RVA: 0x69929c8 VA: 0x7598faa9c8
	private Boolean UnityEngine.UIElements.IUIElementsUtility.EndContainerGUIFromException(Exception exception) { }
	// RVA: 0x698ecac VA: 0x7598fa6cac
	public static Void RegisterCachedPanel(Int32 instanceID, Panel panel) { }
	// RVA: 0x698eddc VA: 0x7598fa6ddc
	public static Void RemoveCachedPanel(Int32 instanceID) { }
	// RVA: 0x698e8f8 VA: 0x7598fa68f8
	public static Boolean TryGetPanel(Int32 instanceID, out Panel panel) { }
	// RVA: 0x6992a88 VA: 0x7598faaa88
	internal static Void BeginContainerGUI(LayoutCache cache, Event evt, IMGUIContainer container) { }
	// RVA: 0x6992c58 VA: 0x7598faac58
	internal static Void EndContainerGUI(Event evt, Rect layoutSize) { }
	// RVA: 0x6992e7c VA: 0x7598faae7c
	internal static EventBase CreateEvent(Event systemEvent) { }
	// RVA: 0x698e4c0 VA: 0x7598fa64c0
	internal static EventBase CreateEvent(Event systemEvent, EventType eventType) { }
	// RVA: 0x699220c VA: 0x7598faa20c
	private static Boolean DoDispatch(BaseVisualElementPanel panel) { }
	// RVA: 0x698ee5c VA: 0x7598fa6e5c
	internal static Void GetAllPanels(List`1 panels, ContextType contextType) { }
	// RVA: 0x6992ef0 VA: 0x7598faaef0
	internal static Enumerator GetPanelsIterator() { }
	// RVA: 0x6992f98 VA: 0x7598faaf98
	internal static Single PixelsPerUnitScaleForElement(VisualElement ve, Sprite sprite) { }
	// RVA: 0x6993040 VA: 0x7598fab040
	private static Void .cctor() { }
}
```