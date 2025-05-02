# ParameterExpression

**Namespace:** `System.Linq.Expressions`


## Properties

- `String Name`

- `Boolean IsByRef`


## Methods

- `String get_Name()`

- `Boolean get_IsByRef()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
public class ParameterExpression : Expression
{
	private readonly String <Name>k__BackingField; // 0x10

	public override Type Type { get; }
	public sealed override ExpressionType NodeType { get; }
	public String Name { get; }
	public Boolean IsByRef { get; }

	// RVA: 0x62476a0 VA: 0x759885f6a0
	internal Void .ctor(String name) { }
	// RVA: 0x6247714 VA: 0x759885f714
	internal static ParameterExpression Make(Type type, String name, Boolean isByRef) { }
	// RVA: 0x6247e9c VA: 0x759885fe9c
	public override Type get_Type() { }
	// RVA: 0x6247f08 VA: 0x759885ff08
	public sealed override ExpressionType get_NodeType() { }
	// RVA: 0x6247f10 VA: 0x759885ff10
	public String get_Name() { }
	// RVA: 0x6247f18 VA: 0x759885ff18
	public Boolean get_IsByRef() { }
	// RVA: 0x6247f24 VA: 0x759885ff24
	internal virtual Boolean GetIsByRef() { }
	// RVA: 0x6247f2c VA: 0x759885ff2c
	protected internal override Expression Accept(ExpressionVisitor visitor) { }
}
```