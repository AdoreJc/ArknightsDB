# StyleMatchingContext

**Namespace:** `UnityEngine.UIElements`


## Fields

- `StyleVariableContext variableContext`

- `VisualElement currentElement`


## Properties

- `Int32 styleSheetCount`


## Methods

- `Int32 get_styleSheetCount()`

- `Void AddStyleSheet(StyleSheet)`

- `Void RemoveStyleSheetRange(Int32, Int32)`

- `StyleSheet GetStyleSheetAt(Int32)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class StyleMatchingContext
{
	private List`1 m_StyleSheetStack; // 0x10
	public StyleVariableContext variableContext; // 0x18
	public VisualElement currentElement; // 0x20
	public Action`2 processResult; // 0x28

	public Int32 styleSheetCount { get; }

	// RVA: 0x6999314 VA: 0x7598fb1314
	public Int32 get_styleSheetCount() { }
	// RVA: 0x699935c VA: 0x7598fb135c
	public Void .ctor(Action`2 processResult) { }
	// RVA: 0x699944c VA: 0x7598fb144c
	public Void AddStyleSheet(StyleSheet sheet) { }
	// RVA: 0x6999550 VA: 0x7598fb1550
	public Void RemoveStyleSheetRange(Int32 index, Int32 count) { }
	// RVA: 0x69995b8 VA: 0x7598fb15b8
	public StyleSheet GetStyleSheetAt(Int32 index) { }
}
```