# JPath

**Namespace:** `Newtonsoft.Json.Linq.JsonPath`


## Fields

- `Int32 _currentIndex`


## Methods

- `Void set_Filters(List`1)`

- `Void ParseMain()`

- `Boolean ParsePath(List`1, Int32, Boolean)`

- `PathFilter ParseIndexer(Char)`

- `PathFilter ParseArrayIndexer(Char)`

- `Void EatWhitespace()`

- `PathFilter ParseQuery(Char)`

- `QueryExpression ParseExpression()`

- `Object ParseValue()`

- `String ReadQuotedString()`

- `Boolean Match(String)`

- `QueryOperator ParseOperator()`

- `PathFilter ParseQuotedField(Char)`

- `Void EnsureLength(String)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq.JsonPath
internal class JPath
{
	private readonly String _expression; // 0x10
	private List`1 <Filters>k__BackingField; // 0x18
	private Int32 _currentIndex; // 0x20

	public List`1 Filters { get; set; }

	// RVA: 0x61a1110 VA: 0x75987b9110
	public List`1 get_Filters() { }
	// RVA: 0x61a1118 VA: 0x75987b9118
	private Void set_Filters(List`1 value) { }
	// RVA: 0x619a848 VA: 0x75987b2848
	public Void .ctor(String expression) { }
	// RVA: 0x61a1120 VA: 0x75987b9120
	private Void ParseMain() { }
	// RVA: 0x61a12e4 VA: 0x75987b92e4
	private Boolean ParsePath(List`1 filters, Int32 currentPartStartIndex, Boolean query) { }
	// RVA: 0x61a1974 VA: 0x75987b9974
	private PathFilter ParseIndexer(Char indexerOpenChar) { }
	// RVA: 0x61a2028 VA: 0x75987ba028
	private PathFilter ParseArrayIndexer(Char indexerCloseChar) { }
	// RVA: 0x61a1290 VA: 0x75987b9290
	private Void EatWhitespace() { }
	// RVA: 0x61a1e64 VA: 0x75987b9e64
	private PathFilter ParseQuery(Char indexerCloseChar) { }
	// RVA: 0x61a27dc VA: 0x75987ba7dc
	private QueryExpression ParseExpression() { }
	// RVA: 0x61a30b8 VA: 0x75987bb0b8
	private Object ParseValue() { }
	// RVA: 0x61a3574 VA: 0x75987bb574
	private String ReadQuotedString() { }
	// RVA: 0x61a3444 VA: 0x75987bb444
	private Boolean Match(String s) { }
	// RVA: 0x61a2ed4 VA: 0x75987baed4
	private QueryOperator ParseOperator() { }
	// RVA: 0x61a1adc VA: 0x75987b9adc
	private PathFilter ParseQuotedField(Char indexerCloseChar) { }
	// RVA: 0x61a1a68 VA: 0x75987b9a68
	private Void EnsureLength(String message) { }
	// RVA: 0x619a918 VA: 0x75987b2918
	internal IEnumerable`1 Evaluate(JToken t, Boolean errorWhenNoMatch) { }
	// RVA: 0x61a37c8 VA: 0x75987bb7c8
	internal static IEnumerable`1 Evaluate(List`1 filters, JToken t, Boolean errorWhenNoMatch) { }
}
```