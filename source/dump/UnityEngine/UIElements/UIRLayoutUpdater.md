# UIRLayoutUpdater

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Void UpdateSubTree(VisualElement, Int32, Boolean)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class UIRLayoutUpdater : BaseVisualTreeUpdater
{
	private static readonly String s_Description; // 0x0
	private static readonly ProfilerMarker s_ProfilerMarker; // 0x8

	public override ProfilerMarker profilerMarker { get; }

	// RVA: 0x6a06194 VA: 0x759901e194
	public override ProfilerMarker get_profilerMarker() { }
	// RVA: 0x6a061ec VA: 0x759901e1ec
	public override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x6a06234 VA: 0x759901e234
	public override Void Update() { }
	// RVA: 0x6a06520 VA: 0x759901e520
	private Void UpdateSubTree(VisualElement ve, Int32 currentLayoutPass, Boolean isDisplayed) { }
	// RVA: 0x6a06d30 VA: 0x759901ed30
	public Void .ctor() { }
	// RVA: 0x6a06d38 VA: 0x759901ed38
	private static Void .cctor() { }
}
```