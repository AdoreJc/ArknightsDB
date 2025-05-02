# SimpleBinaryExpression

**Namespace:** `System.Linq.Expressions`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
internal class SimpleBinaryExpression : BinaryExpression
{
	private readonly ExpressionType <NodeType>k__BackingField; // 0x20
	private readonly Type <Type>k__BackingField; // 0x28

	public sealed override ExpressionType NodeType { get; }
	public sealed override Type Type { get; }

	// RVA: 0x623046c VA: 0x759884846c
	internal Void .ctor(ExpressionType nodeType, Expression left, Expression right, Type type) { }
	// RVA: 0x62304a8 VA: 0x75988484a8
	public sealed override ExpressionType get_NodeType() { }
	// RVA: 0x62304b0 VA: 0x75988484b0
	public sealed override Type get_Type() { }
}
```