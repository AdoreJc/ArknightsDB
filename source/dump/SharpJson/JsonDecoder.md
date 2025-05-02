# JsonDecoder

**Namespace:** `SharpJson`


## Fields

- `String <errorMessage>k__BackingField`

- `Boolean <parseNumbersAsFloat>k__BackingField`

- `Lexer lexer`


## Properties

- `String errorMessage`

- `Boolean parseNumbersAsFloat`


## Methods

- `String get_errorMessage()`

- `Void set_errorMessage(String)`

- `Boolean get_parseNumbersAsFloat()`

- `Void set_parseNumbersAsFloat(Boolean)`

- `Object Decode(String)`

- `Object ParseValue()`

- `Void TriggerError(String)`

- `T EvalLexer(T)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : SharpJson
public class JsonDecoder
{
	private String <errorMessage>k__BackingField; // 0x10
	private Boolean <parseNumbersAsFloat>k__BackingField; // 0x18
	private Lexer lexer; // 0x20

	public String errorMessage { get; set; }
	public Boolean parseNumbersAsFloat { get; set; }

	// RVA: 0x61c3900 VA: 0x75987db900
	public String get_errorMessage() { }
	// RVA: 0x61c3908 VA: 0x75987db908
	private Void set_errorMessage(String value) { }
	// RVA: 0x61c3910 VA: 0x75987db910
	public Boolean get_parseNumbersAsFloat() { }
	// RVA: 0x61c3918 VA: 0x75987db918
	public Void set_parseNumbersAsFloat(Boolean value) { }
	// RVA: 0x61c3924 VA: 0x75987db924
	public Void .ctor() { }
	// RVA: 0x61c3950 VA: 0x75987db950
	public Object Decode(String text) { }
	// RVA: 0x61c3c08 VA: 0x75987dbc08
	public static Object DecodeText(String text) { }
	// RVA: 0x61c3c80 VA: 0x75987dbc80
	private IDictionary`2 ParseObject() { }
	// RVA: 0x61c3f2c VA: 0x75987dbf2c
	private IList`1 ParseArray() { }
	// RVA: 0x61c39f0 VA: 0x75987db9f0
	private Object ParseValue() { }
	// RVA: 0x61c3e84 VA: 0x75987dbe84
	private Void TriggerError(String message) { }
	// RVA: 0x VA: 0x0
	private T EvalLexer(T value) { }
}
```