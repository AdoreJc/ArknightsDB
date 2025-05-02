# InvocationExpression

**Namespace:** `System.Linq.Expressions`


## Properties

- `Expression Expression`


## Methods

- `Expression get_Expression()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
public class InvocationExpression : Expression, IArgumentProvider
{
	private readonly Type <Type>k__BackingField; // 0x10
	private readonly Expression <Expression>k__BackingField; // 0x18

	public sealed override Type Type { get; }
	public sealed override ExpressionType NodeType { get; }
	public Expression Expression { get; }
	public virtual Int32 ArgumentCount { get; }

	// RVA: 0x6246fc4 VA: 0x759885efc4
	internal Void .ctor(Expression expression, Type returnType) { }
	// RVA: 0x624704c VA: 0x759885f04c
	public sealed override Type get_Type() { }
	// RVA: 0x6247054 VA: 0x759885f054
	public sealed override ExpressionType get_NodeType() { }
	// RVA: 0x624705c VA: 0x759885f05c
	public Expression get_Expression() { }
	// RVA: 0x6247064 VA: 0x759885f064
	public virtual Expression GetArgument(Int32 index) { }
	// RVA: 0x62470fc VA: 0x759885f0fc
	public virtual Int32 get_ArgumentCount() { }
	// RVA: 0x6247120 VA: 0x759885f120
	protected internal override Expression Accept(ExpressionVisitor visitor) { }
	// RVA: 0x6247148 VA: 0x759885f148
	internal virtual InvocationExpression Rewrite(Expression lambda, Expression[] arguments) { }
}
```