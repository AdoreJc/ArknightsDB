# BinaryExpression

**Namespace:** `System.Linq.Expressions`


## Properties

- `Expression Right`

- `Expression Left`

- `MethodInfo Method`

- `LambdaExpression Conversion`

- `Boolean IsLifted`

- `Boolean IsLiftedToNull`


## Methods

- `Expression get_Right()`

- `Expression get_Left()`

- `MethodInfo get_Method()`

- `BinaryExpression Update(Expression, LambdaExpression, Expression)`

- `Expression ReduceVariable()`

- `Expression ReduceMember()`

- `Expression ReduceIndex()`

- `LambdaExpression get_Conversion()`

- `Boolean get_IsLifted()`

- `Boolean get_IsLiftedToNull()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
public class BinaryExpression : Expression
{
	private readonly Expression <Right>k__BackingField; // 0x10
	private readonly Expression <Left>k__BackingField; // 0x18

	public override Boolean CanReduce { get; }
	public Expression Right { get; }
	public Expression Left { get; }
	public MethodInfo Method { get; }
	public LambdaExpression Conversion { get; }
	public Boolean IsLifted { get; }
	public Boolean IsLiftedToNull { get; }
	internal Boolean IsReferenceComparison { get; }

	// RVA: 0x622deb8 VA: 0x7598845eb8
	internal Void .ctor(Expression left, Expression right) { }
	// RVA: 0x622df48 VA: 0x7598845f48
	public override Boolean get_CanReduce() { }
	// RVA: 0x622df6c VA: 0x7598845f6c
	private static Boolean IsOpAssignment(ExpressionType op) { }
	// RVA: 0x622df7c VA: 0x7598845f7c
	public Expression get_Right() { }
	// RVA: 0x622df84 VA: 0x7598845f84
	public Expression get_Left() { }
	// RVA: 0x622df8c VA: 0x7598845f8c
	public MethodInfo get_Method() { }
	// RVA: 0x622df98 VA: 0x7598845f98
	internal virtual MethodInfo GetMethod() { }
	// RVA: 0x622dfa0 VA: 0x7598845fa0
	public BinaryExpression Update(Expression left, LambdaExpression conversion, Expression right) { }
	// RVA: 0x622ee74 VA: 0x7598846e74
	public override Expression Reduce() { }
	// RVA: 0x622f8b0 VA: 0x75988478b0
	private static ExpressionType GetBinaryOpFromAssignmentOp(ExpressionType op) { }
	// RVA: 0x622f7ac VA: 0x75988477ac
	private Expression ReduceVariable() { }
	// RVA: 0x622eeec VA: 0x7598846eec
	private Expression ReduceMember() { }
	// RVA: 0x622f350 VA: 0x7598847350
	private Expression ReduceIndex() { }
	// RVA: 0x622e0fc VA: 0x75988460fc
	public LambdaExpression get_Conversion() { }
	// RVA: 0x62300f8 VA: 0x75988480f8
	internal virtual LambdaExpression GetConversion() { }
	// RVA: 0x6230100 VA: 0x7598848100
	public Boolean get_IsLifted() { }
	// RVA: 0x622e4ec VA: 0x75988464ec
	public Boolean get_IsLiftedToNull() { }
	// RVA: 0x6230290 VA: 0x7598848290
	protected internal override Expression Accept(ExpressionVisitor visitor) { }
	// RVA: 0x622e108 VA: 0x7598846108
	internal Boolean get_IsReferenceComparison() { }
}
```