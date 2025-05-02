# JsonReader

**Namespace:** `LitJson`


## Fields

- `Int32 current_input`

- `Int32 current_symbol`

- `Boolean end_of_json`

- `Boolean end_of_input`

- `Lexer lexer`

- `Boolean parser_in_string`

- `Boolean parser_return`

- `Boolean read_started`

- `TextReader reader`

- `Boolean reader_is_owned`

- `Boolean skip_non_members`

- `Object token_value`

- `JsonToken token`


## Properties

- `Boolean AllowComments`

- `Boolean AllowSingleQuotedStrings`

- `Boolean SkipNonMembers`

- `Boolean EndOfInput`

- `Boolean EndOfJson`

- `JsonToken Token`

- `Object Value`


## Methods

- `Boolean get_AllowComments()`

- `Void set_AllowComments(Boolean)`

- `Boolean get_AllowSingleQuotedStrings()`

- `Void set_AllowSingleQuotedStrings(Boolean)`

- `Boolean get_SkipNonMembers()`

- `Void set_SkipNonMembers(Boolean)`

- `Boolean get_EndOfInput()`

- `Boolean get_EndOfJson()`

- `JsonToken get_Token()`

- `Object get_Value()`

- `Void ProcessNumber(String)`

- `Void ProcessSymbol()`

- `Boolean ReadToken()`

- `Void Close()`

- `Boolean Read()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : LitJson
public class JsonReader
{
	private static IDictionary`2 parse_table; // 0x0
	private Stack`1 automaton_stack; // 0x10
	private Int32 current_input; // 0x18
	private Int32 current_symbol; // 0x1c
	private Boolean end_of_json; // 0x20
	private Boolean end_of_input; // 0x21
	private Lexer lexer; // 0x28
	private Boolean parser_in_string; // 0x30
	private Boolean parser_return; // 0x31
	private Boolean read_started; // 0x32
	private TextReader reader; // 0x38
	private Boolean reader_is_owned; // 0x40
	private Boolean skip_non_members; // 0x41
	private Object token_value; // 0x48
	private JsonToken token; // 0x50

	public Boolean AllowComments { get; set; }
	public Boolean AllowSingleQuotedStrings { get; set; }
	public Boolean SkipNonMembers { get; set; }
	public Boolean EndOfInput { get; }
	public Boolean EndOfJson { get; }
	public JsonToken Token { get; }
	public Object Value { get; }

	// RVA: 0x65f155c VA: 0x7598c0955c
	public Boolean get_AllowComments() { }
	// RVA: 0x65f1578 VA: 0x7598c09578
	public Void set_AllowComments(Boolean value) { }
	// RVA: 0x65f1598 VA: 0x7598c09598
	public Boolean get_AllowSingleQuotedStrings() { }
	// RVA: 0x65f15b4 VA: 0x7598c095b4
	public Void set_AllowSingleQuotedStrings(Boolean value) { }
	// RVA: 0x65f15d4 VA: 0x7598c095d4
	public Boolean get_SkipNonMembers() { }
	// RVA: 0x65f15dc VA: 0x7598c095dc
	public Void set_SkipNonMembers(Boolean value) { }
	// RVA: 0x65f15e8 VA: 0x7598c095e8
	public Boolean get_EndOfInput() { }
	// RVA: 0x65f15f0 VA: 0x7598c095f0
	public Boolean get_EndOfJson() { }
	// RVA: 0x65f15f8 VA: 0x7598c095f8
	public JsonToken get_Token() { }
	// RVA: 0x65f1600 VA: 0x7598c09600
	public Object get_Value() { }
	// RVA: 0x65f1608 VA: 0x7598c09608
	private static Void .cctor() { }
	// RVA: 0x65efe94 VA: 0x7598c07e94
	public Void .ctor(String json_text) { }
	// RVA: 0x65efca4 VA: 0x7598c07ca4
	public Void .ctor(TextReader reader) { }
	// RVA: 0x65f1ce8 VA: 0x7598c09ce8
	private Void .ctor(TextReader reader, Boolean owned) { }
	// RVA: 0x65f160c VA: 0x7598c0960c
	private static Void PopulateParseTable() { }
	// RVA: 0x65f20a0 VA: 0x7598c0a0a0
	private static Void TableAddCol(ParserToken row, Int32 col, Int32[] symbols) { }
	// RVA: 0x65f1f88 VA: 0x7598c09f88
	private static Void TableAddRow(ParserToken rule) { }
	// RVA: 0x65f2200 VA: 0x7598c0a200
	private Void ProcessNumber(String number) { }
	// RVA: 0x65f2370 VA: 0x7598c0a370
	private Void ProcessSymbol() { }
	// RVA: 0x65f2528 VA: 0x7598c0a528
	private Boolean ReadToken() { }
	// RVA: 0x65f2750 VA: 0x7598c0a750
	public Void Close() { }
	// RVA: 0x65ec794 VA: 0x7598c04794
	public Boolean Read() { }
}
```