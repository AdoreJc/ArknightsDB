# VisualTreeBindingsUpdater

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int64 m_LastUpdateTime`


## Methods

- `IBinding GetBindingObjectFromElement(VisualElement)`

- `Void StartTracking(VisualElement)`

- `Void StopTracking(VisualElement)`

- `Void StartTrackingRecursive(VisualElement)`

- `Void StopTrackingRecursive(VisualElement)`

- `Void PerformTrackingOperations()`

- `Void UpdateBindings()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualTreeBindingsUpdater : BaseVisualTreeHierarchyTrackerUpdater
{
	private static readonly PropertyName s_BindingRequestObjectVEPropertyName; // 0x0
	private static readonly PropertyName s_AdditionalBindingObjectVEPropertyName; // 0x4
	private static readonly String s_Description; // 0x8
	private static readonly ProfilerMarker s_ProfilerMarker; // 0x10
	private static readonly ProfilerMarker s_ProfilerBindingRequestsMarker; // 0x18
	private static ProfilerMarker s_MarkerUpdate; // 0x20
	private static ProfilerMarker s_MarkerPoll; // 0x28
	private static Boolean <disableBindingsThrottling>k__BackingField; // 0x30
	private readonly HashSet`1 m_ElementsWithBindings; // 0x38
	private readonly HashSet`1 m_ElementsToAdd; // 0x40
	private readonly HashSet`1 m_ElementsToRemove; // 0x48
	private Int64 m_LastUpdateTime; // 0x50
	private HashSet`1 m_ElementsToBind; // 0x58
	private Dictionary`2 <temporaryObjectCache>k__BackingField; // 0x60
	private List`1 updatedBindings; // 0x68

	public override ProfilerMarker profilerMarker { get; }
	public Dictionary`2 temporaryObjectCache { get; }

	// RVA: 0x699be9c VA: 0x7598fb3e9c
	public override ProfilerMarker get_profilerMarker() { }
	// RVA: 0x699bef4 VA: 0x7598fb3ef4
	private IBinding GetBindingObjectFromElement(VisualElement ve) { }
	// RVA: 0x699c0b4 VA: 0x7598fb40b4
	private Void StartTracking(VisualElement ve) { }
	// RVA: 0x699c134 VA: 0x7598fb4134
	private Void StopTracking(VisualElement ve) { }
	// RVA: 0x699c1b4 VA: 0x7598fb41b4
	public Dictionary`2 get_temporaryObjectCache() { }
	// RVA: 0x699c02c VA: 0x7598fb402c
	public static IBinding GetAdditionalBinding(VisualElement ve) { }
	// RVA: 0x699c1bc VA: 0x7598fb41bc
	private Void StartTrackingRecursive(VisualElement ve) { }
	// RVA: 0x699c2d4 VA: 0x7598fb42d4
	private Void StopTrackingRecursive(VisualElement ve) { }
	// RVA: 0x699c3e0 VA: 0x7598fb43e0
	public override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x699c4d4 VA: 0x7598fb44d4
	protected override Void OnHierarchyChange(VisualElement ve, HierarchyChangeType type) { }
	// RVA: 0x699c4ec VA: 0x7598fb44ec
	private static Int64 CurrentTime() { }
	// RVA: 0x699c53c VA: 0x7598fb453c
	public Void PerformTrackingOperations() { }
	// RVA: 0x699c7c0 VA: 0x7598fb47c0
	public override Void Update() { }
	// RVA: 0x699cdbc VA: 0x7598fb4dbc
	private Void UpdateBindings() { }
	// RVA: 0x699d34c VA: 0x7598fb534c
	public Void .ctor() { }
	// RVA: 0x699d500 VA: 0x7598fb5500
	private static Void .cctor() { }
}
```