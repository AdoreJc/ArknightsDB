# Expression

**Namespace:** `System.Linq.Expressions`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
public class Expression`1 : LambdaExpression
{

	internal sealed override Type TypeCore { get; }
	internal override Type PublicType { get; }

	// RVA: 0x VA: 0x0
	internal Void .ctor(Expression body) { }
	// RVA: 0x VA: 0x0
	internal sealed override Type get_TypeCore() { }
	// RVA: 0x VA: 0x0
	internal override Type get_PublicType() { }
	// RVA: 0x VA: 0x0
	internal virtual Expression`1 Rewrite(Expression body, ParameterExpression[] parameters) { }
	// RVA: 0x VA: 0x0
	protected internal override Expression Accept(ExpressionVisitor visitor) { }
}
```