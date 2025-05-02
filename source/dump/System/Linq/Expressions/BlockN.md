# BlockN

**Namespace:** `System.Linq.Expressions`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
internal class BlockN : BlockExpression
{
	private IReadOnlyList`1 _expressions; // 0x10

	internal override Int32 ExpressionCount { get; }

	// RVA: 0x623ae20 VA: 0x7598852e20
	internal Void .ctor(IReadOnlyList`1 expressions) { }
	// RVA: 0x6242314 VA: 0x759885a314
	internal override Expression GetExpression(Int32 index) { }
	// RVA: 0x62423bc VA: 0x759885a3bc
	internal override Int32 get_ExpressionCount() { }
	// RVA: 0x624245c VA: 0x759885a45c
	internal override BlockExpression Rewrite(ReadOnlyCollection`1 variables, Expression[] args) { }
}
```