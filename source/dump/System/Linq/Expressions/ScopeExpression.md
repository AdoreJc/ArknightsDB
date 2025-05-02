# ScopeExpression

**Namespace:** `System.Linq.Expressions`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq.Expressions
internal class ScopeExpression : BlockExpression
{
	private IReadOnlyList`1 _variables; // 0x10

	protected IReadOnlyList`1 VariablesList { get; }

	// RVA: 0x62424c8 VA: 0x759885a4c8
	internal Void .ctor(IReadOnlyList`1 variables) { }
	// RVA: 0x62424f4 VA: 0x759885a4f4
	internal override ReadOnlyCollection`1 GetOrMakeVariables() { }
	// RVA: 0x624253c VA: 0x759885a53c
	protected IReadOnlyList`1 get_VariablesList() { }
	// RVA: 0x6242544 VA: 0x759885a544
	internal IReadOnlyList`1 ReuseOrValidateVariables(ReadOnlyCollection`1 variables) { }
}
```