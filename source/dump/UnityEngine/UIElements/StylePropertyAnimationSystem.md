# StylePropertyAnimationSystem

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int64 m_CurrentTimeMs`

- `ValuesFloat m_Floats`

- `ValuesInt m_Ints`

- `ValuesLength m_Lengths`

- `ValuesColor m_Colors`

- `ValuesBackground m_Backgrounds`

- `ValuesFontDefinition m_FontDefinitions`

- `ValuesFont m_Fonts`

- `ValuesTextShadow m_TextShadows`

- `ValuesScale m_Scale`

- `ValuesRotate m_Rotate`

- `ValuesTranslate m_Translate`

- `ValuesTransformOrigin m_TransformOrigin`


## Methods

- `T GetOrCreate(ref)`

- `Boolean StartTransition(VisualElement, StylePropertyId, T, T, Int32, Int32, Func`2, Values`1)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Single, Single, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Int32, Int32, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Length, Length, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Color, Color, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Background, Background, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, FontDefinition, FontDefinition, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Font, Font, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, TextShadow, TextShadow, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Scale, Scale, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Rotate, Rotate, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, Translate, Translate, Int32, Int32, Func`2)`

- `Boolean StartTransition(VisualElement, StylePropertyId, TransformOrigin, TransformOrigin, Int32, Int32, Func`2)`

- `Void CancelAllAnimations()`

- `Void CancelAllAnimations(VisualElement)`

- `Void CancelAnimation(VisualElement, StylePropertyId)`

- `Void UpdateAnimation(VisualElement, StylePropertyId)`

- `Void GetAllAnimations(VisualElement, List`1)`

- `Void UpdateTracking(Values`1)`

- `Int64 CurrentTimeMs()`

- `Void Update()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class StylePropertyAnimationSystem : IStylePropertyAnimationSystem
{
	private Int64 m_CurrentTimeMs; // 0x10
	private ValuesFloat m_Floats; // 0x18
	private ValuesInt m_Ints; // 0x20
	private ValuesLength m_Lengths; // 0x28
	private ValuesColor m_Colors; // 0x30
	private ValuesBackground m_Backgrounds; // 0x38
	private ValuesFontDefinition m_FontDefinitions; // 0x40
	private ValuesFont m_Fonts; // 0x48
	private ValuesTextShadow m_TextShadows; // 0x50
	private ValuesScale m_Scale; // 0x58
	private ValuesRotate m_Rotate; // 0x60
	private ValuesTranslate m_Translate; // 0x68
	private ValuesTransformOrigin m_TransformOrigin; // 0x70
	private readonly List`1 m_AllValues; // 0x78
	private readonly Dictionary`2 m_PropertyToValues; // 0x80


	// RVA: 0x6955f64 VA: 0x7598f6df64
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private T GetOrCreate(ref T values) { }
	// RVA: 0x VA: 0x0
	private Boolean StartTransition(VisualElement owner, StylePropertyId prop, T startValue, T endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve, Values`1 values) { }
	// RVA: 0x6956074 VA: 0x7598f6e074
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Single startValue, Single endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x695613c VA: 0x7598f6e13c
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Int32 startValue, Int32 endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6956214 VA: 0x7598f6e214
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Length startValue, Length endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69562ec VA: 0x7598f6e2ec
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Color startValue, Color endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69563fc VA: 0x7598f6e3fc
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Background startValue, Background endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69564f4 VA: 0x7598f6e4f4
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, FontDefinition startValue, FontDefinition endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69565e4 VA: 0x7598f6e5e4
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Font startValue, Font endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69566bc VA: 0x7598f6e6bc
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, TextShadow startValue, TextShadow endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69567d4 VA: 0x7598f6e7d4
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Scale startValue, Scale endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69568c4 VA: 0x7598f6e8c4
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Rotate startValue, Rotate endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69569dc VA: 0x7598f6e9dc
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, Translate startValue, Translate endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6956af4 VA: 0x7598f6eaf4
	public Boolean StartTransition(VisualElement owner, StylePropertyId prop, TransformOrigin startValue, TransformOrigin endValue, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6956c0c VA: 0x7598f6ec0c
	public Void CancelAllAnimations() { }
	// RVA: 0x6956d5c VA: 0x7598f6ed5c
	public Void CancelAllAnimations(VisualElement owner) { }
	// RVA: 0x6956fe8 VA: 0x7598f6efe8
	public Void CancelAnimation(VisualElement owner, StylePropertyId id) { }
	// RVA: 0x6957078 VA: 0x7598f6f078
	public Void UpdateAnimation(VisualElement owner, StylePropertyId id) { }
	// RVA: 0x6957108 VA: 0x7598f6f108
	public Void GetAllAnimations(VisualElement owner, List`1 propertyIds) { }
	// RVA: 0x VA: 0x0
	private Void UpdateTracking(Values`1 values) { }
	// RVA: 0x6957260 VA: 0x7598f6f260
	private Int64 CurrentTimeMs() { }
	// RVA: 0x6957268 VA: 0x7598f6f268
	public Void Update() { }
}
```