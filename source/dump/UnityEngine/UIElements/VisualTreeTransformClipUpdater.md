# VisualTreeTransformClipUpdater

**Namespace:** `UnityEngine.UIElements`


## Fields

- `UInt32 m_Version`

- `UInt32 m_LastVersion`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualTreeTransformClipUpdater : BaseVisualTreeUpdater
{
	private UInt32 m_Version; // 0x20
	private UInt32 m_LastVersion; // 0x24
	private static readonly String s_Description; // 0x0
	private static readonly ProfilerMarker s_ProfilerMarker; // 0x8

	public override ProfilerMarker profilerMarker { get; }

	// RVA: 0x699ab7c VA: 0x7598fb2b7c
	public override ProfilerMarker get_profilerMarker() { }
	// RVA: 0x699abd4 VA: 0x7598fb2bd4
	public override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x699accc VA: 0x7598fb2ccc
	private static Void DirtyHierarchy(VisualElement ve, Boolean mustDirtyWorldTransform, Boolean mustDirtyWorldClip) { }
	// RVA: 0x699ae20 VA: 0x7598fb2e20
	private static Void DirtyBoundingBoxHierarchy(VisualElement ve) { }
	// RVA: 0x699aec8 VA: 0x7598fb2ec8
	public override Void Update() { }
	// RVA: 0x699af24 VA: 0x7598fb2f24
	public Void .ctor() { }
	// RVA: 0x699af30 VA: 0x7598fb2f30
	private static Void .cctor() { }
}
```