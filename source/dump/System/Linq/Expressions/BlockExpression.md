# BlockExpression

**Namespace:** `System.Linq.Expressions`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
public class BlockExpression : Expression
{

	public ReadOnlyCollection`1 Variables { get; }
	public sealed override ExpressionType NodeType { get; }
	public override Type Type { get; }
	internal virtual Int32 ExpressionCount { get; }

	// RVA: 0x6241bbc VA: 0x7598859bbc
	public ReadOnlyCollection`1 get_Variables() { }
	// RVA: 0x6241bc8 VA: 0x7598859bc8
	internal Void .ctor() { }
	// RVA: 0x6241c20 VA: 0x7598859c20
	protected internal override Expression Accept(ExpressionVisitor visitor) { }
	// RVA: 0x6241c48 VA: 0x7598859c48
	public sealed override ExpressionType get_NodeType() { }
	// RVA: 0x6241c50 VA: 0x7598859c50
	public override Type get_Type() { }
	// RVA: 0x6241c90 VA: 0x7598859c90
	internal virtual Expression GetExpression(Int32 index) { }
	// RVA: 0x6241cb8 VA: 0x7598859cb8
	internal virtual Int32 get_ExpressionCount() { }
	// RVA: 0x6241ce0 VA: 0x7598859ce0
	internal virtual ReadOnlyCollection`1 GetOrMakeVariables() { }
	// RVA: 0x6241d38 VA: 0x7598859d38
	internal virtual BlockExpression Rewrite(ReadOnlyCollection`1 variables, Expression[] args) { }
}
```