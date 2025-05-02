# StyleSyntaxParser

**Namespace:** `UnityEngine.UIElements.StyleSheets.Syntax`


## Methods

- `Expression Parse(String)`

- `Expression ParseExpression(StyleSyntaxTokenizer)`

- `Void ProcessCombinatorStack()`

- `Expression ParseTerm(StyleSyntaxTokenizer)`

- `ExpressionCombinator ParseCombinatorType(StyleSyntaxTokenizer)`

- `Expression ParseGroup(StyleSyntaxTokenizer)`

- `Expression ParseDataType(StyleSyntaxTokenizer)`

- `Expression ParseNonTerminalValue(String)`

- `Expression ParseProperty(StyleSyntaxTokenizer)`

- `Void ParseMultiplier(StyleSyntaxTokenizer, ref)`

- `Void ParseRanges(StyleSyntaxTokenizer, out, out)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.StyleSheets.Syntax
internal class StyleSyntaxParser
{
	private List`1 m_ProcessExpressionList; // 0x10
	private Stack`1 m_ExpressionStack; // 0x18
	private Stack`1 m_CombinatorStack; // 0x20
	private Dictionary`2 m_ParsedExpressionCache; // 0x28


	// RVA: 0x6985930 VA: 0x7598f9d930
	public Expression Parse(String syntax) { }
	// RVA: 0x698654c VA: 0x7598f9e54c
	private Expression ParseExpression(StyleSyntaxTokenizer tokenizer) { }
	// RVA: 0x6986d84 VA: 0x7598f9ed84
	private Void ProcessCombinatorStack() { }
	// RVA: 0x6986894 VA: 0x7598f9e894
	private Expression ParseTerm(StyleSyntaxTokenizer tokenizer) { }
	// RVA: 0x6986c2c VA: 0x7598f9ec2c
	private ExpressionCombinator ParseCombinatorType(StyleSyntaxTokenizer tokenizer) { }
	// RVA: 0x69869fc VA: 0x7598f9e9fc
	private Expression ParseGroup(StyleSyntaxTokenizer tokenizer) { }
	// RVA: 0x698709c VA: 0x7598f9f09c
	private Expression ParseDataType(StyleSyntaxTokenizer tokenizer) { }
	// RVA: 0x6987820 VA: 0x7598f9f820
	private Expression ParseNonTerminalValue(String syntax) { }
	// RVA: 0x698797c VA: 0x7598f9f97c
	private Expression ParseProperty(StyleSyntaxTokenizer tokenizer) { }
	// RVA: 0x6987584 VA: 0x7598f9f584
	private Void ParseMultiplier(StyleSyntaxTokenizer tokenizer, ref ExpressionMultiplier multiplier) { }
	// RVA: 0x6987c94 VA: 0x7598f9fc94
	private Void ParseRanges(StyleSyntaxTokenizer tokenizer, out Int32 min, out Int32 max) { }
	// RVA: 0x69877e0 VA: 0x7598f9f7e0
	private static Void EatSpace(StyleSyntaxTokenizer tokenizer) { }
	// RVA: 0x698707c VA: 0x7598f9f07c
	private static Boolean IsExpressionEnd(StyleSyntaxToken token) { }
	// RVA: 0x69877cc VA: 0x7598f9f7cc
	private static Boolean IsCombinator(StyleSyntaxToken token) { }
	// RVA: 0x6987c70 VA: 0x7598f9fc70
	private static Boolean IsMultiplier(StyleSyntaxToken token) { }
	// RVA: 0x6987db8 VA: 0x7598f9fdb8
	public Void .ctor() { }
}
```