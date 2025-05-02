# VisualTreeStyleUpdater

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Boolean m_IsApplyingStyles`

- `UInt32 m_Version`

- `UInt32 m_LastVersion`

- `VisualTreeStyleUpdaterTraversal m_StyleContextHierarchyTraversal`


## Methods

- `Void ApplyStyles()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualTreeStyleUpdater : BaseVisualTreeUpdater
{
	private HashSet`1 m_ApplyStyleUpdateList; // 0x20
	private HashSet`1 m_TransitionPropertyUpdateList; // 0x28
	private Boolean m_IsApplyingStyles; // 0x30
	private UInt32 m_Version; // 0x34
	private UInt32 m_LastVersion; // 0x38
	private VisualTreeStyleUpdaterTraversal m_StyleContextHierarchyTraversal; // 0x40
	private static readonly String s_Description; // 0x0
	private static readonly ProfilerMarker s_ProfilerMarker; // 0x8

	public override ProfilerMarker profilerMarker { get; }

	// RVA: 0x69985ec VA: 0x7598fb05ec
	public override ProfilerMarker get_profilerMarker() { }
	// RVA: 0x6998644 VA: 0x7598fb0644
	public override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x699878c VA: 0x7598fb078c
	public override Void Update() { }
	// RVA: 0x6998a98 VA: 0x7598fb0a98
	private Void ApplyStyles() { }
	// RVA: 0x6998f1c VA: 0x7598fb0f1c
	public Void .ctor() { }
	// RVA: 0x6999278 VA: 0x7598fb1278
	private static Void .cctor() { }
}
```