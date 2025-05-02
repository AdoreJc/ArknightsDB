# VisualElementAnimationSystem

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Boolean m_HasNewAnimations`

- `Boolean m_IterationListDirty`

- `Int64 lastUpdate`


## Methods

- `Void UnregisterAnimation(IValueAnimationUpdate)`

- `Void UnregisterAnimations(List`1)`

- `Void RegisterAnimation(IValueAnimationUpdate)`

- `Void RegisterAnimations(List`1)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualElementAnimationSystem : BaseVisualTreeUpdater
{
	private HashSet`1 m_Animations; // 0x20
	private List`1 m_IterationList; // 0x28
	private Boolean m_HasNewAnimations; // 0x30
	private Boolean m_IterationListDirty; // 0x31
	private static readonly String s_Description; // 0x0
	private static readonly ProfilerMarker s_ProfilerMarker; // 0x8
	private static readonly String s_StylePropertyAnimationDescription; // 0x10
	private static readonly ProfilerMarker s_StylePropertyAnimationProfilerMarker; // 0x18
	private Int64 lastUpdate; // 0x38

	public override ProfilerMarker profilerMarker { get; }
	private static ProfilerMarker stylePropertyAnimationProfilerMarker { get; }

	// RVA: 0x6997388 VA: 0x7598faf388
	public override ProfilerMarker get_profilerMarker() { }
	// RVA: 0x69973e0 VA: 0x7598faf3e0
	private static ProfilerMarker get_stylePropertyAnimationProfilerMarker() { }
	// RVA: 0x6997438 VA: 0x7598faf438
	public Void UnregisterAnimation(IValueAnimationUpdate anim) { }
	// RVA: 0x699749c VA: 0x7598faf49c
	public Void UnregisterAnimations(List`1 anims) { }
	// RVA: 0x6997614 VA: 0x7598faf614
	public Void RegisterAnimation(IValueAnimationUpdate anim) { }
	// RVA: 0x6997678 VA: 0x7598faf678
	public Void RegisterAnimations(List`1 anims) { }
	// RVA: 0x69977f0 VA: 0x7598faf7f0
	public override Void Update() { }
	// RVA: 0x6997c70 VA: 0x7598fafc70
	public override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x6997c74 VA: 0x7598fafc74
	public Void .ctor() { }
	// RVA: 0x6997d58 VA: 0x7598fafd58
	private static Void .cctor() { }
}
```