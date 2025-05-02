# MemberExpression

**Namespace:** `System.Linq.Expressions`


## Properties

- `MemberInfo Member`

- `Expression Expression`


## Methods

- `MemberInfo get_Member()`

- `Expression get_Expression()`

- `MemberExpression Update(Expression)`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
public class MemberExpression : Expression
{
	private readonly Expression <Expression>k__BackingField; // 0x10

	public MemberInfo Member { get; }
	public Expression Expression { get; }
	public sealed override ExpressionType NodeType { get; }

	// RVA: 0x624741c VA: 0x759885f41c
	public MemberInfo get_Member() { }
	// RVA: 0x6247428 VA: 0x759885f428
	public Expression get_Expression() { }
	// RVA: 0x6247430 VA: 0x759885f430
	internal Void .ctor(Expression expression) { }
	// RVA: 0x62474a4 VA: 0x759885f4a4
	internal static PropertyExpression Make(Expression expression, PropertyInfo property) { }
	// RVA: 0x624754c VA: 0x759885f54c
	internal static FieldExpression Make(Expression expression, FieldInfo field) { }
	// RVA: 0x62475f4 VA: 0x759885f5f4
	public sealed override ExpressionType get_NodeType() { }
	// RVA: 0x62475fc VA: 0x759885f5fc
	internal virtual MemberInfo GetMember() { }
	// RVA: 0x6247620 VA: 0x759885f620
	protected internal override Expression Accept(ExpressionVisitor visitor) { }
	// RVA: 0x6246824 VA: 0x759885e824
	public MemberExpression Update(Expression expression) { }
}
```