# StyleVariableResolver

**Namespace:** `UnityEngine.UIElements`


## Fields

- `StylePropertyValueMatcher m_Matcher`

- `StyleProperty m_Property`

- `ResolveContext m_CurrentContext`

- `StyleVariableContext <variableContext>k__BackingField`


## Properties

- `StyleSheet currentSheet`

- `StyleVariableContext variableContext`


## Methods

- `StyleSheet get_currentSheet()`

- `StyleVariableContext get_variableContext()`

- `Void set_variableContext(StyleVariableContext)`

- `Void Init(StyleProperty, StyleSheet, StyleValueHandle[])`

- `Void PushContext(StyleSheet, StyleValueHandle[])`

- `Void PopContext()`

- `Void AddValue(StyleValueHandle)`

- `Boolean ResolveVarFunction(ref)`

- `Result ResolveVarFunction(ref, Int32, String)`

- `Boolean ValidateResolvedValues()`

- `Result ResolveVariable(String)`

- `Result ResolveFallback(ref)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class StyleVariableResolver
{
	internal const Int32 kMaxResolves; // 0x0
	private static StyleSyntaxParser s_SyntaxParser; // 0x0
	private StylePropertyValueMatcher m_Matcher; // 0x10
	private List`1 m_ResolvedValues; // 0x18
	private Stack`1 m_ResolvedVarStack; // 0x20
	private StyleProperty m_Property; // 0x28
	private Stack`1 m_ContextStack; // 0x30
	private ResolveContext m_CurrentContext; // 0x38
	private StyleVariableContext <variableContext>k__BackingField; // 0x48

	private StyleSheet currentSheet { get; }
	private StyleValueHandle[] currentHandles { get; }
	public List`1 resolvedValues { get; }
	public StyleVariableContext variableContext { get; set; }

	// RVA: 0x6a1b8a0 VA: 0x75990338a0
	private StyleSheet get_currentSheet() { }
	// RVA: 0x6a1b8a8 VA: 0x75990338a8
	private StyleValueHandle[] get_currentHandles() { }
	// RVA: 0x6a1b8b0 VA: 0x75990338b0
	public List`1 get_resolvedValues() { }
	// RVA: 0x6a1b8b8 VA: 0x75990338b8
	public StyleVariableContext get_variableContext() { }
	// RVA: 0x6a1b8c0 VA: 0x75990338c0
	public Void set_variableContext(StyleVariableContext value) { }
	// RVA: 0x6a1b8c8 VA: 0x75990338c8
	public Void Init(StyleProperty property, StyleSheet sheet, StyleValueHandle[] handles) { }
	// RVA: 0x6a1b984 VA: 0x7599033984
	private Void PushContext(StyleSheet sheet, StyleValueHandle[] handles) { }
	// RVA: 0x6a1ba30 VA: 0x7599033a30
	private Void PopContext() { }
	// RVA: 0x6a1bab8 VA: 0x7599033ab8
	public Void AddValue(StyleValueHandle handle) { }
	// RVA: 0x6a1bb8c VA: 0x7599033b8c
	public Boolean ResolveVarFunction(ref Int32 index) { }
	// RVA: 0x6a1bd10 VA: 0x7599033d10
	private Result ResolveVarFunction(ref Int32 index, Int32 argc, String varName) { }
	// RVA: 0x6a1c39c VA: 0x759903439c
	public Boolean ValidateResolvedValues() { }
	// RVA: 0x6a1be6c VA: 0x7599033e6c
	private Result ResolveVariable(String variableName) { }
	// RVA: 0x6a1c0f8 VA: 0x75990340f8
	private Result ResolveFallback(ref Int32 index) { }
	// RVA: 0x6a1bc58 VA: 0x7599033c58
	private static Void ParseVarFunction(StyleSheet sheet, StyleValueHandle[] handles, ref Int32 index, out Int32 argCount, out String variableName) { }
	// RVA: 0x6a1c50c VA: 0x759903450c
	public Void .ctor() { }
	// RVA: 0x6a1c670 VA: 0x7599034670
	private static Void .cctor() { }
}
```