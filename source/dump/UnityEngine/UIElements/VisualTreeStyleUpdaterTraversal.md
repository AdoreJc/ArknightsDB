# VisualTreeStyleUpdaterTraversal

**Namespace:** `UnityEngine.UIElements`


## Fields

- `StyleVariableContext m_ProcessVarContext`

- `Single <currentPixelsPerPoint>k__BackingField`

- `StyleMatchingContext m_StyleMatchingContext`

- `StylePropertyReader m_StylePropertyReader`


## Properties

- `Single currentPixelsPerPoint`


## Methods

- `Single get_currentPixelsPerPoint()`

- `Void set_currentPixelsPerPoint(Single)`

- `Void PrepareTraversal(Single)`

- `Void AddChangedElement(VisualElement, VersionChangeType)`

- `Void Clear()`

- `Void PropagateToChildren(VisualElement)`

- `Void PropagateToParents(VisualElement)`

- `Void ProcessTransitions(VisualElement, ref, ref)`

- `Void ForceUpdateTransitions(VisualElement)`

- `Boolean ShouldSkipElement(VisualElement)`

- `ComputedStyle ProcessMatchedRules(VisualElement, List`1)`

- `Void ProcessMatchedVariables(StyleSheet, StyleRule)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualTreeStyleUpdaterTraversal : HierarchyTraversal
{
	private StyleVariableContext m_ProcessVarContext; // 0x10
	private HashSet`1 m_UpdateList; // 0x18
	private HashSet`1 m_ParentList; // 0x20
	private List`1 m_TempMatchResults; // 0x28
	private Single <currentPixelsPerPoint>k__BackingField; // 0x30
	private StyleMatchingContext m_StyleMatchingContext; // 0x38
	private StylePropertyReader m_StylePropertyReader; // 0x40
	private readonly List`1 m_AnimatedProperties; // 0x48

	private Single currentPixelsPerPoint { get; set; }

	// RVA: 0x6999610 VA: 0x7598fb1610
	private Single get_currentPixelsPerPoint() { }
	// RVA: 0x6999618 VA: 0x7598fb1618
	private Void set_currentPixelsPerPoint(Single value) { }
	// RVA: 0x6998f14 VA: 0x7598fb0f14
	public Void PrepareTraversal(Single pixelsPerPoint) { }
	// RVA: 0x699870c VA: 0x7598fb070c
	public Void AddChangedElement(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x6998b84 VA: 0x7598fb0b84
	public Void Clear() { }
	// RVA: 0x6999620 VA: 0x7598fb1620
	private Void PropagateToChildren(VisualElement ve) { }
	// RVA: 0x69996f4 VA: 0x7598fb16f4
	private Void PropagateToParents(VisualElement ve) { }
	// RVA: 0x699979c VA: 0x7598fb179c
	private static Void OnProcessMatchResult(VisualElement current, MatchResultInfo info) { }
	// RVA: 0x69997cc VA: 0x7598fb17cc
	public override Void TraverseRecursive(VisualElement element, Int32 depth) { }
	// RVA: 0x699a64c VA: 0x7598fb264c
	private Void ProcessTransitions(VisualElement element, ref ComputedStyle oldStyle, ref ComputedStyle newStyle) { }
	// RVA: 0x699a730 VA: 0x7598fb2730
	private Void ForceUpdateTransitions(VisualElement element) { }
	// RVA: 0x6998c28 VA: 0x7598fb0c28
	internal Void CancelAnimationsWithNoTransitionProperty(VisualElement element, ref ComputedStyle newStyle) { }
	// RVA: 0x6999df8 VA: 0x7598fb1df8
	protected Boolean ShouldSkipElement(VisualElement element) { }
	// RVA: 0x6999e7c VA: 0x7598fb1e7c
	private ComputedStyle ProcessMatchedRules(VisualElement element, List`1 matchingSelectors) { }
	// RVA: 0x699a9c4 VA: 0x7598fb29c4
	private Void ProcessMatchedVariables(StyleSheet sheet, StyleRule rule) { }
	// RVA: 0x6999018 VA: 0x7598fb1018
	public Void .ctor() { }
}
```