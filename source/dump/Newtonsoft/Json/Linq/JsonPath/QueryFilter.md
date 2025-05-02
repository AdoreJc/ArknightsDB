# QueryFilter

**Namespace:** `Newtonsoft.Json.Linq.JsonPath`


## Fields

- `QueryExpression <Expression>k__BackingField`


## Properties

- `QueryExpression Expression`


## Methods

- `QueryExpression get_Expression()`

- `Void set_Expression(QueryExpression)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq.JsonPath
internal class QueryFilter : PathFilter
{
	private QueryExpression <Expression>k__BackingField; // 0x10

	public QueryExpression Expression { get; set; }

	// RVA: 0x61a5580 VA: 0x75987bd580
	public QueryExpression get_Expression() { }
	// RVA: 0x61a5588 VA: 0x75987bd588
	public Void set_Expression(QueryExpression value) { }
	// RVA: 0x61a5590 VA: 0x75987bd590
	public override IEnumerable`1 ExecuteFilter(IEnumerable`1 current, Boolean errorWhenNoMatch) { }
	// RVA: 0x61a5660 VA: 0x75987bd660
	public Void .ctor() { }
}
```