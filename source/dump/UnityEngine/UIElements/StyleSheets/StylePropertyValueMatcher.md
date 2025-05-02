# StylePropertyValueMatcher

**Namespace:** `UnityEngine.UIElements.StyleSheets`


## Properties

- `StylePropertyValue current`


## Methods

- `StylePropertyValue get_current()`

- `MatchResult Match(Expression, List`1)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.StyleSheets
internal class StylePropertyValueMatcher : BaseStyleMatcher
{
	private List`1 m_Values; // 0x20

	private StylePropertyValue current { get; }
	public override Int32 valueCount { get; }
	public override Boolean isCurrentVariable { get; }
	public override Boolean isCurrentComma { get; }

	// RVA: 0x6984e84 VA: 0x7598f9ce84
	private StylePropertyValue get_current() { }
	// RVA: 0x6984f08 VA: 0x7598f9cf08
	public override Int32 get_valueCount() { }
	// RVA: 0x6984f50 VA: 0x7598f9cf50
	public override Boolean get_isCurrentVariable() { }
	// RVA: 0x6984f58 VA: 0x7598f9cf58
	public override Boolean get_isCurrentComma() { }
	// RVA: 0x6985000 VA: 0x7598f9d000
	public MatchResult Match(Expression exp, List`1 values) { }
	// RVA: 0x6985190 VA: 0x7598f9d190
	protected override Boolean MatchKeyword(String keyword) { }
	// RVA: 0x6985244 VA: 0x7598f9d244
	protected override Boolean MatchNumber() { }
	// RVA: 0x6985278 VA: 0x7598f9d278
	protected override Boolean MatchInteger() { }
	// RVA: 0x69852ac VA: 0x7598f9d2ac
	protected override Boolean MatchLength() { }
	// RVA: 0x69853a0 VA: 0x7598f9d3a0
	protected override Boolean MatchPercentage() { }
	// RVA: 0x6985494 VA: 0x7598f9d494
	protected override Boolean MatchColor() { }
	// RVA: 0x698556c VA: 0x7598f9d56c
	protected override Boolean MatchResource() { }
	// RVA: 0x69855a0 VA: 0x7598f9d5a0
	protected override Boolean MatchUrl() { }
	// RVA: 0x69855e0 VA: 0x7598f9d5e0
	protected override Boolean MatchTime() { }
	// RVA: 0x6985640 VA: 0x7598f9d640
	protected override Boolean MatchCustomIdent() { }
	// RVA: 0x698571c VA: 0x7598f9d71c
	protected override Boolean MatchAngle() { }
	// RVA: 0x6985818 VA: 0x7598f9d818
	public Void .ctor() { }
}
```