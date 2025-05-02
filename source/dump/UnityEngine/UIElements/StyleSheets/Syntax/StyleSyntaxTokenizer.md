# StyleSyntaxTokenizer

**Namespace:** `UnityEngine.UIElements.StyleSheets.Syntax`


## Fields

- `Int32 m_CurrentTokenIndex`


## Properties

- `StyleSyntaxToken current`


## Methods

- `StyleSyntaxToken get_current()`

- `StyleSyntaxToken MoveNext()`

- `StyleSyntaxToken PeekNext()`

- `Void Tokenize(String)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.StyleSheets.Syntax
internal class StyleSyntaxTokenizer
{
	private List`1 m_Tokens; // 0x10
	private Int32 m_CurrentTokenIndex; // 0x18

	public StyleSyntaxToken current { get; }

	// RVA: 0x69867cc VA: 0x7598f9e7cc
	public StyleSyntaxToken get_current() { }
	// RVA: 0x6987470 VA: 0x7598f9f470
	public StyleSyntaxToken MoveNext() { }
	// RVA: 0x6987700 VA: 0x7598f9f700
	public StyleSyntaxToken PeekNext() { }
	// RVA: 0x6985b58 VA: 0x7598f9db58
	public Void Tokenize(String syntax) { }
	// RVA: 0x6987fe4 VA: 0x7598f9ffe4
	private static Boolean IsNextCharacter(String s, Int32 index, Char c) { }
	// RVA: 0x69880c0 VA: 0x7598fa00c0
	private static Boolean IsNextLetterOrDash(String s, Int32 index) { }
	// RVA: 0x6988028 VA: 0x7598fa0028
	private static Boolean IsNextNumber(String s, Int32 index) { }
	// RVA: 0x6987fa8 VA: 0x7598f9ffa8
	private static Int32 GlobCharacter(String s, Int32 index, Char c) { }
	// RVA: 0x6985ac8 VA: 0x7598f9dac8
	public Void .ctor() { }
}
```