# LayoutRebuilder

**Namespace:** `UnityEngine.UI`


## Fields

- `RectTransform m_ToRebuild`

- `Int32 m_CachedHashFromTransform`


## Properties

- `Transform transform`


## Methods

- `Void Initialize(RectTransform)`

- `Void Clear()`

- `Transform get_transform()`

- `Boolean IsDestroyed()`

- `Void Rebuild(CanvasUpdate)`

- `Void PerformLayoutControl(RectTransform, UnityAction`1)`

- `Void PerformLayoutCalculation(RectTransform, UnityAction`1)`

- `Void LayoutComplete()`

- `Void GraphicUpdateComplete()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class LayoutRebuilder : ICanvasElement
{
	private RectTransform m_ToRebuild; // 0x10
	private Int32 m_CachedHashFromTransform; // 0x18
	private static ObjectPool`1 s_Rebuilders; // 0x0

	public Transform transform { get; }

	// RVA: 0x6a5636c VA: 0x759906e36c
	private Void Initialize(RectTransform controller) { }
	// RVA: 0x6a563ac VA: 0x759906e3ac
	private Void Clear() { }
	// RVA: 0x6a563d0 VA: 0x759906e3d0
	private static Void .cctor() { }
	// RVA: 0x6a565b8 VA: 0x759906e5b8
	private static Void ReapplyDrivenProperties(RectTransform driven) { }
	// RVA: 0x6a5660c VA: 0x759906e60c
	public Transform get_transform() { }
	// RVA: 0x6a56614 VA: 0x759906e614
	public Boolean IsDestroyed() { }
	// RVA: 0x6a56674 VA: 0x759906e674
	private static Void StripDisabledBehavioursFromList(List`1 components) { }
	// RVA: 0x6a56778 VA: 0x759906e778
	public static Void ForceRebuildLayoutImmediate(RectTransform layoutRoot) { }
	// RVA: 0x6a56840 VA: 0x759906e840
	public Void Rebuild(CanvasUpdate executing) { }
	// RVA: 0x6a56e14 VA: 0x759906ee14
	private Void PerformLayoutControl(RectTransform rect, UnityAction`1 action) { }
	// RVA: 0x6a56b14 VA: 0x759906eb14
	private Void PerformLayoutCalculation(RectTransform rect, UnityAction`1 action) { }
	// RVA: 0x6a51a2c VA: 0x7599069a2c
	public static Void MarkLayoutForRebuild(RectTransform rect) { }
	// RVA: 0x6a571e4 VA: 0x759906f1e4
	private static Boolean ValidController(RectTransform layoutRoot, List`1 comps) { }
	// RVA: 0x6a573d8 VA: 0x759906f3d8
	private static Void MarkLayoutRootForRebuild(RectTransform controller) { }
	// RVA: 0x6a57528 VA: 0x759906f528
	public Void LayoutComplete() { }
	// RVA: 0x6a575a8 VA: 0x759906f5a8
	public Void GraphicUpdateComplete() { }
	// RVA: 0x6a575ac VA: 0x759906f5ac
	public override Int32 GetHashCode() { }
	// RVA: 0x6a575b4 VA: 0x759906f5b4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6a57604 VA: 0x759906f604
	public override String ToString() { }
	// RVA: 0x6a57670 VA: 0x759906f670
	public Void .ctor() { }
}
```