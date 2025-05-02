# VisualTreeViewDataUpdater

**Namespace:** `UnityEngine.UIElements`


## Fields

- `UInt32 m_Version`

- `UInt32 m_LastVersion`


## Methods

- `Void ValidateViewDataOnSubTree(VisualElement, Boolean)`

- `Void PropagateToParents(VisualElement)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualTreeViewDataUpdater : BaseVisualTreeUpdater
{
	private HashSet`1 m_UpdateList; // 0x20
	private HashSet`1 m_ParentList; // 0x28
	private UInt32 m_Version; // 0x30
	private UInt32 m_LastVersion; // 0x34
	private static readonly String s_Description; // 0x0
	private static readonly ProfilerMarker s_ProfilerMarker; // 0x8

	public override ProfilerMarker profilerMarker { get; }

	// RVA: 0x699b908 VA: 0x7598fb3908
	public override ProfilerMarker get_profilerMarker() { }
	// RVA: 0x699b960 VA: 0x7598fb3960
	public override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x699ba98 VA: 0x7598fb3a98
	public override Void Update() { }
	// RVA: 0x699bbf4 VA: 0x7598fb3bf4
	private Void ValidateViewDataOnSubTree(VisualElement ve, Boolean enablePersistence) { }
	// RVA: 0x699b9f0 VA: 0x7598fb39f0
	private Void PropagateToParents(VisualElement ve) { }
	// RVA: 0x699bd44 VA: 0x7598fb3d44
	public Void .ctor() { }
	// RVA: 0x699be00 VA: 0x7598fb3e00
	private static Void .cctor() { }
}
```