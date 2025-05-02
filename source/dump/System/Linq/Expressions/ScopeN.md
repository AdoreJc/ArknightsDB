# ScopeN

**Namespace:** `System.Linq.Expressions`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
internal class ScopeN : ScopeExpression
{
	private IReadOnlyList`1 _body; // 0x18

	protected IReadOnlyList`1 Body { get; }
	internal override Int32 ExpressionCount { get; }

	// RVA: 0x623abf0 VA: 0x7598852bf0
	internal Void .ctor(IReadOnlyList`1 variables, IReadOnlyList`1 body) { }
	// RVA: 0x6242774 VA: 0x759885a774
	protected IReadOnlyList`1 get_Body() { }
	// RVA: 0x624277c VA: 0x759885a77c
	internal override Expression GetExpression(Int32 index) { }
	// RVA: 0x6242824 VA: 0x759885a824
	internal override Int32 get_ExpressionCount() { }
	// RVA: 0x62428c4 VA: 0x759885a8c4
	internal override BlockExpression Rewrite(ReadOnlyCollection`1 variables, Expression[] args) { }
}
```